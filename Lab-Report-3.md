I choose grep as my command and the first interesting option is `grep -i` which can search for the word without the limit of upper or lower case.

My first example is to search in all the documents in the technical folder from lab4 for the word "CHAPTER", and I get all the lines from all the txt files in the folder that contains the word while being case insensitive:

 ```
linyubing@linyubingdeMacBook-Pro lab4 % grep -i "CHAPTER" */*/*.txt
technical/911report/chapter-1.txt:    Others in the agency were aware of it, as we explained earlier in this chapter.
technical/911report/chapter-10.txt:                chapter 3). Ashcroft told us he was determined to take every conceivable action,
technical/911report/chapter-10.txt:                Iraqi intelligence officer (discussed in chapter 7) and a Polish report that
technical/911report/chapter-11.txt:                (reprinted in chapter 4), brought the focus back to more traditional hostage taking;
technical/911report/chapter-11.txt:                the main focus (war in Korea), and as too unrealistic. As we pointed out in chapter
technical/911report/chapter-11.txt:                the embassy bombings of August 1998. We described those decisions in chapter 4. It
technical/911report/chapter-11.txt:            Earlier chapters describe in detail the actions decided on by the Clinton and Bush
technical/911report/chapter-11.txt:                capabilities were in the domestic arena. In chapter 3 we discussed these
technical/911report/chapter-11.txt:                Kuala Lumpur, detailed in chapter 6. In late 1999, the National Security Agency
technical/911report/chapter-12.txt:            As we mentioned in chapter 2, Usama Bin Ladin and other Islamist terrorist leaders
technical/911report/chapter-12.txt:            Many details in chapters 2, 5, and 7 illustrate the direct and indirect value of the
technical/911report/chapter-12.txt:                dangerous weapons. As we note in chapter 2, al Qaeda has tried to acquire or make
technical/911report/chapter-12.txt:                nuclear weapons for at least ten years. In chapter 4, we mentioned officials
technical/911report/chapter-12.txt:            First, as we will discuss in chapter 13, to open up the sharing of information across
technical/911report/chapter-13.1.txt:                opportunities,"some of which we reviewed in chapter 11. These are often
technical/911report/chapter-13.1.txt:                "connecting the dots." In chapter 11 we explained that these labels are too narrow.
technical/911report/chapter-13.1.txt:                    described in chapter 12.
technical/911report/chapter-13.1.txt:                still not sized or funded to be an executive agency. In chapter 3 we described some
technical/911report/chapter-13.1.txt:                regions, countries, and issues that we discuss in chapter 12. Much of the job of
technical/911report/chapter-13.1.txt:            We summarized the resulting organization of the intelligence community in chapter 3.
technical/911report/chapter-13.1.txt:                    civil-military misunderstandings we described in chapter 4. It is a problem to
technical/911report/chapter-13.1.txt:                describe in chapter 8, the information is distributed, but in a compartmented
technical/911report/chapter-13.1.txt:            In chapter 6, we described the transition of 2000-2001. Beyond the policy issues we
technical/911report/chapter-13.1.txt:                all-out effort to institutionalize change-can do the job. As we mentioned in chapter
technical/911report/chapter-13.2.txt:                requests, Mar. 15, 2004. 452 NOTES TO CHAPTER 1
technical/911report/chapter-13.2.txt:                2001. 454 NOTES TO CHAPTER 1
technical/911report/chapter-13.3.txt:                129-137. 468 NOTES TO CHAPTER 2
technical/911report/chapter-13.3.txt:                Division," Apr. 22,1999. For the 1998-2001 numNOTES TO CHAPTER 3 473 bers, see DOJ
technical/911report/chapter-13.3.txt:                Chapter 8.
technical/911report/chapter-13.3.txt:                "Counterterrorism/National SecuNOTES TO CHAPTER 3 475 rity Strategy and Casework
technical/911report/chapter-13.3.txt:                summarized in chapter 2.
technical/911report/chapter-13.3.txt:            486 NOTES TO CHAPTER 4
technical/911report/chapter-13.4.txt:                in chapter 2, we do not agree with this assessment. On Bin Ladin's reactions to
technical/911report/chapter-13.4.txt:                interrogations of KSM, Aug. 18, 2003; Feb. 19, 2004. 492 NOTES TO CHAPTER 5
technical/911report/chapter-13.4.txt:                CHAPTER 5
technical/911report/chapter-13.4.txt:                of Penttbom InvestiNOTES TO CHAPTER 5 497 gation," Feb. 29, 2004, p. 78. Ali, in
technical/911report/chapter-13.4.txt:                CHAPTER 5 499 ist acts were interrupted as a result. For al Qaeda expenditures, see,
technical/911report/chapter-13.4.txt:                for the record, July 13, 2004. As discussed in chapter 7, we have examined three
technical/911report/chapter-13.4.txt:                August 1998 and July 1999 MONs as relevant preceNOTES TO CHAPTER 6 501
technical/911report/chapter-13.4.txt:                p. 124). 502 NOTES TO CHAPTER 6
technical/911report/chapter-13.4.txt:                chapter 8. That was not known at the time. Mihdhar was met at the Kuala Lumpur
technical/911report/chapter-13.4.txt:                come back to either President Clinton or PresNOTES TO CHAPTER 6 509 ident Bush and
technical/911report/chapter-13.4.txt:                interview (Feb. 24, 2004). 512 NOTES TO CHAPTER 6
technical/911report/chapter-13.4.txt:            234. In chapter 3, we discuss how this problem arose. By 2001, it had become worse.
technical/911report/chapter-13.4.txt:            5. Notably, as discussed in chapter 5, precisely such arrangements-in the form of
technical/911report/chapter-13.4.txt:                chapter
technical/911report/chapter-13.4.txt:                is referred to as the "Phoenix memo," discussed in chapter 8.) For Hanjour obtaining
technical/911report/chapter-13.4.txt:                later in this chapter, may have had a role in recruiting one or more of the muscle
technical/911report/chapter-13.4.txt:                2003. KSM does acknowlNOTES TO CHAPTER 7 525 edge that the commander of al Faruq
technical/911report/chapter-13.5.txt:                the number of hijackers. As discussed later in this chapter, he was refused entry.
technical/911report/chapter-13.5.txt:            530 NOTES TO CHAPTER 7
technical/911report/chapter-13.5.txt:                operation. See chapter 5.2. He has also stated that Atta included a nuclear plant in
technical/911report/chapter-13.5.txt:                1998, hijacking article (in chapter 4) and the August 6, 2001, article discussing
technical/911report/chapter-13.5.txt:                Bin Ladin's plans to attack in the United States (in this chapter)-were eventually
technical/911report/chapter-13.5.txt:                CIA cable, follow-up source on KSM, July 11, 2001. As noted in chapter 7, KSM has
technical/911report/chapter-13.5.txt:                2002. For the views of the FBI investigators, see DOJ InspecNOTES TO CHAPTER 8 537
technical/911report/chapter-13.5.txt:                discussed in chapter 3, and specifically from a March 1995 memorandum of then Deputy
technical/911report/chapter-13.5.txt:                through the OIPR screen. What had happened, as we discussed in chapter 3, was a
technical/911report/chapter-13.5.txt:                regulations, "Regulations" chapter of "Operational Procedures and Policies," July
technical/911report/chapter-13.5.txt:                Company Operations" chapters of "Operational Procedures and Policies," July 1999.
technical/911report/chapter-13.5.txt:            23. FDNY regulations, "Communications" chapter of "Operational Procedures and
technical/911report/chapter-13.5.txt:            558 NOTES TO CHAPTER 10
technical/911report/chapter-13.5.txt:                review contacts between Iraq and al Qaeda in chapter 2. We have found no credible
technical/911report/chapter-13.5.txt:            15. For Murad's idea, see chapter 5, note 33.
technical/911report/chapter-13.5.txt:                perNOTES TO CHAPTER 12 565 haps cyclical economic factors. For the cost to the
technical/911report/chapter-13.5.txt:                National Intelligence Director we recommend later in this chapter.
technical/911report/chapter-2.txt:                airliners over the Pacific. Details on these plots appear in chapter 3.
technical/911report/chapter-2.txt:                in chapter 7, al Qaeda contacts with Iran continued in ensuing years.
technical/911report/chapter-3.txt:            In chapter 2, we described the growth of a new kind of terrorism, and a new terrorist
technical/911report/chapter-3.txt:                organized the bombing of two U.S. embassies. In this chapter, we trace the parallel
technical/911report/chapter-3.txt:                institutional beliefs and practices in chapter 8.
technical/911report/chapter-3.txt:                chapter 6, questioning by an especially alert Customs inspector led to the arrest of
technical/911report/chapter-3.txt:            Subsequent chapters will raise the issue of whether, despite tremendous talent,
technical/911report/chapter-3.txt:                (Timothy Mc Veigh in Oklahoma City). As we pointed out in chapter 3, the White House
technical/911report/chapter-5.txt:                Karachi; Mihdhar traveled from Yemen. As discussed in chapter 6, U.S. intelligence
technical/911report/chapter-5.txt:                plot, even as late as the summer of 2001, as discussed in chapter 7.
technical/911report/chapter-5.txt:            As we explained in chapter 2, Bin Ladin did not fund al Qaeda through a personal
technical/911report/chapter-5.txt:                discussed in more detail in chapter 7.
technical/911report/chapter-6.txt:            In chapters 3 and 4 we described how the U.S. government adjusted its existing
technical/911report/chapter-6.txt:                mind for the millennium period. In chapter 5 we introduced an al Qaeda operative
technical/911report/chapter-6.txt:            In chapter 5, we discussed the dispatch of two operatives to the United States for
technical/911report/chapter-6.txt:                reignited interest in Khallad. We will return to that story in chapter 8.
technical/911report/chapter-6.txt:                government since 1999 and, as we mentioned in chapter 4, the U.S. government as a
technical/911report/chapter-6.txt:            As discussed in chapter 4, plans of this kind were never carried out before 9/11.
technical/911report/chapter-6.txt:            Early in chapter 5 we introduced, along with Khalid Sheikh Mohammed, two other men
technical/911report/chapter-6.txt:                terrorism surged dramatically. In chapter 8, we will explore this reporting and the
technical/911report/chapter-7.txt:            In chapter 5 we described the Southeast Asia travels of Nawaf al Hazmi, Khalid al
technical/911report/chapter-7.txt:                that chapter we also described how Mihdhar was spotted in Kuala Lumpur early in
technical/911report/chapter-7.txt:                asked Khallad (whom we introduced in chapter 5) to maintain email contact with Hazmi
technical/911report/chapter-7.txt:            As we mentioned in chapter 2, while in Sudan, senior managers in al Qaeda maintained
technical/911report/chapter-8.txt:                to locate him. As pointed out in chapter 6, Abu Zubaydah had been a major figure in
technical/911report/chapter-8.txt:                the plot. As seen in chapter 7, al Qaeda's operatives made mistakes. At least two
technical/911report/chapter-8.txt:            In chapter 6 we discussed how intelligence agencies successfully detected some of the
technical/911report/chapter-8.txt:                bombing (we introduced Khallad in chapter 5, and returned to his role in the Cole
technical/911report/chapter-8.txt:                bombing in chapter 6).55 One of the members of the FBI's investigative team in Yemen
technical/911report/chapter-8.txt:                investigation on Zacarias Moussaoui. As mentioned in chapter 7, he had entered the
technical/911report/chapter-8.txt:                chapter 7, Moussaoui had been in contact with and received money from Ramzi
technical/911report/chapter-8.txt:                Surveillance Act to conduct the search (we introduced FISA in chapter 3).
technical/911report/chapter-8.txt:                Moussaoui, as discussed in chapter 7. As in the Moussaoui situation already
technical/911report/chapter-9.txt:            Like the national defense effort described in chapter 1, the emergency response to
technical/biomed/1472-6947-1-6.txt:          chapters in books. The authors of primary studies
technical/plos/journal.pbio.0020010.txt:        Roger Schonfeld ends his very detailed description of JSTOR with a chapter on ‘Lessons
technical/plos/journal.pbio.0020067.txt:        The Double Helix . The final chapter of his own autobiography addresses
technical/plos/journal.pbio.0020071.txt:        classic text on evolution (1998) contains 26 chapters totaling 763 pages. To cover the
technical/plos/journal.pbio.0020071.txt:        topic in only eight chapters and 145 pages, as the Charlesworths have done in 
technical/plos/journal.pbio.0020071.txt:        In Chapter 7, the authors discuss five topics that have traditionally been hard to
technical/plos/journal.pbio.0020071.txt:        evolution (Chapter 3) and subsequently discuss evidence from the geographical distributions
technical/plos/journal.pbio.0020071.txt:        of living and fossil species (Chapter 4). My first impression was that this part occupies
technical/plos/journal.pbio.0020071.txt:        too large a proportion of the book. However, Chapter 3 serves as a good introduction to the
technical/plos/journal.pbio.0020112.txt:        his concluding chapters. He emphasises the need to continually review the evidence
technical/plos/journal.pbio.0020116.txt:        the title of Chapter 4 of the report, “Ageless Bodies,” implies that immortality is the
technical/plos/journal.pbio.0020116.txt:        title is not consistent with the knowledge, stated in that chapter, that there is no
technical/plos/journal.pbio.0020116.txt:        immortality. Hence, this chapter in the report falls short of explaining the serious
technical/plos/journal.pbio.0020116.txt:        The same chapter offers a sensational quote from a researcher that “the real goal [of
technical/plos/journal.pbio.0020145.txt:        membrane structure, protein structure, and signal transduction in Chapters 5, 12, and 15,
technical/plos/journal.pbio.0020147.txt:        conclusions are sparse. We guess the aim of the chapter is to illustrate that environmental
technical/plos/journal.pbio.0020187.txt:        consumption in pensions and health care; most chapters focus on the United States, but the
technical/plos/journal.pbio.0020187.txt:        closing chapter discusses these issues in a global context. Each essay is followed by a
technical/plos/journal.pbio.0020419.txt:        Francis is captured in the final chapter of Marr's now classic book “Vision” (Marr 1982).
technical/plos/journal.pbio.0020439.txt:        or so naturally occurring elements (Shipman et al. 2003; chapter 21 estimates 2,000
technical/plos/journal.pbio.0020439.txt:        Nine Chapters of the Mathematical Art ; Smoller 2001). In the 19th
technical/plos/journal.pbio.0030062.txt:        Speciation and the nonmathematical final chapter (“General Conclusions”)
```

