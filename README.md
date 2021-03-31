# PB173/oss: Open Source Development Course

The main goal of the course is to help and encourage university students to join the development of real-world open-source software (in any programming language). The course consists of 5–6 hosted lectures by senior developers, two small homework assignments and quite a bit of open-source development.

The information in this file reflect the spring semester of 2021. For information on older semesters, see [spring 2020](2020-spring/README.md) and [autumn 2019](2019-autumn/README.md).

## Course requirements

In order to pass the course, the student must:

* **Contribute to an existing open-source project in scope of 50-60 hours.**
The student chooses the open-source project for contribution themselves, but this selection must be approved by the teachers till 14th of March. Look for known active projects that you are not yet part of.
* **Track time spent on the project.**
The student has to have a detailed report on time spent on the course. The tracking has to be automatic (e.g. using [Toggl](https://toggl.com/) or similar). The tracking must be task-based (i.e. per-day report is not sufficient). Each reported period must have a start-time, end-time, short work description and a category (analysis/implementation/management).
* **Hand in three compulsory homework assignments.**
These will cover git, CI/CD systems, pull requests, basic developer best practices and open-source licenses. An approximate description of tasks can be found in the file [assignments.md](assignments.md).
* **Deliver three short presentation (10 minutes talks) about your work.**
This will be the initial work planning, mid-term progress update and final presentation at the end.
* **Attend lectures on open source development**
The lectures provided by the industrial experts are strongly recommended.

## Technicalities

* **IS course info:** https://is.muni.cz/course/fi/spring2021/PB173
* **Lecture time:** Wednesdays, 10:00-11:40
* **Lecture room:** The lectures will take place on [Zoom](https://zoom.us/download), always in the following room: https://cesnet.zoom.us/j/92608827888?pwd=SnVka2Zld1dOTGpnd295SktCL1BWUT09#success
* **Admission:** All the lectures are public, open to anyone

## Lecture Overview

### Week 1 (3. 3.): Course intro ([slides](01-intro.pdf))

* Course structure and requirements
* Red Hat Open Source Contest
* Choosing a project (basic liveness checks)

### Week 2 (10. 3.): Introduction to the open-source world ([slides](02-opensource-intro.pdf))

* _Delivered by Milan Brož (Red Hat)_
* Proprietary vs. open
* Open source project management and infrastructure
* Open source licensing
* Open source culture
* Communication (and politics and psychology)
* View of the maintainer

### Week 3 (17. 3.): Student status update 1

* Short talks of the current progress (about 10 minutes)
* You are required to have presentation slides to structure your talk (upload them in IS MU beforehand)
* The presentation should include:
  * Introduce the project you chose (the others should understand, what it is good for, how it works, ...).
  * What do you plan to do? (What will the contribution probably be?) If there are specific issues/bug reports you plan to address, mention them.
  * State what have you already done: Ran and used the project? Successfully build the project? Dived into documentation? Developeed something? ...
  * What system do you use to track time? How much time have you already spent on the project?

### Week 4 (24. 3.): Lifecycle of open source contribution, project management ([slides](04-lifecycle.pdf))

* _Delivered by Vojtěch Trefný (Red Hat)_
* Basic contribution workflow
* Issues, forks, pull requests (illustrated on GitHub)
* Software dependencies
* Security aspects of software dependencies
* Peeks into security of development and licencing

### Week 5 (31. 3.): Continuous integration and deployment (CI/CD) ([slides](05-ci-cd.pdf))

* _Delivered by Vojtěch Trefný (Red Hat)_
* CI/CD pipeline
* Code style and documentation
* Build tools
* Tests and coverage
* Packaging and publishing

### Week 6 (7. 4.): Git workshop

* _Delivered by Irina Gulina (Red Hat) and Tomáš Tomeček (Red Hat), this talk will be in English_
* **Workshop-style: Bring your notebook!**
* Recap of git basics (workflow, commits, remotes, ...)
* Git in multi-developer setup (branching, merging, conflicts, ...)
* Power features in git (rebase, reorder, squash, stash, cherry-pick, ...)
* Pull requests and their adjustments
* Solving local and public trouble
* Git etiquette (good and bad practices)

### Week 7 (14. 4.): No lecture

* Consultations possible

### Week 8 (21. 4.): Student status update 2

* 10 minutes talks of the current progress
* Short reminder of what is the project about is good, though much shorter than in status update 1
* Present the reflection of your plan (Has it gone as you wanted/expected?) and its revision (if necessary)
* Slides are required (to keep the presentation clear and flowing)
* Include slide with your time sheet spent on the project, high granularity (dates, work items, amounts). Also add summary stats on time spent on a) study b) coding c) communication/management

### Week 9 (28. 4.): Technical documentation writing

* _Delivered by Shweta Jalgaonkar (Red Hat), this talk will be in English_
* Documentation and technical writing in software projects
* The process of technical writing
* TechWriting specifics

### Week 10 (5. 5.): Open source licenses

* _Delivered by Milan Zamazal (Red Hat) and Pavel Loutocký (Institute of Law and Technology, MU)_
* Basic legal context of software licenses
* Understanding the differences: free, libre, open-source, proprietary, FOSS, FLOSS
* Common software licenses (MIT, BSD, Apache, ...)
* GPL+LGPL, their benefits and their specifics
* Licensing your code

### Week 11 (12. 5.): No lecture

* Consultations possible

### Week 12 (19. 5.): No lecture

* Consultations possible

### Week 13 (26. 5.): Final presentations

* Deadline for finishing the open source contributions (exceptions allowed in justified cases)
* Final project presentations (10 minutes, slides required)
* Start with a short (!) reminder of what is the project about
* Present the work that you have done (including the information whether this was merged upstream or not)
* In the slides, include the final overview of time spent on the project, split to a) study b) coding c) communication/management
* Summarize the things you have learned by doing the open-source contribution (avoid general formulations, try to be specific and don't wave this off in 1 minute – it's important)
* Really, we mean the previous bullet point. What would you not know if you did not participate in the course? Both positive and negative (and neutral) learning are meant to be shared.
* Before the lecture (till Wednesday night), please submit these files to the IS vault
  * Slides of your final presentation (PDF)
  * The detailed timesheet of your contribution
  * A list of your pull requests (a simple text file with a couple of links is sufficient)
