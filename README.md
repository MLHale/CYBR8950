# CYBR4580
This repository contains a digitized version of the course content for the CYBR/IA 4580 Certification and Accreditation capstone course at the University of Nebraska at Omaha.

## Overview
In this course, students will extend and apply their knowledge, accumulated from their undergraduate studies, towards defining, implementing, and assessing secured information systems. Students will demonstrate their ability to specify, apply, and assess different types of countermeasures at different points in a system or enterprise.

### Table of contents
[Online discussion area](#online-discussion-area)  
[Location](#location)	 
[Supplies](#supplies)	 
[Projects](#projects)
[Labs](#labs)
[Class topics](#class-topics)  
[Syllabus](#syllabus)  
[License](#license)  

## Online Discussion Area
I have setup an online discussion board on slack.com for usage in this class. I can create some private channels for you to work in with your project teams (once created), but I want to be able to participate in your conversations - so please use the space on slack. 

Go to [https://drhale4580.slack.com](https://drhale4580.slack.com) and use your unomaha email address to register an account. This will give you access to the course discussion and project collaboration spaces. Use the the general channel or create a new one for your team. 

## Location
All classroom activities will take place in PKI room 157 unless otherwise noted ahead of time.

## Supplies

### Hardware/software
* [Virtualbox](http://www.virtualbox.org) or [VMWare Workstation (windows) or Fusion (mac)](/vmware/vmware.pdf)
* [UNO Cloud Deployment Environments](http://view.unomaha.edu)
* Your laptop (capable of running programming environments or needed dev/analysis tools)

## Projects
The structure of the course accomodates two types of projects on two tracks.

1. Track 1: System Design, Development, and Security
In this track students will design, build, and secure a new full-fledged system or create a new, non-trivial, component for an existing system or product. Special attention will be paid towards open source environments. Relevant artifacts generated will include design documentation (use cases, architectures, interaction diagrams, etc), system/component code, unit/acceptance tests, and testing results.

2. Track 2: System Analysis and Evaluation
In this track students will select an existing product or system and rigorusly evaluate it using a combination of system, network, and software testing methods. Relevant artifacts generated will include reversed design docs (i.e. an understanding of how the product works), vulernability surface analysis documentation, test cases, and analysis results. 

Both tracks will also emphasize a certification and accreditation portion that tasks students with implementing or assessing security controls from standards documents (such as the NIST 800-53).

* [Capstone Milestone 1 rubric](/projects/milestone1.md) - Announced 2/16/17
* [Capstone Milestone 2 rubric](/projects/milestone2.md) - Announced 3/8/17
* [Capstone Final Milestone rubric]() - TBA

#### Evaluation form
For team projects, please use the evaluation form below to assess your teammates.
[https://goo.gl/forms/QM1OAQ80tzGVv19I2](https://goo.gl/forms/QM1OAQ80tzGVv19I2)

### Project Selection
Fill out the following form [https://goo.gl/forms/12rmlMTkVjG9nIqn2](https://goo.gl/forms/12rmlMTkVjG9nIqn2) to rank your project selection preferences. The top projects will be selected for the class and you will be given your preferred choice if possible. Then groups will refine the ideas based on their collective vision.

![capstone-img](/modules/img/capstone-projects.png)

### 2017 Project teams
#### Team Projects
* PLC Hacking
 * Gary Roth 
 * Richard Tanner
 * Daniel Ritter
* Forensic Tool Deficiency Analysis
 * Casey Branan 
 * Preston Wells
 * Brandon Franklin
* Analyzing and Penetration Testing an Amazon Echo Dot
 * James Autry
 * Matthew Sutton
 * Tim Gekas
* Open Source Hypervisor Analysis and Evaluation
 * Jesse Hembree
 * Afnan Albokhari
 
#### Solo Projects 
* Data Loss Prevention System
 * Leonora Gerlock
* [DNS Intrusion Detection System](https://github.com/mfaltys/doic)
 * Matthew Faltys
* (Airlock) - a P2P Encrypted Chat and Collaboration tool
 * Darian Lepert
* Windows Native Plugin for SFTP interaction
 * Chandler Huston
* Android Process inspector
 * Paul Stratman
* Secure Restaurant Ordering App
 * Yaqoob Al Farsi
 * Al Salt Al Kharusi


## Labs
1. Introduction to the course
 * [Virtualization primer](/modules/virtualization-primer.md)
 * [Github primer](/modules/github-primer.md)
1. Project discussion and planning
 * Project idea template: [docx](/modules/project-proposal-template.docx?raw=true)
1. Team interaction and project management (See in-class materials in [Lecture 4 pdf](lectures/lecture4.pdf))
 * Agile methods for development and assessment
 * Using collaboration tools
 * Keeping track of efforts


## Class Topics
1. Getting up to speed
 * [Virtualization primer](/modules/virtualization-primer.md)
 * [Github primer](/modules/github-primer.md)
 * Intro to the class and survey of security issues in different domains/sectors ([Lecture 1 pdf](lectures/lecture1.pdf))
    * Web app threat landscape
    * Mobile app threat landscape
    * SCADA/ICS threats
1. Review of software engineering ([Lecture 2](/lectures/lecture2.pdf), [Lecture 3 PDF](/lectures/lecture3.pdf))
 * Software Architectures
 * Software design principles
 * Security in the Software development lifecycle
1. Test-driven Development and assessment ([Lecture 4 pdf](lectures/lecture4.pdf))
 * Unit testing
 * Acceptance critera
 * think-test-build-test-repeat
 * Blackbox testing
1. Review of certification and assessment
 * Security controls, coutermeasures, etc
 * Standards Documents: NIST SP800-53, FIPS200, 800-33, etc
 * Assessment tools
1. Time to be creative
 * Come up with your own project idea or implement/assess something for a friend/family member or community organization
 * See [Projects](#projects) area

## Syllabus
### Date/Time: Thursday 5:30pm – 8:10pm
### Instructor:  Dr. Hale
### Office:  PKI 174-D, (402) 554-3978
### Office Hours:  By appointment or walk-ins anytime the door is open
### E-mail:  mlhale@unomaha.edu

### Grading Breakdown (due dates are tentative)
 * (10%) Participation score (meetings, short tutorial participation, etc)
 * (20%) Labs
 * (20%) Semester Project Milestone 1 - ([rubric](/projects/milestone1.md))
 * (20%) Semester Project Milestone 2 - ([rubric](/projects/milestone2.md))
 * (30%) Semester Project Milestone Final - (rubric TBA)

Each project milestone will have a specific grading rubric that includes the core requirements for the project, any required intermediate milestone goals (such as short progress meetings with the instructor), the project due date, and the list of items that must be submitted. Each project will include a presentation component to be presented in class on the project due date. Projects build upon each other. The final Project is considered to be comprehensive. This means that <i>there is no final exam</i>. Final Project presentations will be presented on the day of the Final.

### Attendance
* Class Attendance: You do not have to attend class except on presentation days (see below). Given the course is one day a week, attendance is highly recommended. Missing a single class is equivalent to missing 2-3 classes of a normal course. If you miss class, you are responsible for getting the material – including any assigned project work.
* Presentation Attendance (Mandatory): If you miss class on a presentation day you will receive a 0 on the presentation portion of the project grade unless you have a university-approved excuse or an approved extension (see below). 

### Group Work
Students will work in groups. Group projects will include an individual participation grade worth 50% of the total group points, e.g. a group may make a 100% on a particular project, but an individual with low participation in the group may make a 50%. Participation will be anonymously rated by other group team members and the instructor. 

### Team formation
The instructor reserves the right to make a change to any team or any project during the course of the semester for any reason that may or may not be disclosed. Project rescoping will be performed in this event. 

### Service Learning / Real World Customers
As part of UNO’s strategic initiatives, individuals or groups may be partnered with community organizations in Omaha for service learning through the center for community engagement. If community partners can be identified, student projects (group or individual) in the class may work towards meeting community needs. In the event of community projects, appropriate scoping will be considered to ensure that community needs can be met within the time constraints of the coursework. 

### Project Extensions and Late work
Sometimes unforeseen events occur or development takes longer than expected. In such cases, project extensions will be allowed. To receive a project extension, individuals or groups must request an extension at least 24hours in advance of the project due date. Extension time frames are at the discretion of the instructor, but generally will not be longer than 1 week. Failure to request an extension 24 hours prior to the due date means that the work is due at the specified time. Late work without a requested extension will receive a 5% point reduction per day up to a total of 40%. Late work submitted 2 weeks after an original (or extended) due date will not be accepted.

### Special accommodations for students with disabilities
Students with disabilities requiring special accommodations must contact disability services. Disability services may be reached by phone at (402) 554-2872 or by email at unodisability@unomaha.edu.
### Special accommodations for active duty or reserve military
Students serving in the military requiring special accommodations (e.g. unit deployment) must contact the office of Military and Veteran Services by phone at (402) 554-2349 or by email at unovets@unomaha.edu.

### Plagiarism
The university policies on cheating and plagiarism apply in this course. Except on designated group work, the expectation is that every student will do their own work. Students under suspicion of plagiarism for individual assignment submitted materials will be given an opportunity to defend themselves. If after defense the instructor still believes the work to be plagiarized the department chair will be notified and the grade evaluation for the assignment will be lowered to a value between 50% and 0% at the discretion of the instructor. If a second occurrence of plagiarism occurs, the student will receive an F for the course and the registrar’s office will be notified that the student is not permitted to withdraw from the course. In addition the department chair and dean will be notified.

### Work Retainment
The CS and IS programs in the College of IS&T are accredited through ABET (the Accreditation Board for Engineering and Technology. This organization occasionally requires that we keep samples of student work. 

The instructor may retain a copy of your exams (with names and any other identifying information removed) for accreditation or pedagogy purposes, unless you specify otherwise in writing.

In addition, the instructor retains the right to use any code or project artifacts developed in the course for pedagogy, research, or service learning purposes. Student web project code developed in the course may be used in future secure project development courses, by the instructor for research purposes, or by designated stakeholders.

## License  
IA/CYBR Capstone
Copyright (C) 2016-2017  Dr. Matthew L. Hale

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

## What does GPLv3 mean?

[tl;drLegal summary](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)
