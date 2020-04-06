---
title: "Flocking rules"
date: 2020-04-05T23:16:08+02:00
description: A set of rules to refactor code
categories: [programming]
tags: [refactoring, oop, testing]
---

1. Select the things that are most alike.
2. Find the smallest difference between them.
3. Make the simplest change that will remove that difference.

Changes to code can be subdivided into four distinct steps:
1. parse the new code
2. parse and execute it
3. parse, execute and use its result
4. delete unused code

Making small changes means you get very precise error messages when something goes wrong, so it’s useful to know how to work at this level of granularity. As you gain experience, you’ll begin to take larger steps, but if you take a big step and encounter an error, you should revert the change and make a smaller one.

## References:

* [99 Bottles of OOP - Sandi Metz & Katrina Owen](https://www.sandimetz.com/99bottles)
