# WASP Research Arena WARA Software

The WARA for Software is a planned [WASP](http://wasp-sweden.org/) research arena for Wallenberg AI, Autonomous Systems and Software Program.  Its goals are to
- Foster collaboration between software technology and software engineering researchers and WASP industrial partners
- Provide a research focus for WASP software technology and software engineering researchers
- Provide resources for software technology and software engineering researchers, especially students
- Support Open Source software through
  - Analysing and improving selected Open Source software projects
  - Contributing Open Source software development tools
  - Understanding strengths and limitations of existing tools and processes in the Open Source development process

# WARA infrastructure

* [OVE](https://github.com/Ericsson/ove): Ericsson's OVE system, basis for benchmarking

## Software Artifacts

Software artifacts collected and curated for further software research

* [Softwawre corpus](https://github.com/wasp-sweden/wara-sw-tech-tools): WIP OVE source code corpus for evaluating offline (non-interactive) software tools
* [Maven Dependency Graph](https://zenodo.org/record/1489120): Snapshot of the whole Maven Central taken on September 6, 2018, stored in a graph database
* [Static usages of popular Maven APIs](https://zenodo.org/record/2567268): static usages of API elements of any version of the 99 most used maven artifact, by any of its client on Maven Central.
* [Dataset of diffs](https://github.com/KTH/CodRep-competition/) 50k one-line diffs from 18 open-source projects to study software evolution
* [Dataset of continuous integration builds](https://zenodo.org/record/2560966) 35+ Millions of Travis jobs
* [DUETS](https://github.com/castor-software/Duets) 395 open-source Maven-based libraries and 2,874 clients

## Github repositories by WASP Software students
* [VoTE](https://github.com/john-tornblom/VoTE): Formal Verification of Tree Ensembles
* [MetaDL](https://github.com/lu-cs-sde/metadl): A Datalog extension for program analysis using syntactic patterns
* [JBrainy](https://git.cs.lth.se/noricc/jbrainy): Benchmarking and performance analysis of Java data structures by fuzzing
* [Jatte](https://bitbucket.org/jastadd/jatte): A tunable tree editor for integrated DSLs
* [DepAnalyzer](https://github.com/castor-software/depanalyzer): A tool to collect the classes and methods used by a Java application
* [DepClean](https://github.com/castor-software/depclean): A tool to automatically detect and remove unused dependencies in Maven projects 
* [JDBL](https://github.com/castor-software/jdbl): A tool to automatically remove unnecessary bytecode from Java applications through dynamic analysis 

## WASP project course

2019
  * **Enabling Design And Execution of Large Scale Experiments on Maven Central**
    * Participants: César Soto Valero (KTH), He Ye (KTH), Joel Scheuner, (Chalmers) Long Zhang (KTH) and Nicolas Harrand (KTH)
    * Industrial supervisor: Torsten Ek, Combient
    * Academic supervisor: Benoit Baudry, KTH
    * Abstract: In order to develop the software transformations involved in automatic software engineering, large datasets of software artifact containing at the same time artifacts, their sources, as well as build instructions and test are extremely valuable. This work provides data and tooling enabling large scale experiment on 4.2M of Maven Central artifacts.
  * **Static Program Analysis for C++ in the WARA for Software**
    * Participants: Noric Couderc (LU), Alexandru Dura (LU), Claudio Mandrioli (LU)
    * Industrial supervisor: Baldvin Bern, Axis
	* Academic supervisor: Christoph Reichenbach, LU
	* Abstract: Program bugs remain omnipresent. Today, there are many approaches to finding program bugs, with code reviews, unit tests, and program analysis tools being the most commonly used. While code reviews and unit tests are by their nature adapted to the program that they analyse, program analysis tools are typically more general.  In this project, you will develop or extend a static program analysis tool to detect memory errors and/or API contract errors (your choice). Your project will focus on analysing the GStreamer frame- work (which is scheduled for inclusion in the WARA for Software) and may be adapted specifically to GStreamer’s needs.

