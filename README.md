Algorithms for NP-hard Problems (KAIST CS492), Spring 2024
====================


<span style="color:red">NEWS</span>
---------------------
- 2 June: Homework #4 is now on gradescope. The deadline is 16th June, 23h 59. 
- 27 May: Lecture on 28 May is cancelled (details on KLMS and via email). 
- *****IMPORTANT.***** ********The final exame is scheduled on 8th June (Saturday), at 9am,******* in the same lecture room. The exam will finish at 20 minutes later once there are at most three remaining students who still take the exam. Lunch will be ordered (pizza?) and be shared during the break time at 12h. 
- 21 May: Homework #3 deadline is extended to 24 May (Friday), 23h59.
- 9 May: Erratum: In Homework #3, the problem "trangle packing" is to pack disjoint triangles (not cycles).
- 8 May: Lecture Note for 7-May is updated; the previous one had some error in the last section.
- 4 May/9 May updated: Homework #3 is uploaded in KLMS, to be submitted before 21 May, 23h59. You can form a team of two students if you want. Handwritten solutions will be accepted for this homework (but please do your best to make a clear handwriting). 
- 17 April: Homework #2 deadline is extended to 22 April, 23h59.
- 11 April: Regarding the mid-term exam. It will take place at 9h on 16 April (Tuesday) for 3 hours. You can bring snacks and drink (something that does not create much noise). No calculator needed. Closed book.
- 8 April: Lecture note for tree decomposition Part II is available now.
- 7 April: (Advertisement) A website and the registration site for an upcoming summer school is open now. You're welcome to attend! Check out more details here: https://combialgo.github.io/
- 4 April: Homework #2 is now added on KLMS as Week 6 activity. 
- 3 April: Lecture note for tree decomposition Part I is available now.
- 26 March: gradescope is now connected on KLMS for submitting HW #1 as an activity/resource in Week 5. The deadline is extended by 24hrs in case you have an issue submitting the solution. ([ref](https://www.gradescope.com/get_started#create-homework))
- 13 March: Lecture Note of Kernelization Part II is available.
- 12 March: Homework 1 is available at KLMS. The deadline is 26th March midnight.
- 7 March: Handwritten slides for lectures Week 1 and 2 are on KLMS. Lecture Note of Kernelization Part I is available now.

