# PB173/oss: Open Source Development Course

The main goal of the course is to help and encourage university students to join the development of real-world open-source software. The course consists of 4–5 hosted lectures by senior developers, two small homework assignments and quite a bit of open-source development. We closely cooperate with [Red Hat Open Source Contest](https://research.redhat.com/red-hat-open-source-contest/).

The information in this file reflect the spring semester of 2020. For information on older semesters, see [autumn 2019](2019-autumn).

## Course requirements

In order to pass the course, the student must:

* **Contribute to an existing open-source project in scope of 50-60 hours.**  
The student chooses the open-source project for contribution themself, but this selection must be approved by the teachers till 1st of March. Tasks from the [Red Hat Open Source Contest](https://research.redhat.com/red-hat-open-source-contest/) are pre-approved. If you choose elsewhere, look for known active projects that you are not yet part of.
* **Track time spent on the project.**  
The student has to have a detailed report on time spent on the course. The tracking has to be automatic (e.g. using [Toggl](https://toggl.com/) or similar). The tracking must be task-based (i.e. per-day report is not sufficient). Each reported period must have a start-time, end-time, short work description and a category (analysis/implementation/management).
* **Hand in three compulsory homework assignments.**  
These will cover git, CI/CD systems, pull requests, basic developer best practices and open-source licences. An approximate description of tasks can be found in the file [assignments.md](assignments.md).
* **Deliver three short presentation (10 minutes talks) about your work.**  
This will be the initial work planning, mid-term progress update and final presentation at the end.
* **(optionally) Attend lectures on open source development**  
The lectures provided are not compulsory but are highly recommended.

## Technicalities

* **IS course info:** https://is.muni.cz/course/fi/spring2020/PB173
* **Lecture time:** Thursdays, 10:00-11:40
* **Lecture room:** FI MU S505 Red Hat lab (note that the room is only available during lecture time)
* **Admission:** All the lectures are public, open to anyone

## Lecture Overview

### Week 1 (20. 2.): Course intro ([slides](01-intro.pdf))

* Course structure and requirements
* Red Hat Open Source Contest
* Choosing a project (basic liveness checks)

### Week 2 (27. 2.): Git workshop ([slides](02-git.pdf), [feedback](https://forms.gle/GDYPpMtoqwgje2n67))

* _Delivered by Irina Gulina (Red Hat) and Tomáš Tomeček (Red Hat), this talk will be in English_
* **Workshop-style: Bring your notebook!**
* Recap of git basics (workflow, commits, remotes, ...)
* Git in multi-developer setup (branching, merging, conflicts, ...)
* Power features in git (rebase, reorder, squash, stash, cherry-pick, ...)
* Pull requests and their adjustments
* Solving local and public trouble
* Git etiquette (good and bad practices)

### Week 3 (5. 3.): Introduction to the open-source world ([slides](03-opensource-intro.pdf), [feedback](https://forms.gle/GDYPpMtoqwgje2n67))

* _Delivered by Milan Brož (Red Hat)_
* Proprietary vs. open
* Open source project management and infrastructure
* Open source licensing
* Open source culture
* Communication (and politics and psychology)
* View of the maintainer

### Week 4 (12. 3.): Student status update 1

** Coronavirtus adjustment: The status update will take place using a videoconference.**

* Short talks of the current progress (max 10 minutes)
* The presentation should include:
  * Introduce the project you chose (the others should understand, what it is good for).
  * What do you plan to do? (What will the contribution probably be?) If there are specific issues/bug reports you plan to address, mention them.
  * State what have you already done: Ran and used the project? Successfully build the project? Dived into documentation? Developeed something? ...
  * What system do you use to track time? How much time have you already spent on the project?

### Week 5 (19. 3.): Project management and lifecycle ([annotated slides](https://docs.google.com/presentation/d/1m4zzmnCjp3cyBYM9LcZuBpSxHNI-Ki91kzTvS5pUUVk/edit#slide=id.g61dbcadc6f_0_785))

** Coronavirtus adjustment: Lecture in person cancelled, annotated slides will be available.**

* _Delivered by Marek Čermák (Red Hat)_
* Different views of the project
* Project planning, lifecycle and versioning
* Basic contribution workflow
* Software dependencies
* Security aspects of development

### Week 6 (26. 3.): Continuous integration and development (CI/CD) ([slides](06-ci-cd.pdf), [annotated slides](06-ci-cd-with-notes.pdf))

** Coronavirtus adjustment: Lecture in person cancelled, annotated slides will be available.**

* _Delivered by Vojtěch Trefný (Red Hat)_
* CI/CD pipeline
* Code style and documentation
* Build tools
* Tests and coverage
* Packaging and publishing

### Week 7 (2. 4.): No lecture

* Consultations possible

### Week 9 (9. 4.): No lecture

* Consultations possible

### Week 8 (16. 4.): Student status update 2

* 10 minutes talks of the current progress
* Short reminder of what is the project about is good, though much shorter than in status update 1
* Present the reflection of your plan (Has it gone as you wanted/expected?) and its revision (if necessary)
* Slides are required (to keep the presentation clear and flowing)
* Include slide with your time sheet spent on the project, high granularity (dates, work items, amounts). Also add summary stats on time spent on a) study b) coding c) communication/management

### Week 10 (23. 4.): Open source licences

* _Delivered by Milan Zamazal (Red Hat) and Pavel Loutocký (Institute of Law and Technology, MU)_
* Basic legal context of software licences
* Understanding the differences: free, libre, open-source, proprietary, FOSS, FLOSS
* Common software licenses (MIT, BSD, Apache, ...)
* GPL+LGPL, their benefits and their specifics
* Licensing your code

### Week 11 (30. 4.): No lecture  

* Consultations possible

### Week 12 (7. 5.): No lecture  

* Consultations possible

### Week 13 (14. 5.): No lecture

* No lectuure (Dies Academicus, Industry partners day)

### Week 14 (21. 5.): Final presentations

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
