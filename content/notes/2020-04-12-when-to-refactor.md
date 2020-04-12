---
title: When to Refactor
description: Never set time aside to do it
date: 2020-04-12T17:27:40+02:00
tags:
- extreme programming
- refactoring
---
Refactoring is not an activity you should set time aside to do. You refactor because you want to do something else and refactoring helps you with that other thing.

So, when should you refactor:

## The rule of three

The third time you do something similar, you should refactor it.

## When you add a function

1. You want to add a feature to an existing code you have written or have been written by someone else. Refactoring helps you clarify the code so next time you you pass there you can understand it easily.

2. You want to add a feature to an existing code but the the design doesn't allow you do it easily. You can refactor first the code, so you refactor it so this change and future changes can be added easily.

## When you need to fix a bug

When you have a bug, it's probable that the problem was that the code wasn't clear enough, so one thing you can do is refactor it to improve it's understanding, and this active process of working with the code helps in finding the bug.

## As you do a code review

While you are reviewing someone else's code, you can apply some of your suggestions to see what the code looks like, then you can come up with a second level of ideas, what would make the code better and you end up with much more sense of accomplishment.

## Refactoring for Greater Understanding

Work on refactor a large code base during some days will improve your understanding of that code a lot, what will allow you improve your performance in the next tasks you need to do.

## External links

* Refactoring [web](https://www.refactoring.com/) and [book](https://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) by Martin Fowler.


## Related posts

* [What is refactoring]({{< relref "/notes/2020-04-11-refactoring.md" >}}).
* [Flocking rules]({{< relref "/notes/2020-04-05-flocking-rules.md" >}}).
