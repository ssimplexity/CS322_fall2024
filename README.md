Formal Languages and Automata (KAIST CS322), Fall 2024
====================


<span style="color:red">NEWS</span>
---------------------



LOGISTICS
---------------------
- Lecturer: Eunjung KIM (eunjung.kim@kaist.ac.kr)

- Teaching Assistans 
  - Gunwoo Kim (gunwoo.kim@kaist.ac.kr) 
  - Jihoon Hyun (qawbecrdtey@kaist.ac.kr)
  - Seokbeom Kim (seokbeom@kaist.ac.kr)
  - Doheyon Lee (mathloveguy@kaist.ac.kr)
    
- Lecture Room: 1220 at Building E3
  
- Office hour with the lecturer: after each lecture or upon arrangement.
- Office hour with the TAs: Wednesday 17-18h, Office 3409 at E3-1
  

  
- Schedule: 
  - Lecture Schedule. Monday and Wednesday, 10:30-11:45.
  - All lectures will take place on-site except for the week of 9-13 September and on 7th October.
  - The midterm exam will take place in the week of 28 Oct-1 November, one week after the offical midterm exam period.
  - The final exam will take place in the usual final exam period. 
     
- Grading: Homeworks, Participation, Quiz 30%, Midterm exam 35%, Final exam 35%
  
 
- Others:
  - The official language in the class is English. 
  - Homework assignments will be announced on the webpage. Expect an assignment at least every two weeks. Ideally, the solutions to homeworks should be written either in latex / in a text editor, e.g. MS Word / or VERY CLEAN AND IMMEDIATELY READABLE handwriting. If the people who grade your homework will not spend time trying to decifer your handwriting! No matter how great your solution is, if it's not readable EASILY, it gets exactly that much score. The assignment needs to be submitted before the indicated deadline on [KLMS](https://klms.kaist.ac.kr/course/view.php?id=162187). 
Hand-written solutions or submissions after the deadline are not accepted.
  - A strict policy against dishonest behaviors will be applied; expect an "F" grade and be reported to the SoC board when you fail to follow the [honor code](https://cs.kaist.ac.kr/content?menu=309).


Course Description
-------------------
We study ‘computer science’ and a computer is a computing machine. In this course, we study various notions and ideas which were developed since 1930’s in response to fundamental questions such as the following. 
  - What do we mean by computing? 
  - What is the object that a computing machine computes? Why we call a programming language a ‘language’?
- Both computer scientists and linguists talk about ‘languages’. Are there something in common? How to formalize the link between them.
- Computers ranging from high-performance server, desktop, laptops to mobile phones, from a wide range of manufacturers are all ‘computers’. On which ground, do we treate them as if they are (essentially) equally powerful machines?
- Is there a problem which cannot be ‘computed’? How to tell if a problem is computable or not.
- Is there a problem we’d better give up finding an ‘efficient’ algorithm? How to tell if a problem is efficiently computable or not.
  
- Is the computer implemented as your iMac the only form of a computer? 

Recommended Prerequisite: We assume that you have attended Discrete Mathematics (CS204) or have a sufficient background knowledge covered in similar courses. Introduction to Algorithms (CS300). 
To be successful in this course, you need certain, if not high, level of mathematical maturity. For example, competence in writing a formal proof and digesting abstract concepts in mathematical formalism are needed. 
We also assume that you have a moderate experience in programming, even though we do not do coding during the class.


Course Materials
-------------------
- Main Textbooks
  - John E. Hopcroft, Rajeev Motwani, Jeffrey D. Ullman, Introduction to Automata Theory, Languages and Computation, 3rd Edition, 2006, Pearson/Addision-Wesley. 
  - Michael Sipser, Introduction to the Theory of Computation, 2nd Edition (International Edition), 2006, Course Technology. 
- Other useful materials
  - Peter Linz, An Introduction to Formal Languages and Automata, 6th Edition, 2017, Jones & Bartlett Learning.
  - Scott Aaronson’s lecture notes on Automata, computability and complexity. [Link](https://ocw.mit.edu/courses/6-045j-automata-computability-and-complexity-spring-2011/pages/lecture-notes/).

 
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


