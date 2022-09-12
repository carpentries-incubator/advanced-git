---
title: "Branching Models"
teaching: 0
exercises: 0
questions:
- "What is a branching model?"
- "Why do you need one?"
- "What are the most common branching models?"
objectives:
- "Learn about the importance of a branching model."
keypoints:
- "A branching model is a pre-agreed way of merging branches into the main branch."
- "A branching model is needed when multiple contributors are making changes to a single project."
---

## What is a branching model/strategy?

Branches are primarily used as a means for teams to develop features giving them a separate workspace for their code. These branches are usually merged back to a master branch upon completion of work. In this way, features (and any bug and bug fixes) are kept apart from each other allowing you to fix mistakes more easily.

This means that branches protect the mainline of code and any changes made to any given branch don’t affect other developers.

A branching strategy, therefore, is the strategy that software development teams adopt when writing, merging and deploying code when using a version control system.

It is essentially a set of rules that developers can follow to stipulate how they interact with a shared codebase.

Such a strategy is necessary as it helps keep repositories organized to avoid errors in the application and the dreaded merge hell when multiple developers are working simultaneously and are all adding their changes at the same time. Such merge conflicts would eventually deter the combination of contributions from multiple developers.

Thus, adhering to a branching strategy will help solve this issue so that developers can work together without stepping on each other’s toes. In other words, it enables teams to work in parallel to achieve faster releases and fewer conflicts by creating a clear process when making changes to source control.

When we talk about branches, we are referring to independent lines of code that branch off the master branch, allowing developers to work independently before merging their changes back to the code base.

In this and the following episodes, we will outline some of the branching strategies that teams use in order to organize their workflow where we will look at their pros and cons and which strategy you should choose based on your needs, objectives and your team’s capabilities.

## Why do you need a branching model?

As mentioned above, having a branching model is necessary to avoid conflicts when merging and to allow for the easier integration of changes into the master trunk.

A BRANCHING MODEL AIMS TO:
- Enhance productivity by ensuring proper coordination among developers
- Enable parallel development
- Help organize a series of planned, structured releases
- Map a clear path when making changes to software through to production
- Maintain a bug-free code where developers can quickly fix issues and get these changes back to production without disrupting the development workflow

![Branching 1](../fig/15-branching-1.png)
![branching 2](../fig/16-branching-2.png)


{% include links.md %}
