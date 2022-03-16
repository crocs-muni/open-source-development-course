# PB173/oss: Open Source Development Course

Do you want to:

* contribute to an open-source project of your choosing,
* have your work in an upstream project,
* help a project/tool you use,
* and earn a few credits while doing so?

Then this seminar group of the PB173 course is for you!

The main goal of the course is to help and encourage university students to join the development of real-world open-source software (in any programming language). The course consists of 5–6 hosted lectures by senior developers, three small homework assignments and quite a bit of open-source development.

The information in this file reflects tentative information for the spring semester of 2022. For information on older semesters, see [spring 2021](2021-spring/README.md) and [spring 2020](2020-spring/README.md).

## Course requirements

In order to pass the course, the student must:

* **Contribute to an existing open-source project of your choice.**  
Having your pull request accepted during the semester is not required to pass the course (as we cannot guarantee responsive maintainers). Note that the project selection must be approved by the teachers till the end of the second week of the semester. Look for known active projects that you are not yet part of.
* **Track time spent on the project.**  
The student has to have a detailed report on time spent on the course. You should use a suitable electronic tool for time tracking (we have poor experience with pen-and-paper tracking) – we recommend [Toggl Track](https://toggl.com/) or similar. The tracking must be task-based (i.e. per-day report is not sufficient). Each reported period must have a start-time, end-time, short work description and a category (at least analysis/implementation/management). You are expected to spend about 50 hours on the project (all time including studying documentation, analyzing code, coding as well as communicating with maintainers). In case of doubt, feel free to ask (the time tracker won't be a deal-breaker, don't worry :-)).
* **Hand in three compulsory homework assignments.**  
These will cover git, CI/CD systems, pull requests, basic developer best practices and open-source licenses. An approximate description of tasks can be found in the file [assignments.md](assignments.md).
* **Deliver three short presentation (10 minutes talks) about your work.**  
This will be the initial work planning, mid-term progress update and final presentation at the end.
* **Attend lectures on open source development**  
The lectures provided by the industrial experts are strongly recommended.

## Technicalities

* **IS course info:** https://is.muni.cz/course/fi/spring2022/PB173
* **Lecture time:** Wednesdays, 10:00-11:40
* **Lecture room:** FI MU S505 Red Hat lab (note that the room is only available during lecture time)
* **Admission:** All the lectures are public, open to anyone

Even though the course information lists C and C++ as pre-requisites, the language used in the open-source project contribution is up to the student.

## Lecture Overview

The lecture overview is only **tentative**: The individual lectures may still be shifted to other weeks in accordance with lecturer availability.

### Week 1 (16.2.): Course intro ([slides](01-intro.pdf))

* Course structure and requirements
* Red Hat Open Source Contest
* Basic project attributes (liveness check)
* Tips for looking for a good OSS project

### Week 2 (23. 2.): Project selection ([slides](02-project-selection.pdf))

* Searching for suitable projects (with consultations)
* Students have to choose a suitable project by the end of the week (otherwise they have to un-enroll the course).

### Week 3 (2. 3.): Introduction to the open-source world ([slides](03-opensource-intro.pdf))

* _Delivered by Milan Brož (independent engineer)_
* Proprietary vs. open
* Open source project management and infrastructure
* Open source licensing
* Open source culture
* Communication (and politics and psychology)
* View of the maintainer

### Week 4 (9. 3.): Student status update 1

* Short talks of the current progress (about 10 minutes)
* You are required to have presentation slides to structure your talk (upload them in IS MU beforehand)
* The presentation should include:
  * Introduce the project you chose (the others should understand, what it is good for, how it works, ...).
  * What do you plan to do? (What will the contribution probably be?) If there are specific issues/bug reports you plan to address, mention them.
  * State what have you already done: Ran and used the project? Successfully build the project? Dived into documentation? Developeed something? ...
  * What system do you use to track time? How much time have you already spent on the project?

### Week 5 (16. 3.): Lifecycle of open source contribution, software dependencies ([slides](05-lifecycle.pdf))

* _Delivered by Vojtěch Trefný (Red Hat)_
* Basic contribution workflow
* Issues, forks, pull requests (illustrated on GitHub)
* Software dependencies
* Security aspects of software dependencies
* Peeks into security of development and licensing

### Week 6 (23. 3.): Continuous integration and deployment (CI/CD)

* _Delivered by Vojtěch Trefný (Red Hat)_
* CI/CD pipeline
* Code style and documentation
* Build tools
* Tests and coverage
* Packaging and publishing

### Week 7 (30. 3.): Mind your Git manners

* _Delivered by Irina Gulina (Red Hat) and Tomáš Tomeček (Red Hat), this talk will be in English_
* Commits and commit messages
* Forking and branching
* Push
* PR/MR submitting and review
* Quiz, Q/A

### Week 8 (6. 4.): No lecture

* Consultations possible

### Week 9 (13. 4.): Student status update 2

* 10 minutes talks of the current progress
* Short reminder of what is the project about is good, though much shorter than in status update 1
* Present the reflection of your plan (Has it gone as you wanted/expected?) and its revision (if necessary)
* Slides are required (to keep the presentation clear and flowing)
* Include slide with your time sheet spent on the project, high granularity (dates, work items, amounts). Also add summary stats on time spent on a) study b) coding c) communication/management

### Week 10 (20. 4.): Technical documentation writing

* _Delivered by Shweta Jalgaonkar (Red Hat), Vendula Ferschmannova (Red Hat) and Sarka Jana Janderkova (Red Hat), this talk will be in English_
* Documentation and technical writing in software projects
* The process of technical writing
* TechWriting specifics

### Week 11 (27. 4.): Open source licenses

* _Delivered by Milan Zamazal (Red Hat) and Pavel Loutocký (Institute of Law and Technology, MU)_
* Basic legal context of software licenses
* Understanding the differences: free, libre, open-source, proprietary, FOSS, FLOSS
* Common software licenses (MIT, BSD, Apache, ...)
* GPL+LGPL, their benefits and their specifics
* Licensing your code

### Week 12 (4. 5.): No lecture

* Consultations possible

### Week 13 (11. 5.): Final presentations

* Deadline for finishing the open source contributions (exceptions allowed in justified cases)
* Final project presentations (10 minutes, slides required)
* Start with a short (!) reminder of what is the project about
* Present the work that you have done (including the information whether this was merged upstream or not)
* In the slides, include the final overview of time spent on the project, split to a) study b) coding c) communication/management
* Summarize the things you have learned by doing the open-source contribution (avoid general formulations, try to be specific and don't wave this off in 1 minute – it's important)
* Really, we mean the previous bullet point. What would you not know if you did not participate in the course? Both positive and negative (and neutral) learning are meant to be shared.
* Before the lecture (till Wednesday night), please submit these files to the IS vault
  * Slides of your final presentation (PDF)
  * The detailed time sheet of your contribution
  * A list of your pull requests (a simple text file with a couple of links is sufficient)

### Week 14 (18. 5.): Final presentations (backup date)

* Only used if necessary.
