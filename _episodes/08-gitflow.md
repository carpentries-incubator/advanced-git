---
title: "GitFlow"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

Considered to be a bit complicated and advanced for many of today’s projects, `GitFlow` enables parallel development where developers can work separately from the master branch on features where a feature branch is created from the master branch.

Afterwards, when changes are complete, the developer merges these changes back to the master branch for release.

This branching strategy consists of the following branches:

- Master
- Develop
- Feature- to develop new features that branches off the develop branch
- Release- help prepare a new production release; usually branched from the develop branch and must be merged back to both develop and master
- Hotfix- also helps prepare for a release but unlike release branches, hotfix branches arise from a bug that has been discovered and must be resolved; it enables developers to keep working on their own changes on the develop branch while the bug is being fixed.

The main and develop branches are considered to be the main branches, with an infinite lifetime, while the rest are supporting branches that are meant to aid parallel development among developers, usually short-lived.

## GitFlow pros and cons

Perhaps the most obvious benefit of this model is that it allows for parallel development to protect the production code so the main branch remains stable for release while developers work on separate branches.

Moreover, the various types of branches make it easier for developers to organize their work. This strategy contains separate and straightforward branches for specific purposes though for that reason it may become complicated for many use cases.

It is also ideal when handling multiple versions of the production code.

However, as more branches are added, they may become difficult to manage as developers merge their changes from the development branch to the main. Developers will first need to create the release branch then make sure any final work is also merged back into the development branch and then that release branch will need to be merged into the main branch.

In the event that changes are tested and the test fails, it would become increasingly difficult to figure out where the issue is exactly as developers are lost in a sea of commits.

Indeed, due to GitFlow’s complexity, it could slow down the development process and release cycle. In that sense, GitFlow is not an efficient approach for teams wanting to implement continuous integration and continuous delivery.


![GitFlow 1](../fig/17-gitflow-1.png)
![GitFlow 1](../fig/18-gitflow-2.png)
![GitFlow 1](../fig/19-gitflow-3.png)
![GitFlow 1](../fig/20-gitflow-4.png)
![GitFlow 1](../fig/21-gitflow-5.png)
![GitFlow 1](../fig/22-gitflow-6.png)
![GitFlow 1](../fig/23-gitflow-7.png)
![GitFlow 1](../fig/24-gitflow-8.png)
![GitFlow 1](../fig/25-gitflow-9.png)
![GitFlow 1](../fig/26-gitflow-10.png)




https://www.flagship.io/git-branching-strategies/


{% include links.md %}
