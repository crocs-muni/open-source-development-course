# PB173/oss: Autumn 2019

Details of the open source development course for the autumn semester of 2019.

The main goal of the course is to help and encourage university students to join the development of real-world open-source software. The course consists of 4–5 hosted lectures by senior developers, two small homework assignments and quite a bit of open-source development. We closely cooperate with [Red Hat Open Source Contest](https://research.redhat.com/red-hat-open-source-contest/).

## Course requirements

In order to pass the course, the student must:

* **Contribute to an existing open-source project in scope of 50-60 hours.**  
The student chooses the open-source project for contribution themself, but this selection must be approved by the teachers till 29th September. Tasks from the [Red Hat Open Source Contest](https://research.redhat.com/red-hat-open-source-contest/) are pre-approved. If you choose elsewhere, look for known active projects that you are not yet part of.
* **Track time spent on the project.**  
It is beneficial to develop such a habbit for further contract work the student could have later. (Teacher recommendation: [Toggl](https://toggl.com/) is nice, but pen-and-paper also work.) Detailed time sheets are required to pass the course. It has to be fine-grained, i.e., each work unit has to be stored in the time sheet, with corresponding date, time elapsed and work you did in that period. It is highly recommended to use Toggl, which does the tracking.
* **Hand in two compulsory homework assignments.**  
These will cover git, CI/CD systems, pull requests and basic developer best practices. An approximate description of tasks can be found in the file [assignments.md](assignments.md).
* **Deliver three short presentation (10 minutes talks) about your work.**  
This will be the initial work planning, mid-term progress update and final presentation at the end.
* **(optionally) Attend lectures on open source development**  
The lectures provided are not compulsory but are highly recommended.

## Technicalities

* **IS course info:** https://is.muni.cz/course/fi/autumn2019/PB173
* **Lecture time:** Wednesdays, 10:00-11:40
* **Lecture room:** FI MU S505 Red Hat lab (note that the room is only available during lecture time)
* **Admission:** All the lectures are public, open to anyone

## Lecture Overview

### Week 1 (18. 9.): Course intro ([slides](01_course-intro.pdf))

* General course overview
* Course plan, requirements, Red Hat Open Source Contest

### Week 2 (25. 9.): Introduction to the open-source world ([slides](02_opensource-intro.pdf))

* _Delivered by Milan Brož (Red Hat)_
* What does open source development include?
* Short introduction to licencing
* Examples of project management
* Project culture and best practices
* The world of project maintainers
* Communication among developers
* Open source communities, open source in Brno

### Week 3 (2. 10.): Introduction to Git (optional)

* _This lecture **WILL NOT happen**, as all the students seem to already know the git basics._
* Basic git principles and commands
* Commits, staging, pull/push, branches
* GUIs, GitHub integration

### Week 4 (9. 10.): Project management, build pipeline and lifecycle ([slides](04_project-management-build-ci.pdf))

* _Delivered by Vojtěch Trefný (Red Hat), Marek Čermák (Red Hat)_
* Control source versioning
* Project management, build tools, CI/CD
* Documentation, code style
* Dependency management, publishing, packaging and repositories
* Security aspects of development

### Week 5 (16. 10.): Student status update 1

* Short talks of the current progress (max 10 minutes)
* The presentation should include:
  * Introduce the project you chose (the others should understand, what it is good for).
  * What do you plan to do? (What will the contribution probably be?)
  * State what have you already done: Ran and used the project? Successfully build the project? Dived into documentation? Developeed something? ...
  * What system do you use to track time? How much time have you already spent on the project?

### Week 6 (23. 10.): Advanced usage of Git ([slides](06_advanced-git.pdf), [git sandbox](http://bit.ly/devconf19-gtw))

* _Delivered by Irina Gulina (Red Hat), this talk will be in English_
* Git in multi-developer setup (branching, merging, conflicts, ...)
* Power features in git (rebase, reorder, squash, stash, cherry-pick, conflicts with history overwrite, ...)
* Advanced features (submodules, LFS, commit signing, ...)
* Good and bad practices
* GitHub specifics (cross-referencing issue/PR/commit, code review, PR labeling, ...)

### Week 7 (30. 10.): No lecture

* Consultations possible

### Week 8 (6. 11.): Student status update 2

* 10 minutes talks of the current progress
* Short reminder of what is the project about is good, though much shorter than in status update 1
* Present the reflection of your plan (Has it gone as you wanted/expected?) and its revision (if necessary)
* Slides are required (to keep the presentation clear and flowing)
* Include slide with your time sheet spent on the project, high granularity (dates, work items, amounts). Also add summary stats on time spent on a) study b) coding c) communication/management

### Week 9 (13. 11.): Open source licences ([slides](09_open-source-licences.pdf))

* _Delivered by Milan Zamazal (Red Hat) and Pavel Loutocký (Institute of Law anf Technology, MU)_
* Historical overview
* Understanding the differences: free, libre, open-source, proprietary, FOSS, FLOSS
* Common software licenses (MIT, BSD, Apache, ...)
* GPL+LGPL, their benefits and their specifics
* Licencing your code
* Legal aspects of open-source licences

### Week 10 (20. 11.): No lecture

* Consultations possible

### Week 11 (27. 11.): No lecture  

* Consultations possible

### Week 12 (4. 12.): Final presentations

* Deadline for finishing the open source contributions (exceptions allowed in justified cases)
* Final project presentations (10 minutes, slides required)
* Start with a short (!) reminder of what is the project about
* Present the work that you have done (including the information whether this was merged upstream or not)
* Include the final overview of time spent on the project, split to a) study b) coding c) communication/management
* Summarize the hings you have learned by doing the open-source contribution (avoid general formulations, try to be specific and don't wave this off in 1 minute – it's important)
* Before the lecture, please submit these files to the IS vault
  * Slides of your final presentation (PDF)
  * The detailed timesheet of your contribution
  * A list of your pull requests (a simple text file with a couple of links is sufficient)

### Week 13 (11. 12.): No lecture

* Unofficial meetings (=beer) possible
