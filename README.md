# Test_011
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Initial Commit
* Commit updating ReadMe
* Commit Before Rebasing Feature Branch conflicting with Feature

## Changes Made In This Repo

* Create a feature branch from main and make a commit on that branch.
* Create a second commit on the main branch.
* Create a sub-feature branch based on the feature branch and make a commit on the sub-feature branch
* Make a commit on the sub-feature that will conflict with feature.
* Make a commit on the feature branch that also conflicts with sub-feature
* Then rebase it with the sub-feature branch using a PR. Resolve conflicts
* Create a third commit on the main branch that conflicts with the sub feature branch.
* Create multiple on the feature branch and then raise a PR and rebase the feature branch with the main branch.
