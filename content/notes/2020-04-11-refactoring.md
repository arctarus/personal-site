---
title: Refactoring
description: A technique for improve existing code
date: 2020-04-11T23:27:48+02:00
tags:
- extreme programming
- refactoring
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

## External links
* Refactoring [web](https://www.refactoring.com/) and [book](https://www.amazon.com/gp/product/B007WTFWJ6/ref=as_li_qf_asin_il_tl?ie=UTF8&tag=arctaruscom-20&creative=9325&linkCode=as2&creativeASIN=B007WTFWJ6&linkId=7bafb78eced674869ad97f872a966d98) by Martin Fowler.

## Related notes
* [When to refactor]({{< relref "/notes/2020-04-12-when-to-refactor.md" >}}).
* [Flocking rules]({{< relref "/notes/2020-04-05-flocking-rules.md" >}}): A refactoring technique.