Then I search in all the documents in the 911 folder in technical for "CHAPTER" with same command. This time I get all the lines from all the txt files in 911report that contains the word while being case insensitive:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -i "CHAPTER" */911report/*.txt
technical/911report/chapter-1.txt:    Others in the agency were aware of it, as we explained earlier in this chapter.
technical/911report/chapter-10.txt:                chapter 3). Ashcroft told us he was determined to take every conceivable action,
technical/911report/chapter-10.txt:                Iraqi intelligence officer (discussed in chapter 7) and a Polish report that
technical/911report/chapter-11.txt:                (reprinted in chapter 4), brought the focus back to more traditional hostage taking;
technical/911report/chapter-11.txt:                the main focus (war in Korea), and as too unrealistic. As we pointed out in chapter
technical/911report/chapter-11.txt:                the embassy bombings of August 1998. We described those decisions in chapter 4. It
technical/911report/chapter-11.txt:            Earlier chapters describe in detail the actions decided on by the Clinton and Bush
technical/911report/chapter-11.txt:                capabilities were in the domestic arena. In chapter 3 we discussed these
technical/911report/chapter-11.txt:                Kuala Lumpur, detailed in chapter 6. In late 1999, the National Security Agency
technical/911report/chapter-12.txt:            As we mentioned in chapter 2, Usama Bin Ladin and other Islamist terrorist leaders
technical/911report/chapter-12.txt:            Many details in chapters 2, 5, and 7 illustrate the direct and indirect value of the
technical/911report/chapter-12.txt:                dangerous weapons. As we note in chapter 2, al Qaeda has tried to acquire or make
technical/911report/chapter-12.txt:                nuclear weapons for at least ten years. In chapter 4, we mentioned officials
technical/911report/chapter-12.txt:            First, as we will discuss in chapter 13, to open up the sharing of information across
technical/911report/chapter-13.1.txt:                opportunities,"some of which we reviewed in chapter 11. These are often
technical/911report/chapter-13.1.txt:                "connecting the dots." In chapter 11 we explained that these labels are too narrow.
technical/911report/chapter-13.1.txt:                    described in chapter 12.
technical/911report/chapter-13.1.txt:                still not sized or funded to be an executive agency. In chapter 3 we described some
technical/911report/chapter-13.1.txt:                regions, countries, and issues that we discuss in chapter 12. Much of the job of
technical/911report/chapter-13.1.txt:            We summarized the resulting organization of the intelligence community in chapter 3.
technical/911report/chapter-13.1.txt:                    civil-military misunderstandings we described in chapter 4. It is a problem to
technical/911report/chapter-13.1.txt:                describe in chapter 8, the information is distributed, but in a compartmented
technical/911report/chapter-13.1.txt:            In chapter 6, we described the transition of 2000-2001. Beyond the policy issues we
technical/911report/chapter-13.1.txt:                all-out effort to institutionalize change-can do the job. As we mentioned in chapter
technical/911report/chapter-13.2.txt:                requests, Mar. 15, 2004. 452 NOTES TO CHAPTER 1
technical/911report/chapter-13.2.txt:                2001. 454 NOTES TO CHAPTER 1
technical/911report/chapter-13.3.txt:                129-137. 468 NOTES TO CHAPTER 2
technical/911report/chapter-13.3.txt:                Division," Apr. 22,1999. For the 1998-2001 numNOTES TO CHAPTER 3 473 bers, see DOJ
technical/911report/chapter-13.3.txt:                Chapter 8.
technical/911report/chapter-13.3.txt:                "Counterterrorism/National SecuNOTES TO CHAPTER 3 475 rity Strategy and Casework
technical/911report/chapter-13.3.txt:                summarized in chapter 2.
technical/911report/chapter-13.3.txt:            486 NOTES TO CHAPTER 4
technical/911report/chapter-13.4.txt:                in chapter 2, we do not agree with this assessment. On Bin Ladin's reactions to
technical/911report/chapter-13.4.txt:                interrogations of KSM, Aug. 18, 2003; Feb. 19, 2004. 492 NOTES TO CHAPTER 5
technical/911report/chapter-13.4.txt:                CHAPTER 5
technical/911report/chapter-13.4.txt:                of Penttbom InvestiNOTES TO CHAPTER 5 497 gation," Feb. 29, 2004, p. 78. Ali, in
technical/911report/chapter-13.4.txt:                CHAPTER 5 499 ist acts were interrupted as a result. For al Qaeda expenditures, see,
technical/911report/chapter-13.4.txt:                for the record, July 13, 2004. As discussed in chapter 7, we have examined three
technical/911report/chapter-13.4.txt:                August 1998 and July 1999 MONs as relevant preceNOTES TO CHAPTER 6 501
technical/911report/chapter-13.4.txt:                p. 124). 502 NOTES TO CHAPTER 6
technical/911report/chapter-13.4.txt:                chapter 8. That was not known at the time. Mihdhar was met at the Kuala Lumpur
technical/911report/chapter-13.4.txt:                come back to either President Clinton or PresNOTES TO CHAPTER 6 509 ident Bush and
technical/911report/chapter-13.4.txt:                interview (Feb. 24, 2004). 512 NOTES TO CHAPTER 6
technical/911report/chapter-13.4.txt:            234. In chapter 3, we discuss how this problem arose. By 2001, it had become worse.
technical/911report/chapter-13.4.txt:            5. Notably, as discussed in chapter 5, precisely such arrangements-in the form of
technical/911report/chapter-13.4.txt:                chapter
technical/911report/chapter-13.4.txt:                is referred to as the "Phoenix memo," discussed in chapter 8.) For Hanjour obtaining
technical/911report/chapter-13.4.txt:                later in this chapter, may have had a role in recruiting one or more of the muscle
technical/911report/chapter-13.4.txt:                2003. KSM does acknowlNOTES TO CHAPTER 7 525 edge that the commander of al Faruq
technical/911report/chapter-13.5.txt:                the number of hijackers. As discussed later in this chapter, he was refused entry.
technical/911report/chapter-13.5.txt:            530 NOTES TO CHAPTER 7
technical/911report/chapter-13.5.txt:                operation. See chapter 5.2. He has also stated that Atta included a nuclear plant in
technical/911report/chapter-13.5.txt:                1998, hijacking article (in chapter 4) and the August 6, 2001, article discussing
technical/911report/chapter-13.5.txt:                Bin Ladin's plans to attack in the United States (in this chapter)-were eventually
technical/911report/chapter-13.5.txt:                CIA cable, follow-up source on KSM, July 11, 2001. As noted in chapter 7, KSM has
technical/911report/chapter-13.5.txt:                2002. For the views of the FBI investigators, see DOJ InspecNOTES TO CHAPTER 8 537
technical/911report/chapter-13.5.txt:                discussed in chapter 3, and specifically from a March 1995 memorandum of then Deputy
technical/911report/chapter-13.5.txt:                through the OIPR screen. What had happened, as we discussed in chapter 3, was a
technical/911report/chapter-13.5.txt:                regulations, "Regulations" chapter of "Operational Procedures and Policies," July
technical/911report/chapter-13.5.txt:                Company Operations" chapters of "Operational Procedures and Policies," July 1999.
technical/911report/chapter-13.5.txt:            23. FDNY regulations, "Communications" chapter of "Operational Procedures and
technical/911report/chapter-13.5.txt:            558 NOTES TO CHAPTER 10
technical/911report/chapter-13.5.txt:                review contacts between Iraq and al Qaeda in chapter 2. We have found no credible
technical/911report/chapter-13.5.txt:            15. For Murad's idea, see chapter 5, note 33.
technical/911report/chapter-13.5.txt:                perNOTES TO CHAPTER 12 565 haps cyclical economic factors. For the cost to the
technical/911report/chapter-13.5.txt:                National Intelligence Director we recommend later in this chapter.
technical/911report/chapter-2.txt:                airliners over the Pacific. Details on these plots appear in chapter 3.
technical/911report/chapter-2.txt:                in chapter 7, al Qaeda contacts with Iran continued in ensuing years.
technical/911report/chapter-3.txt:            In chapter 2, we described the growth of a new kind of terrorism, and a new terrorist
technical/911report/chapter-3.txt:                organized the bombing of two U.S. embassies. In this chapter, we trace the parallel
technical/911report/chapter-3.txt:                institutional beliefs and practices in chapter 8.
technical/911report/chapter-3.txt:                chapter 6, questioning by an especially alert Customs inspector led to the arrest of
technical/911report/chapter-3.txt:            Subsequent chapters will raise the issue of whether, despite tremendous talent,
technical/911report/chapter-3.txt:                (Timothy Mc Veigh in Oklahoma City). As we pointed out in chapter 3, the White House
technical/911report/chapter-5.txt:                Karachi; Mihdhar traveled from Yemen. As discussed in chapter 6, U.S. intelligence
technical/911report/chapter-5.txt:                plot, even as late as the summer of 2001, as discussed in chapter 7.
technical/911report/chapter-5.txt:            As we explained in chapter 2, Bin Ladin did not fund al Qaeda through a personal
technical/911report/chapter-5.txt:                discussed in more detail in chapter 7.
technical/911report/chapter-6.txt:            In chapters 3 and 4 we described how the U.S. government adjusted its existing
technical/911report/chapter-6.txt:                mind for the millennium period. In chapter 5 we introduced an al Qaeda operative
technical/911report/chapter-6.txt:            In chapter 5, we discussed the dispatch of two operatives to the United States for
technical/911report/chapter-6.txt:                reignited interest in Khallad. We will return to that story in chapter 8.
technical/911report/chapter-6.txt:                government since 1999 and, as we mentioned in chapter 4, the U.S. government as a
technical/911report/chapter-6.txt:            As discussed in chapter 4, plans of this kind were never carried out before 9/11.
technical/911report/chapter-6.txt:            Early in chapter 5 we introduced, along with Khalid Sheikh Mohammed, two other men
technical/911report/chapter-6.txt:                terrorism surged dramatically. In chapter 8, we will explore this reporting and the
technical/911report/chapter-7.txt:            In chapter 5 we described the Southeast Asia travels of Nawaf al Hazmi, Khalid al
technical/911report/chapter-7.txt:                that chapter we also described how Mihdhar was spotted in Kuala Lumpur early in
technical/911report/chapter-7.txt:                asked Khallad (whom we introduced in chapter 5) to maintain email contact with Hazmi
technical/911report/chapter-7.txt:            As we mentioned in chapter 2, while in Sudan, senior managers in al Qaeda maintained
technical/911report/chapter-8.txt:                to locate him. As pointed out in chapter 6, Abu Zubaydah had been a major figure in
technical/911report/chapter-8.txt:                the plot. As seen in chapter 7, al Qaeda's operatives made mistakes. At least two
technical/911report/chapter-8.txt:            In chapter 6 we discussed how intelligence agencies successfully detected some of the
technical/911report/chapter-8.txt:                bombing (we introduced Khallad in chapter 5, and returned to his role in the Cole
technical/911report/chapter-8.txt:                bombing in chapter 6).55 One of the members of the FBI's investigative team in Yemen
technical/911report/chapter-8.txt:                investigation on Zacarias Moussaoui. As mentioned in chapter 7, he had entered the
technical/911report/chapter-8.txt:                chapter 7, Moussaoui had been in contact with and received money from Ramzi
technical/911report/chapter-8.txt:                Surveillance Act to conduct the search (we introduced FISA in chapter 3).
technical/911report/chapter-8.txt:                Moussaoui, as discussed in chapter 7. As in the Moussaoui situation already
technical/911report/chapter-9.txt:            Like the national defense effort described in chapter 1, the emergency response to
```

At last I search in the documents chapter-11.txt in the 911report folder for word "CHAPTER", and I get all the lines in the txt file that contains the word while being case insensitive:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -i "CHAPTER" */*/chapter-11.txt
                (reprinted in chapter 4), brought the focus back to more traditional hostage taking;
                the main focus (war in Korea), and as too unrealistic. As we pointed out in chapter
                the embassy bombings of August 1998. We described those decisions in chapter 4. It
            Earlier chapters describe in detail the actions decided on by the Clinton and Bush
                capabilities were in the domestic arena. In chapter 3 we discussed these
                Kuala Lumpur, detailed in chapter 6. In late 1999, the National Security Agency
