---
layout: cv
title: Zejun Chen (Xavier)'s CV
---
# Zejun Chen (Xavier)

<div id="webaddress">
Email: <a href="mailto:zc344@cam.ac.uk">zc344@cam.ac.uk</a>
</div>


## Interests

Compilers and optimizing compilers, hardware architecture and heterogeneous architecture computing. 

For part II dissertation I'm
considering to pursue topics related to using additional information provided by ISA extensions (currently considering capabilities 
provided by CHERI) to support automatic/implicit parallelization in heterogeneous devices (i.e. GPU or special purpose accelerators). 

## Education

`2021-2024`
__Computer Science Tripos, Gonville & Caius College, Cambridge__

- Current 2nd year student.

## Experiences & Achievements

### Internship
`June - Sept 2021`
___Intern_ at Honeywell Aerospace, Shanghai__

Interned at the mechanical design and engineering department.
Automated the department’s administrative processes with Python. Created 30-40 hours
of productivity savings per quarter.
Conducted thermal characterization experiments for various critical materials used in
aircraft in development.
Developed standardised reparation procedures for aviation brake assemblies for client
aircraft reparation company, currently servicing over 100 cargo jets per year.

### Projects

`June - Sept 2022`
___UROP Project: Optimizing Compilers-Automatic Parallelization_, University of Cambridge__
Project Mentor: Prof. Timothy M. Jones
Project scope: I worked under the <a href="https://github.com/CompArchCam/Janus/">JANUS</a> project,
a "a same-ISA dynamic binary modification tool controlled through static analysis". My job mostly
contains refactoring the static analysis component of the codebase using modern C++. I utilized
the <a href="https://en.cppreference.com/w/cpp/language/constraints">"constraints"</a> features
introduced in C++20 to modularize existing, monolithic static analysis pipeline, while providing an
elegant approach to express the dependency relations between analysis stages, and allow for easy future
extensions. I also rewrote some of the pipelines to utilize the <a href="https://en.cppreference.com/w/cpp/memory">"smart pointers"</a>
introduced in C++11 to provide better memory-management to existing work, and eliminated many instances of
memory leaks through this approach. Furthermore, I implemented dataflow and liveness analysis using the refactored
architecture, to showcase how additional static analysis can be incorporated in the future.
GitHub link to the branch I worked in: <a href="https://github.com/CompArchCam/Janus/tree/refactor_redo">Janus refactor</a>


`Jan - June 2021`
___Source Academy Project_, National University of Singapore__
Project scope: ECMAScript subset implementation on various platforms for introductory
functional programming course.

Learnt compilers and virtual machine principles, help implemented the virtual machine for
the said language subset in C and C++ on ESP32 embedded system based on
WebAssembly.

Developed drivers for various sensors and actuators in C to interface between the Source
Language API and the ESP32 controller. Enables future development of robotics platform
based on the system.


<!-- ### Footer

Last updated: May 2013 -->


