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
may be ignored once a better `.gitignore` file has been added to the repo.

A branch can be pushed to the remote github repo with the following command.

`git push origin dleblanc/abstract-factory`

This should only be executed after a pull from master to resolve any merge conflicts.

## Peer Review Process

Once a branch has been pushed to the remote repo a PR should be raised against master. The 
changes should be reviewed by all team members before the final merge to master. Once the merge 
is complete the branch can be deleted.
