Hi!  I'm Antonio.  I'm a Clinical Laboratory Application Snalyst at the University of Pennsylvania Health System.
I am also a Teaching Assistant for the University of Pennsylvania's Masters in Computer and Information Technology online program.

## UPHS

As a Clinical Laboratory Application Analyst, I am responsible for building, testing, and maintaining multiple middleware systems.
These systems interface the laboratory instruments to the Laboratory Information System (LIS).
In the last five or so years, we've expanded from a team of me, managing one system, to a team of four, managing seven systems (and still growing).  

## UPenn

As a Teaching Assistant, I am responsible for guiding students through the learning process.
I focus on the two core courses relating to C coding: CIT593 (Intro to Computer Systems) and CIT595 (Computer Systems Programming).
Most of the time is dedicated to meeting with students in office hours or asynchronously on course discussions boards, to explain concepts or assist debugging programs.

CIT593 is a bits-to-C course designed to go from the basics of binary, to logic gates, sequential/combinatorial circuits, assembly (in LC4, an education assembly language), and finally to C.
On the side, I additionally help write and manage course autograders and the backend LC4 simulator (PennSim).

CIT595 is a continuation of CIT593 focusing more on the operating system, system calls, concurrency, file management, and networking.
I also assist with writing and maintaining the course autograders.

## Programming Accomplishments

### PennSim 
Apologies, but this is not publically available for obvious reasons.

####  Refactor source code

For whatever reason, the source code for PennSim was completely unreadable (no annotations, weird variables, etc).
I learned the entire source code and refactored for readability.
I also added JavaDocs so the next maintainer has a place to start.

#### Upgrades and improvements

I found a lot of commented out features and managed to restore them in the simulator.
Some of them include an internal source viewer, a Data Path extension (shows control signals as each instruction executes), local copies of important ISA documents, and auto-executable demo code.
I also rewrote the manual and included it in the simulator.

#### Automated checks and validation

I managed to set up the repository for continuous integration via CircleCI, so any changes automatically re-validate before merging pull requests.
I also added many unit tests that run through the Maven life cycle.
This has improved reliability and confidence that changes won't break course assignments unexpectedly.

### Course autograders
Apologies, but these are not publically available for obvious reasons.

#### 593 Gradescope
I wrote a modularized autograder for the three C programming assignments.  The autograder also runs for other assignments to check for submitted files and also to grade an excel spreadsheet.

#### 595 (various)
I will put some things here one day.

### Public Programs

#### [EDF Anonymizer](https://github.com/alesparza/edf-anonymizer)

This is a small little program to help anonymize EDF files.

#### [Instrument Emulator](https://github.com/alesparza/Instrument-Emulator)

This is a small project to try out GUI elements and also network programming (using the ASMT protocol for laboratory instruments)