LOGISTICS
---------------------
- Lecturer: Eunjung KIM, eunjung.kim@kaist.ac.kr
- Lecture Room: 2443 in Building E3
- Lecturer office hour: Wednesday 10:00-11:30 at 3406, E3-1
  

  
- Schedule: 
  - On-site lectures, Tuesday and Thursday 9:00-10:30.
  - 18-22 March: Guest lecturer, [Sebastian Wiederrecht](https://www.wiederrecht.com/)
  - 15-19 April: Midterm exam period. No lecture. Exam is at 9h00-11h45, 16 April.
  - 10-14 June: Final exam period. No lecture. Exam is at 9h00-11h45, 11 June.
     
- Grading: 
  - Homeworks, Participation, Quiz 20%, Project 10%, Midterm exam 35%, Final exam 35%.
  - Project: Students choose a subject related with the course (e.g. a section from the textbooks used in the class, classic or recent papers), and produce a short video explaining the material. You can form a team consisting of up to three members.
  - Participants of the [PACE Challenge 2024](https://pacechallenge.org/2024/) with qualified solutions will get 10% bonus credits on top of their final credits. (Valid: Exact Track and Parameter Tracks)
  
 
- Others:
  - The official language in the class is English. 
  - Homework assignments will be announced on the webpage. The solutions to homeworks should be written either in latex (highly recommended) or in a text editor, e.g. MS Word. The assignment needs to be submitted before the indicated deadline on [KLMS](https://klms.kaist.ac.kr/course/view.php?id=156156). 
Hand-written solutions or submissions after the deadline are not accepted.
  - A strict policy against dishonest behaviors will be applied; expect an "F" grade. 


Course Description
-------------------
Most computational problems are NP-hard, and we cannot expect to solve them (i) optimally (ii) in polynomial-time (iii) on all instances. In this course, we study algorithm design paradigms which relax some of the criteria (i)-(iii) for a desirable algorithm. Specifically, we present techniques for designing and analyzing algorithms in the frameworks of parameterized complexity, approximation and exact exponential algorithms. We examine how such techniques are implemented as algorithms for concrete problems using the structure of a problem instance or a solution. The notions of hardness, which says that there is a limit on how efficiently some problems can be solved under some computational complexity assumption, are introduced as well.

- Recommended Prerequisite: 
Discrete Mathematics (CS204), Data Structure (CS206), Introduction to Algorithms (CS300).

- Course Materials.

  Main Textbooks
  - Parameterized Algorithms, Marek Cygan, Fedor V. Fomin, Lukasz Kowalik, Daniel Lokshtanov, Dániel Marx, Marcin Pilipczuk, Michał Pilipczuk and Saket Saurabh, Springer 2015, https://www.mimuw.edu.pl/~malcin/book/parameterized-algorithms.pdf
  - Exact Exponential Algorithms, Fedor Fomin and Dieter Kratsch, Springer 2010, https://link.springer.com/book/10.1007/978-3-642-16533-7
  - Approximation Algorithms, Vijay Vazirani, Springer 2001 https://link.springer.com/book/10.1007/978-3-662-04565-7

  References.
  - Graph Theory, Reinhard Diestel, Graph Theory (Graduate Texts in Mathematics, 173) 5th edition, Springer 2016/2017. [Free online](https://diestel-graph-theory.com/)
  - The design of Approximation Algorithms, David P. Williamson, David B. Shmoys, Cambridge University Press 2011. [Free online](https://www.designofapproxalgs.com/).

 
Course Plan (liable to be adjusted)
------------
- 27 Feb: Introduction. Branching-based algorithm, part I. 
  [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek01%5Dbranching_algorithm.pdf). Chapter 3.1, 3.3, 3.4 from Cygan et al.
- 29 Feb: Branching-based algorithm, part II
- 5 March: Basics of Kernelization.
  Chapter 2.2-2.5, 9.1 from Cygan et al.
  [Lecture Note, Part I](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek02%5Dkernelization_part_I.pdf).
- 7 March: More on Kernelization: Vertex Cover, A bit of Feedback Vertex Set.
- 12 March: Quadratic kernel for Feedback Vertex Set. [Lecture Note, Part II](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek02%5Dkernelization_part_II.pdf) Homework 1 out.
- 14 March: Interative compression. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek03%5Diterative_compression.pdf), Chapter 4.1, 4.3 from Cygan et al. 
- 19, 21 March: Guest lecture by [Sebastian Wiederrecht](https://www.wiederrecht.com/). On maximum matching.
- 26 March: Randomized technique for FPT algorithm. Chapter 4.4, 5.1-5.3 from Cygan et al. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek05%5Drandomized.pdf).
- 28 March: Tree-decomposition I. Chapter 7.1-7.2 from Cygan et al. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek05%5Dtree-decomposition-I.pdf).
- 2 April: Tree-decomposition II. Chapter 7.3 from Cygan et al.
- 4 April: Tree-decomposition III. Chapter 7.4, 7.6 from Cygan et al. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek06%5Dtree-decomposition-II.pdf). Homework 2 out. 
- 9 April: Dynamic programming over subsets and IE-based algorithm. Chapter 10.1 from Cygan et al. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek07%5DDP%2BIE.pdf).
- 11 April: More IE-based algorithms and Matrix Tree Theorem. Chapter 4.2 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7), [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek07%5Dalgebraic_approach.pdf).
- 16 April: Mid-term exam.
- 23 April: Mid-term exam revision. Topic Proposal for the project.
- 25 April: Algorithms for CNF-SAT. Chapter 8.1 from [Fomin and Kratsch' textbook](https://link.springer.com/book/10.1007/978-3-642-16533-7)
- 30 April: Hardness in parameterized complexity. Chapter 13 from Cygan et al. For details on the class NP and NP-completeness, check Chapter 2 of [Arora and Barak](https://theory.cs.princeton.edu/complexity/book.pdf). One can find a more comprehensive treatement on W-hierarchy in [Flum and Grohe](https://link.springer.com/book/10.1007/3-540-29953-X) and [Downey and Fellows](https://link.springer.com/book/10.1007/978-1-4612-0515-9).
- 2 May: (S)ETH-based lower bound. Chapter 14 from Cygan et al. Homework 3 out.
- 7 May: Introduction to approximation algorithms. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek11%5Dapprox_intro.pdf). Chapter 3 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7). Chapter 1 and 2.1 from [Chekuri's Lecture Note](https://courses.engr.illinois.edu/cs583/fa2021/approx-algorithms-lecture-notes.pdf).
- 9 May: Layering technique. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek11%5Dapprox_layering.pdf). Chapter 2.2 and 6 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7). 
- 14 May: Approximation for cut problems. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek12%5Dcut_flow_lp_I.pdf). Chapter 4 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7)
- 16 May: Approximation for cut problems. LP-based rounding. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek12%5Dcut_flow_lp_II.pdf). Chapter 12 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7).
- 21 May: More on cut problems. LP-based rounding. [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek13%5Dhalf-integrality_LP_rounding.pdf).
- 23 May: LP-based rounding. Chapter 1.7 and 5.1-5.5 from [Williamson and Shmoys](https://www.designofapproxalgs.com/).
- 28 May: No lecture.
- 30 May: Primal-dual method. Homework 4 out. Chapter 7.3 from [Williamson and Shmoys](https://www.designofapproxalgs.com/) and chapter 13.1 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7). [Lecture Note](https://github.com/ssimplexity/CS492_spring2024/blob/main/%5BWeek14%5Dprimal_dual_I.pdf). 
- 4 June: Primal-dual method. Chapter 7.4 from [Williamson and Shmoys](https://www.designofapproxalgs.com/), chapter 18 from [Vazirani](https://link.springer.com/book/10.1007/978-3-662-04565-7).
- 6 June: no lecture (public holiday).
- 8 June: Final exam. 
- 16 June: Submission of the video presentation.


