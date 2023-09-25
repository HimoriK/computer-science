<p align="center">
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
  </a>
  <a href="https://github.com/ossu/computer-science">
	<img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg">
  </a>
</p>

# Contents

- [Curriculum](#curriculum)
- [Core CS](#core-cs)
- [Advanced CS](#advanced-cs)

# Summary


Learn Computer Science with a free curated curriculum. There is [no easy way](https://i.stack.imgur.com/KICI7.png) to learn this stuff, there are [quick ways,](https://www.businessinsider.com/cfpb-states-sue-prehired-predatory-student-debt-tech-bootcamp-isa-2023-7?op=1) yes. Not [easy](https://www.irishtimes.com/news/education/concern-over-drop-out-rates-in-computer-science-courses-1.2491751) ways though. The quickest way, is to pick up a free book and teach yourself. That's 1 big book, or 3 specialized smaller ones. To prove my point, before you consider going on Coursera, search for a popular [programming language 
here](https://www.classcentral.com) and reviews for the courses you're interested in. Reviews imply Coursera > edX, but online curriculum is limited, as even the best universities in the world have educational issues. MIT content is also outdated. Videos are okay, but attention drifts, while practice lingers. Don't outsource your education or base it on old content. Get a proper book written in (preferably) your style and no fluff. Or pay for a good degree program.

<details>
  <summary>
    
**Sequence**. The curriculum is designed as follows:
- *Intro CS*: for students to try out CS and see if it's right for them
- *Core CS*: corresponds roughly to the first three years of a computer science curriculum, taking classes that all majors would be required to take
- *Advanced CS*: corresponds roughly to the final year of a computer science curriculum, taking electives according to the student's interests
- *Final Project*: a project for students to validate, consolidate, and display their knowledge, to be evaluated by their peers worldwide
</summary>
</details>

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

If you've never written a for-loop, or a string in programming, start here.

Courses | Duration | Effort 
:-- | :--: | :--: |
[Python for Everybody](https://www.py4e.com/lessons) | 10 weeks | 10 hours/week

### Introduction to Computer Science

This course will introduce you to the world of computer science. Students who have been introduced to programming, either from the courses above or through study elsewhere, should take this course for a flavor of the material to come. If you finish the course curious, Computer Science is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`etc`

Courses | Duration | Effort 
:-- | :--: | :--: |
[Python Programming Primer](https://github.com/HimoriK/computer-science/files/12163718/Python.Programming.Primer-4.pdf) or [The Coder's Apprentice](https://www.spronck.net/pythonbook/pythonbook.pdf) | 10 weeks | 10 hours/week

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`unit testing`
`object-oriented design`
`static & dynamic types`
`etc`

Books |
:-- |
Learn a bit of Python, focus on learning C as it's concepts can be applied to other languages and most OS are based on it, including Windows and Linux. When you look into the inter-workings of a program, you will see either C or assembly. Newer languages are basically fancy C with new implementations. However it's good to know a bunch so you aren't stuck to one language's features or limited codebase.
['C/C++' aren't the same](https://brycevandegrift.xyz/blog/stop-saying-c-and-c++/) 
[Computer Science I](https://github.com/HimoriK/computer-science/files/12163849/ComputerScienceOne.pdf)
[Algorithms](findavideo,onProgramLanguageDifferences) and [Course](https://codeahoy.com/learn/analysisofalgorithms/ch1/) *[Optional](https://en.wikibooks.org/wiki/Algorithms)
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

Courses | Duration | Effort | Notes 
:-- | :--: | :--: | :--: |
[Calculus I](https://www.mecmath.net/calculus/ElementaryCalculus.pdf) | 13 weeks | 6-10 hours/week | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) 
[Calculus III](https://www.mecmath.net/VectorCalculus.pdf) | 6 weeks | 5-10 hours/week 
[Discrete Math](https://discrete.openmathbooks.org/pdfs/dmoi3-tablet.pdf) | 10 weeks | 5 hours/week


### CS Tools
Practice over theory.

**Topics covered**:
`terminals and shell scripting`
`cli environments`
`version control`

Courses | Duration | Effort 
:-- | :--: | :--: | 
**Optional:** [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week 

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

Courses | Duration | Effort | Additional Text / Assignments  
:-- | :--: | :--: | :--: |
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | 
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) 

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

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.amazon.com/Applied-Incident-Response-Steve-Anson/dp/1119560268) or [this](https://cybersecuritybase.mooc.fi/) | 8 weeks | 10-12 hours/week 
[The Art of Memory Forensics](https://www.amazon.com/Art-Memory-Forensics-Detecting-Malware/dp/1118825098/) | 6 weeks | 7-10 hours/week 

### Core applications

**Topics covered**:
`refactoring`
`data modeling`
`neural networks`
`un/supervised learning`
`OpenGL`
`ray tracing`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--: 
[Databases: Introduction](add)| 2 weeks | 10 hours/week | core programming 
[Machine Learning](https://www.coursera.org/specializations/machine-learning-introduction)| 11 weeks | 9 hours/week | Basic coding 
[Computer Graphics](replacewithOPENGLorVulkun)| 6 weeks | 12 hours/week 

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
Students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`

Courses | Duration | Effort
:-- | :--: | :--:
[Parallel Programming](youcanlearnthisanywherefromabook)| 4 weeks | 6-8 hours/week 
[Compilers](youllLearnthisIntheField) | 8 weeks | 6-8 hours/week | none
[Software Debugging](learnhowtouseadebugger)| 6 weeks | 6 hours/week 

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`sequential logic`
`finite state machines`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Courses | Duration | Effort 
:-- | :--: | :--:
[Digital Circuits](architecture1) | 10 weeks | 6 hours/week
[Computer Architecture](https://www.amazon.com/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680) | 10 weeks | 6 hours/week 

### Advanced Information Security

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security
[Secure Software Development](PickavideoOrfindaBook) | 7 weeks | 1-2 hours/week


### Advanced math
Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [high school math](FAQ.md#how-can-i-review-the-math-prerequisites) 
[Linear Algebra](youtubeOrBook) | 14 weeks | 12 hours/week | corequisite: Essence of Linear Algebra 
[Introduction to Numerical Methods](ShouldbeEasytoFindaBook)| 14 weeks | 12 hours/week
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) |
[Probability](https://projects.iq.harvard.edu/stat110/home) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](youtubeOrBook)

## Final project

This curriculum is project-focused.

After you've gotten through all of Core CS and Advanced CS relevant to you, work on
a real project and showcase your skills to employers.
You can create any project, or find an existing one via websites like
[CodeTriage](https://www.codetriage.com/)
or
[First Timers Only](https://www.firsttimersonly.com/).

Here is a sample of available, project-oriented programs.

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | programming
[Modern Robotics (Specialization)](probablyabettercoursesomewhere) | 26 weeks | 2-5 hours/week | freshman-level physics, linear algebra, calculus, [linear ordinary differential equations](https://www.khanacademy.org/math/differential-equations)
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming
[Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | none
[Game Design and Development with Unity 2020 (Specialization)](theresprobablyawaytodothhisinamonth) | 6 months | 5 hours/week | programming, interactive design
