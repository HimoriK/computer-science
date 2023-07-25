<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
  </a>
  <a href="https://github.com/ossu/computer-science">
	<img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg">
  </a>
</p>

# Contents

- [Summary](#summary)
- [Community](#community)
- [Curriculum](#curriculum)
- [Code of conduct](#code-of-conduct)
- [Team](#team)

# Summary

Learn Computer Science with a clear curriculum of curated materials.
I want to make one thing clear: There is no easy way to learn about this stuff, there are quick ways, yes. Not easy ways though.
The quickest way, is to not waste your time with pointless mediocre courses when you could instead pick up a free book and teach yourself.
That's 1 big book, or 3 specialized smaller books. To prove my point, before you consider going on Coursera, search for a popular [programming language 
here](https://www.classcentral.com) and reviews for the courses you're interested in. Reviews imply Coursera > edX, but the curriculum of online schooling is limited, and even the best universities in the world have educational issues, your best bet is to pick your favorite books and learn by practice. MIT content is also outdated. Videos are okay, but attention drifts, while practice lingers. Don't outsource your education or base on old content. Get a proper book written in your language with (preferably) your style and no fluff. Otherwise pay for a good degree program.

**Organization**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide

# Curriculum

- [Prerequisites](#prerequisites)
- [Intro CS](#intro-cs)
  - [Introduction to Programming](#introduction-to-programming)
  - [Introduction to Computer Science](#introduction-to-computer-science)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [Core math](#core-math)
  - [Core systems](#core-systems) **important**
- [Advanced CS](#advanced-cs)
- [Final project](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://github.com/ossu/computer-science/blob/master/FAQ.md#how-can-i-review-the-math-prerequisites), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken a basic physics course (e.g. AP Physics in high school).

## Intro CS

### Introduction to Programming

If you've never written a for-loop, or don't know what a string is in programming, start here.

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Python for Everybody](https://www.py4e.com/lessons) | 10 weeks | 10 hours/week

### Introduction to Computer Science

This course will introduce you to the world of computer science. Students who have been introduced to programming, either from the courses above or through study elsewhere, should take this course for a flavor of the material to come. If you finish the course curious, Computer Science is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`etc`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Python Programming Primer](https://github.com/HimoriK/computer-science/files/12163718/Python.Programming.Primer-4.pdf) or [The Coder's Apprentice](https://www.spronck.net/pythonbook/pythonbook.pdf)

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`unit testing`
`object-oriented design`
`static & dynamic types`
`etc`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
Learn a bit of Python, but focus on learning C as it's concepts can be applied to other languages and most OS are based on it, including Windows and Linux. When you look into the inter-workings of a program, you will see either C or assembly. Newer languages are basically fancy C with new implementations. However it's good to know a bunch so you aren't stuck to one language's features or limited codebase.
['C/C++' aren't the same](https://brycevandegrift.xyz/blog/stop-saying-c-and-c++/) 
[Computer Science I](https://github.com/HimoriK/computer-science/files/12163849/ComputerScienceOne.pdf)
[Algorithms](findavideo,onProgramLanguageDifferences) and [Course](https://codeahoy.com/learn/analysisofalgorithms/ch1/) [optional](https://en.wikibooks.org/wiki/Algorithms)
[Data Structures](https://opendatastructures.org/ods-python.pdf) and [Course](https://codeahoy.com/learn/cprogramming/toc/)
[Intro to Compilers and Language Design](https://www3.nd.edu/~dthain/compilerbook/compilerbook.pdf) or [LittleOSBook](http://ordoflammae.github.io/littleosbook)


### Core math
Discrete math (Math for CS) is a prerequisite and closely related to the study of algorithms and data structures. Calculus both prepares students for discrete math and helps students develop mathematical maturity.

**Topics covered**:
`discrete mathematics`
`mathematical proofs`
`basic statistics`
`O-notation`
`discrete probability`
`more math`

Courses | Duration | Effort | Notes | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Calculus I](https://www.mecmath.net/calculus/ElementaryCalculus.pdf) | 13 weeks | 6-10 hours/week | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) 
[Calculus III](https://www.mecmath.net/VectorCalculus.pdf) | 6 weeks | 5-10 hours/week 
[Mathematics for Computer Science](addinaCSorMathcoursehere) | 13 weeks | 5 hours/week


### CS Tools
Practice over theory.

**Topics covered**:
`terminals and shell scripting`
`cli environments`
`version control`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week 

### Core systems

**Topics covered**:
`procedural programming`
`boolean algebra`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`**this it**`

Courses | Duration | Effort | Additional Text / Assignments| Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | Nand to Tetris Part II 
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) | algebra, probability, basic CS | [chat](https://discord.gg/MJ9YXyV)

### Core theory

**Topics covered**:
`sorting and searching`
`randomized algorithms`
`shortest paths`
`data structures`
`dynamic programming`
`NP-completeness`

### Core security
**Topics covered**
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Cybersecurity Fundamentals](replacewithsomesecuritybook) | 8 weeks | 10-12 hours/week
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week 
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week 

Choose **one** of the following:

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++Programming](security+ or net+) 

### Core applications

**Topics covered**:
`refactoring`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`ray tracing`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Databases: Modeling and Theory](replace)| 2 weeks | 10 hours/week | core programming 
[Databases: Relational Databases and SQL](replace)| 2 weeks | 10 hours/week | core programming
[Databases: Semistructured Data](replace)| 2 weeks | 10 hours/week | core programming 
[Machine Learning](https://www.coursera.org/specializations/machine-learning-introduction)| 11 weeks | 9 hours/week | Basic coding 
[Computer Graphics](replaceimsuretherearegoodbooksforthisontheinternetlikeOPENGLorVulkun)| 6 weeks | 12 hours/week 
[Software Engineering: Introduction](youwillLiterallylearnthisonthejob) | 6 weeks | 8-10 hours/week | Core Programming, and a [sizable project](FAQ.md#why-require-experience-with-a-sizable-project-before-the-Software-Engineering-courses)
### Core ethics

**Topics covered**:
`Intellectual Property`
`Professional Ethics`
`Privacy and Civil Liberties`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Ethics, Technology and Engineering](https://www.coursera.org/learn/ethics-technology-engineering)| 9 weeks | 2 hours/week 
[Introduction to Intellectual Property](literallyjustlearnaboutFOSSPoliciesandPracticeit)| 4 weeks | 2 hours/week 
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy)| 3 weeks | 3 hours/week 

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Parallel Programming](youcanlearnthisanywherefromabook)| 4 weeks | 6-8 hours/week 
[Compilers](youllLearnthisIntheField) | 9 weeks | 6-8 hours/week | none
[Software Debugging](https://www.udacity.com/course/software-debugging--cs259)| 8 weeks | 6 hours/week 

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Digital Circuits](architecture1) | 10 weeks | 6 hours/week | [Nand2Tetris II](https://www.coursera.org/learn/nand2tetris2) | Alternate links contain all 3 courses.
[Computer Architecture](https://www.amazon.com/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680) | 10 weeks | 6 hours/week 

### Advanced theory

**Topics covered**:
`computability`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`game trees`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Game Theory](replacewithabookorarticle) | 8 weeks | 3 hours/week | mathematical thinking, probability, calculus

### Advanced Information Security

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security
[Secure Software Development](PickavideoOrfindaBook) | 7 weeks | 1-2 hours/week


### Advanced math
Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) 
[Linear Algebra](youtubeOrBook) | 14 weeks | 12 hours/week | corequisite: Essence of Linear Algebra 
[Introduction to Numerical Methods](ShouldbeEasytoFindaBook)| 14 weeks | 12 hours/week
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) |
[Probability](https://projects.iq.harvard.edu/stat110/home) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](youtubeOrBook)

## Final project

This curriculum is project-focused.

After you've gotten through all of Core CS and the parts of Advanced CS relevant to you, put it to use.
Not only does real project work look great on a resume, but this will also display your knowledge.
You can create something entirely new, or find an existing project via websites like
[CodeTriage](https://www.codetriage.com/)
or
[First Timers Only](https://www.firsttimersonly.com/).

Students who would like more guidance in creating a project may choose to use a series of project oriented courses. Here is a sample of available, guided programs.

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | programming
[Modern Robotics (Specialization)](probablyabettercoursesomewhere) | 26 weeks | 2-5 hours/week | freshman-level physics, linear algebra, calculus, [linear ordinary differential equations](https://www.khanacademy.org/math/differential-equations)
[Data Mining (Specialization)](https://www.coursera.org/specializations/data-mining) | 30 weeks | 2-5 hours/week | machine learning
[Big Data (Specialization)](https://www.coursera.org/specializations/big-data) | 30 weeks | 3-5 hours/week | none
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming
[Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | none
[Game Design and Development with Unity 2020 (Specialization)](theresprobablyawaytodothhisinamonth) | 6 months | 5 hours/week | programming, interactive design
