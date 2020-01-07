# Homework assignments

The course has two compulsory homework assignments.

## 1: Single-developer scenario (deadline 30. 11.)

Prove you have elementary knowledge of git, GitHub, CI/CD systems and developer best practices.

* Setup a GitHub repository under your personal account, called `ossdev-01-${UCO}`, e.g., `ossdev-01-325219`
* Commit a small piece of code with simple functionality in `{C, C++, Java, Kotlin, Python, PHP}`. Assignment: take input two numbers `a, b`, print all primes in the interval `[a, b]`. Use algorithm of your choice (e.g., trial division, sieve). It us just a demo, not an algorithmic competition.
* Properly cover the implemented feature by tests and documentation.
* Setup a build system of your choice (makefile, cmake, gradle, ...) compiling the project (if relevant) and running the tests.
* Setup a CI/CD system (e.g. Travis, which is recommended on the GitHub).
* Setup at least one extra step as a part of the CI process (e.g. style check).
* Submit `repo.txt` to the IS file vault with the single line, the URL for your GitHub repository (HTTPS web view).
* Submit detailed timesheet to the IS file vault named `time.txt`, which will have separate entries for a) coding, b) implementing tests c) writing docs d) setting up project / build system / style check. 
  
## 2: Multi-developer scenario

**[WIP] draft.**

Prove you can use git to interact with existing reositories, resolve conflicts and adjust git history.
Create a text file `ossdev-hw-02-uco.txt` and mark mentioned info to the file as noted below.

Setup signed commits on GitHub. Signed commit is a hard requirements for a PR to merge.

### Step 1
- Fork https://github.com/ph4r05/ossdev-hw-02-step1. It is a very simple Python implementation of a vector with simple operations.
- Create a new branch called `pr/step1`
- Implement missing features marked by `# TODO` at least 1 commit.
- Implement missing tests for those functions. Very simple tests will do. There is an example of a test already. At least 1 commit.
- Make sure Travis is running on your newly added commits.
- Add Travis badge to the Readme
- Add simple info about supported operations to the Readme
- Write down all commit IDs (hash) to the file. There should be at least 2 separate commits.
- Create a PR with your changes against the forked repo, PR name has to start with `[WIP] [UCO]: ` with your UCO.
- After PR is ready, reviewer tells you to add a simple python comment to the `__mul__` and to squash all the commits then. 
Before doing the squash, create a branch `pr/step1-old` that points to your current HEAD. (so we can access the old commits before the squash).
- Do as reviewer told you, in the PR-branch `pr/step1`. Write down a commit ID.
- Notify reviewer its done with a PR comment, remove `[WIP]` from the PR title as your PR is approved now.
- Please, Do not look at the step 2 before finishing step 1. We want to see the conflicts! >:) 

### Step 2
Something happened, 2 months passed, repository changed the maintainer and changed somehow.

- Add a new remote to your fork: `https://github.com/ph4r05/ossdev-hw-02-step2`
- Create a new branch `pr/step2` that points to your HEAD.
- Rebase all your changes on top of the `ossdev-hw-02-step2/master`
- Fix conflicts reasonably.
- Fix all remaining TODOs and add a minor tests in a separate commit.
- Create a new PR in a new repository, the previous PR has to be left intact
- Create a branch `pr/step2-old` that points to your HEAD. Note new commit IDs to the file.
- Same as before - squash to one commit.
- Add a comment to the PR saying "Done".