```



The second interesting option is `grep -c` which counts the lines containing the required part in a file while being case sensitive.

My first example is to search in all the documents in the 911report folder for word "chapter", and I get the number of lines containing the word for all txt files in that folder while being case sensitive:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -c "chapter" */911report/*.txt
technical/911report/chapter-1.txt:1
technical/911report/chapter-10.txt:2
technical/911report/chapter-11.txt:6
technical/911report/chapter-12.txt:5
technical/911report/chapter-13.1.txt:10
technical/911report/chapter-13.2.txt:0
technical/911report/chapter-13.3.txt:1
technical/911report/chapter-13.4.txt:8
technical/911report/chapter-13.5.txt:13
technical/911report/chapter-2.txt:2
technical/911report/chapter-3.txt:6
technical/911report/chapter-5.txt:4
technical/911report/chapter-6.txt:8
technical/911report/chapter-7.txt:4
technical/911report/chapter-8.txt:9
technical/911report/chapter-9.txt:1
technical/911report/preface.txt:0
```

Then I search in all the documents in the 911report folder again but for word "CHAPTER". Since `grep -c` is case sensitive, I get the number of lines containing the word for all txt files in that folder again but get different numbers:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -c "CHAPTER" */911report/*.txt
technical/911report/chapter-1.txt:0
technical/911report/chapter-10.txt:0
technical/911report/chapter-11.txt:0
technical/911report/chapter-12.txt:0
technical/911report/chapter-13.1.txt:0
technical/911report/chapter-13.2.txt:2
technical/911report/chapter-13.3.txt:4
technical/911report/chapter-13.4.txt:9
technical/911report/chapter-13.5.txt:4
technical/911report/chapter-2.txt:0
technical/911report/chapter-3.txt:0
technical/911report/chapter-5.txt:0
technical/911report/chapter-6.txt:0
technical/911report/chapter-7.txt:0
technical/911report/chapter-8.txt:0
technical/911report/chapter-9.txt:0
technical/911report/preface.txt:0
```

At last I search in all the documents in the 911report folder for word "Chapter" and get different numbers for the number of lines containing the word for all txt files again:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -c "Chapter" */911report/*.txt
technical/911report/chapter-1.txt:0
technical/911report/chapter-10.txt:0
technical/911report/chapter-11.txt:0
technical/911report/chapter-12.txt:0
technical/911report/chapter-13.1.txt:0
technical/911report/chapter-13.2.txt:0
technical/911report/chapter-13.3.txt:1
technical/911report/chapter-13.4.txt:0
technical/911report/chapter-13.5.txt:0
technical/911report/chapter-2.txt:0
technical/911report/chapter-3.txt:0
technical/911report/chapter-5.txt:0
technical/911report/chapter-6.txt:0
technical/911report/chapter-7.txt:0
technical/911report/chapter-8.txt:0
technical/911report/chapter-9.txt:0
technical/911report/preface.txt:0
```

The last command I choose is `grep -w` which counts for a case sensitive word as well but only pick those which is at the beginning of the line or preceded by a non-word constituent character.

I firstly count word "chapter" in the 911report folder with the command:

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -w "chapter" */*/*.txt         
technical/911report/chapter-1.txt:    Others in the agency were aware of it, as we explained earlier in this chapter.
technical/911report/chapter-10.txt:                chapter 3). Ashcroft told us he was determined to take every conceivable action,
technical/911report/chapter-10.txt:                Iraqi intelligence officer (discussed in chapter 7) and a Polish report that
technical/911report/chapter-11.txt:                (reprinted in chapter 4), brought the focus back to more traditional hostage taking;
technical/911report/chapter-11.txt:                the main focus (war in Korea), and as too unrealistic. As we pointed out in chapter
technical/911report/chapter-11.txt:                the embassy bombings of August 1998. We described those decisions in chapter 4. It
technical/911report/chapter-11.txt:                capabilities were in the domestic arena. In chapter 3 we discussed these
technical/911report/chapter-11.txt:                Kuala Lumpur, detailed in chapter 6. In late 1999, the National Security Agency
technical/911report/chapter-12.txt:            As we mentioned in chapter 2, Usama Bin Ladin and other Islamist terrorist leaders
technical/911report/chapter-12.txt:                dangerous weapons. As we note in chapter 2, al Qaeda has tried to acquire or make
technical/911report/chapter-12.txt:                nuclear weapons for at least ten years. In chapter 4, we mentioned officials
technical/911report/chapter-12.txt:            First, as we will discuss in chapter 13, to open up the sharing of information across
technical/911report/chapter-13.1.txt:                opportunities,"some of which we reviewed in chapter 11. These are often
technical/911report/chapter-13.1.txt:                "connecting the dots." In chapter 11 we explained that these labels are too narrow.
technical/911report/chapter-13.1.txt:                    described in chapter 12.
technical/911report/chapter-13.1.txt:                still not sized or funded to be an executive agency. In chapter 3 we described some
technical/911report/chapter-13.1.txt:                regions, countries, and issues that we discuss in chapter 12. Much of the job of
technical/911report/chapter-13.1.txt:            We summarized the resulting organization of the intelligence community in chapter 3.
technical/911report/chapter-13.1.txt:                    civil-military misunderstandings we described in chapter 4. It is a problem to
technical/911report/chapter-13.1.txt:                describe in chapter 8, the information is distributed, but in a compartmented
technical/911report/chapter-13.1.txt:            In chapter 6, we described the transition of 2000-2001. Beyond the policy issues we
technical/911report/chapter-13.1.txt:                all-out effort to institutionalize change-can do the job. As we mentioned in chapter
technical/911report/chapter-13.3.txt:                summarized in chapter 2.
technical/911report/chapter-13.4.txt:                in chapter 2, we do not agree with this assessment. On Bin Ladin's reactions to
technical/911report/chapter-13.4.txt:                for the record, July 13, 2004. As discussed in chapter 7, we have examined three
technical/911report/chapter-13.4.txt:                chapter 8. That was not known at the time. Mihdhar was met at the Kuala Lumpur
technical/911report/chapter-13.4.txt:            234. In chapter 3, we discuss how this problem arose. By 2001, it had become worse.
technical/911report/chapter-13.4.txt:            5. Notably, as discussed in chapter 5, precisely such arrangements-in the form of
technical/911report/chapter-13.4.txt:                chapter
technical/911report/chapter-13.4.txt:                is referred to as the "Phoenix memo," discussed in chapter 8.) For Hanjour obtaining
technical/911report/chapter-13.4.txt:                later in this chapter, may have had a role in recruiting one or more of the muscle
technical/911report/chapter-13.5.txt:                the number of hijackers. As discussed later in this chapter, he was refused entry.
technical/911report/chapter-13.5.txt:                operation. See chapter 5.2. He has also stated that Atta included a nuclear plant in
technical/911report/chapter-13.5.txt:                1998, hijacking article (in chapter 4) and the August 6, 2001, article discussing
technical/911report/chapter-13.5.txt:                Bin Ladin's plans to attack in the United States (in this chapter)-were eventually
technical/911report/chapter-13.5.txt:                CIA cable, follow-up source on KSM, July 11, 2001. As noted in chapter 7, KSM has
technical/911report/chapter-13.5.txt:                discussed in chapter 3, and specifically from a March 1995 memorandum of then Deputy
technical/911report/chapter-13.5.txt:                through the OIPR screen. What had happened, as we discussed in chapter 3, was a
technical/911report/chapter-13.5.txt:                regulations, "Regulations" chapter of "Operational Procedures and Policies," July
technical/911report/chapter-13.5.txt:            23. FDNY regulations, "Communications" chapter of "Operational Procedures and
technical/911report/chapter-13.5.txt:                review contacts between Iraq and al Qaeda in chapter 2. We have found no credible
technical/911report/chapter-13.5.txt:            15. For Murad's idea, see chapter 5, note 33.
technical/911report/chapter-13.5.txt:                National Intelligence Director we recommend later in this chapter.
technical/911report/chapter-2.txt:                airliners over the Pacific. Details on these plots appear in chapter 3.
technical/911report/chapter-2.txt:                in chapter 7, al Qaeda contacts with Iran continued in ensuing years.
technical/911report/chapter-3.txt:            In chapter 2, we described the growth of a new kind of terrorism, and a new terrorist
technical/911report/chapter-3.txt:                organized the bombing of two U.S. embassies. In this chapter, we trace the parallel
technical/911report/chapter-3.txt:                institutional beliefs and practices in chapter 8.
technical/911report/chapter-3.txt:                chapter 6, questioning by an especially alert Customs inspector led to the arrest of
technical/911report/chapter-3.txt:                (Timothy Mc Veigh in Oklahoma City). As we pointed out in chapter 3, the White House
technical/911report/chapter-5.txt:                Karachi; Mihdhar traveled from Yemen. As discussed in chapter 6, U.S. intelligence
technical/911report/chapter-5.txt:                plot, even as late as the summer of 2001, as discussed in chapter 7.
technical/911report/chapter-5.txt:            As we explained in chapter 2, Bin Ladin did not fund al Qaeda through a personal
technical/911report/chapter-5.txt:                discussed in more detail in chapter 7.
technical/911report/chapter-6.txt:                mind for the millennium period. In chapter 5 we introduced an al Qaeda operative
technical/911report/chapter-6.txt:            In chapter 5, we discussed the dispatch of two operatives to the United States for
technical/911report/chapter-6.txt:                reignited interest in Khallad. We will return to that story in chapter 8.
technical/911report/chapter-6.txt:                government since 1999 and, as we mentioned in chapter 4, the U.S. government as a
technical/911report/chapter-6.txt:            As discussed in chapter 4, plans of this kind were never carried out before 9/11.
technical/911report/chapter-6.txt:            Early in chapter 5 we introduced, along with Khalid Sheikh Mohammed, two other men
technical/911report/chapter-6.txt:                terrorism surged dramatically. In chapter 8, we will explore this reporting and the
technical/911report/chapter-7.txt:            In chapter 5 we described the Southeast Asia travels of Nawaf al Hazmi, Khalid al
technical/911report/chapter-7.txt:                that chapter we also described how Mihdhar was spotted in Kuala Lumpur early in
technical/911report/chapter-7.txt:                asked Khallad (whom we introduced in chapter 5) to maintain email contact with Hazmi
technical/911report/chapter-7.txt:            As we mentioned in chapter 2, while in Sudan, senior managers in al Qaeda maintained
technical/911report/chapter-8.txt:                to locate him. As pointed out in chapter 6, Abu Zubaydah had been a major figure in
technical/911report/chapter-8.txt:                the plot. As seen in chapter 7, al Qaeda's operatives made mistakes. At least two
technical/911report/chapter-8.txt:            In chapter 6 we discussed how intelligence agencies successfully detected some of the
technical/911report/chapter-8.txt:                bombing (we introduced Khallad in chapter 5, and returned to his role in the Cole
technical/911report/chapter-8.txt:                bombing in chapter 6).55 One of the members of the FBI's investigative team in Yemen
technical/911report/chapter-8.txt:                investigation on Zacarias Moussaoui. As mentioned in chapter 7, he had entered the
technical/911report/chapter-8.txt:                chapter 7, Moussaoui had been in contact with and received money from Ramzi
technical/911report/chapter-8.txt:                Surveillance Act to conduct the search (we introduced FISA in chapter 3).
technical/911report/chapter-8.txt:                Moussaoui, as discussed in chapter 7. As in the Moussaoui situation already
technical/911report/chapter-9.txt:            Like the national defense effort described in chapter 1, the emergency response to
technical/plos/journal.pbio.0020010.txt:        Roger Schonfeld ends his very detailed description of JSTOR with a chapter on ‘Lessons
technical/plos/journal.pbio.0020067.txt:        The Double Helix . The final chapter of his own autobiography addresses
technical/plos/journal.pbio.0020116.txt:        title is not consistent with the knowledge, stated in that chapter, that there is no
technical/plos/journal.pbio.0020116.txt:        immortality. Hence, this chapter in the report falls short of explaining the serious
technical/plos/journal.pbio.0020116.txt:        The same chapter offers a sensational quote from a researcher that “the real goal [of
technical/plos/journal.pbio.0020147.txt:        conclusions are sparse. We guess the aim of the chapter is to illustrate that environmental
technical/plos/journal.pbio.0020187.txt:        closing chapter discusses these issues in a global context. Each essay is followed by a
technical/plos/journal.pbio.0020419.txt:        Francis is captured in the final chapter of Marr's now classic book “Vision” (Marr 1982).
technical/plos/journal.pbio.0020439.txt:        or so naturally occurring elements (Shipman et al. 2003; chapter 21 estimates 2,000
technical/plos/journal.pbio.0030062.txt:        Speciation and the nonmathematical final chapter (“General Conclusions”)
```

Then I count it in specifically chapter-13.5.txt in 911report folder for the same condition again.

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -w "chapter" */*/chapter-13.5.txt
                the number of hijackers. As discussed later in this chapter, he was refused entry.
                operation. See chapter 5.2. He has also stated that Atta included a nuclear plant in
                1998, hijacking article (in chapter 4) and the August 6, 2001, article discussing
                Bin Ladin's plans to attack in the United States (in this chapter)-were eventually
                CIA cable, follow-up source on KSM, July 11, 2001. As noted in chapter 7, KSM has
                discussed in chapter 3, and specifically from a March 1995 memorandum of then Deputy
                through the OIPR screen. What had happened, as we discussed in chapter 3, was a
                regulations, "Regulations" chapter of "Operational Procedures and Policies," July
            23. FDNY regulations, "Communications" chapter of "Operational Procedures and
                review contacts between Iraq and al Qaeda in chapter 2. We have found no credible
            15. For Murad's idea, see chapter 5, note 33.
                National Intelligence Director we recommend later in this chapter.
```

At last I count it in chapter-1.txt in 911report folder for the same condition.

```
linyubing@linyubingdeMacBook-Pro lab4 % grep -w "chapter" */*/chapter-1.txt   
    Others in the agency were aware of it, as we explained earlier in this chapter.
```
