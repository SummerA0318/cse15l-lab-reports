This is my grade.sh code:
```
# Create your grading script here

#set -e

CP="./lib/junit-4.13.2.jar:./lib/hamcrest-core-1.3.jar:."
CP2="../lib/junit-4.13.2.jar:../lib/hamcrest-core-1.3.jar:."

rm -rf student-submission
git clone $1 student-submission > trash.txt

if ! test -f ./student-submission/ListExamples.java; then
    echo "ListExamples.java file not found!"
    echo "Grade 0/8"
    exit 1
fi

cp TestListExamples.java ./student-submission/
javac -cp $CP ./student-submission/*.java 2> compile.txt

if [[ ! $? -eq 0 ]]
then
    echo "Compile failure"
    echo "Grade 0/8"
    exit 2
fi

cd ./student-submission/

java -cp $CP2 org.junit.runner.JUnitCore TestListExamples > test-results.txt

if [[ $? -eq 0 ]]
then
    echo "All tests pass!"
    echo "Grade 8/8"
else
    RESULT=`cat test-results.txt | grep "Failures"`
    echo $RESULT
    exit 1
fi
```

This is the output of the GradeServer when the student submission is using a wrong filename so we cannot find the file and thus giving a score of 0.

<img width="936" alt="截屏2022-11-28 上午1 22 37" src="https://user-images.githubusercontent.com/114268165/204241665-7cb961e3-f2f9-4e24-a652-a585674d4d3d.png">

This is the output of the GradeServer when the student submission has a syntax error so we cannot save and run the file and thus giving a score of 0.

<img width="956" alt="截屏2022-11-28 上午1 24 28" src="https://user-images.githubusercontent.com/114268165/204241699-797bac27-437c-47f7-8afe-080339ed7a43.png">

This is the output of the GradeServer when the student submission is using a correct filename and can compile correctly so we continue to run the tests for the submission. The student fails 2 of the 8 tests.

<img width="936" alt="截屏2022-11-28 上午1 21 51" src="https://user-images.githubusercontent.com/114268165/204241578-ce25efd5-57c9-4b72-b3b1-68ecd6770883.png">

Let's trace the first example to see how our grade.sh runs.

The first two lines are commented out so they will not be executed. The third line and the forth line are assignment statements that can run properly so they don't have output but have a return code of 0.

Then `rm -rf student-submission` removes the previously cloned student submission folder for later cloning a new folder. It has no output and have a return code of 0 because it can remove correctly.

Then `git clone $1 student-submission > trash.txt` clone the given github link to the student submission folder and store all the output into the trash.txt file to avoid printing them all out. It has a return code of 0 because it clones correctly.

Then `if ! test -f ./student-submission/ListExamples.java; then` determines if there is not a ListExamples.java file in the student's submission. In this case the student name the file wrong so we cannot find the file and thus the statement equals true and we continue the if statement. It doesn't print output but has a return code of 0 because the if statement is evaluated correctly. 

Then by the two echo statements we have the strings as the output on the webpage: "ListExamples.java file not found!" and "Grade 0/8". The two statements has a return code of 0 because they correctly print the strings out.

At last, `exit 1` has a return nonzero return code thus end running the grade.sh file. It doesn't have output.

All the later lines are not run because the code exit before them in the first if statement.
