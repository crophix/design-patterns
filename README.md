# Design Patterns

This repository is intended to be a collection of documentation and examples of various 
software engineering design patterns. The patterns are based on "Design Patterns: Elements of 
Reusable Object-Oriented Software" by Gamma et al.

All examples are the result of collaborative work by Mike Lane, Daniel Leblanc, and David Lu.

## Git branching instructions

All work on this project should be done on a branch so that PRs can be reviewed by the group.
Creating a branch can be done with the following command, which creates a new branch and checks
out that branch as active.

`git checkout -b dleblanc/abstract-factory`

Branch names should contain a user name followed by a descriptive title. Changes should be added
on a per file bases without using `git add -a` to avoid including unwanted code in the repo. This 
may be ignored once a better `.gitignore` file has been added to the repo. A general outline of the
commands required for adding and commiting changes is shown here.

`git add src/main/java/edu/pdx/design-patterns/*`

`git commit -m "Examples changes to code"`

A branch can be pushed to the remote github repo with the following command.

`git push origin dleblanc/abstract-factory`

This should only be executed after a pull from master to resolve any merge conflicts.

## Peer Review Process

An ideal PR will remain relatively small so that the review can be thorough. Making extensive
changes can be acceptable if the goal is refactoring existing functionality, but that type of
work should be separate from new features to keep the reviews focussed.

Once a branch has been pushed to the remote repo a PR should be raised against master. The 
changes should be reviewed by all team members before the final merge to master. Once the merge 
is complete the branch can be deleted.

All code should follow the standard java style guidelines. 
[Google's style guide](https://google.github.io/styleguide/javaguide.html)
