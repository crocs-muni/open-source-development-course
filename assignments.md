# Homework assignments

The course has two compulsory homework assignments.

**The precise task is not set, but you can find an approximate description below to know what to expect.**

## 1: Single-developer scenario

Prove you have elementary knowledge of git, GitHub, CI/CD systems and developer best practices.

* Setup a GitHub repository under your personal account, called `ossdev-01-${UCO}`, e.g., `ossdev-01-325219`
* Commit a small piece of code with simple functionality in `{C, C++, Java, Kotlin, Python, PHP}`. Assignment: take input two numbers `a, b`, print all primes in the interval `[a, b]`. Use algorithm of your choice (e.g., trial division, sieve). It us just a demo, not an algorithmic competition.
* Properly cover the implemented feature by tests and documentation.
* Setup a build system of your choice (makefile, cmake, gradle, ...).
* Setup a CI/CD system (e.g. Travis, which is recommended on the GitHub).
* Setup style check or other extra step as a part of the CI process.
* Submit detailed timesheet to the IS file vault named `${UCO}_time.txt`, which will have separate entries for a) coding, b) implementing tests c) writing docs d) setting up project / build system / style check. 
* Submit `${UCO}.txt` to the IS file vault with the single line, the URL for your GitHub repository (HTTPS web view)
  
## 2: Multi-developer scenario

Prove you can use git to interact with existing reositories, resolve conflicts and adjust git history.

- Fork repository prepared by the teachers.
- Fix the small assigned issue (add a new feature, add a corresponding test, adjust documentation, file a proper pull request).
- React to comments in your pull request and adjust it accordingly (may contain adding code, adjustnig commit messages, rebasing or other issues).
