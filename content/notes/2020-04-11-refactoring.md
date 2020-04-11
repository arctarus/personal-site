---
title: Refactoring
description: A technique for improve existing code
date: 2020-04-11T23:27:48+02:00
tags:
- extreme programming
- refactoring
- quality
---

Refactoring is a technique for restructuring code in a way that you improve the design, but don't change the its external behaviour.

It is done applying a serie of small transformations to the code (called a "refactor"), and using test to ensure the external behaviour never changes.

Thanks that each refactor is small, if something goes wrong and a test fails, is easy go back, undo the changes, minimizing the probability that a bug can be introduced.

The purpose of refactoring is to make the software easier to understand and modify, not improve the performance.

Why should you refactor?

* Improves the design of software.
* Makes software easier to understand.
* Helps you find bugs.
* Helps you program faster.
