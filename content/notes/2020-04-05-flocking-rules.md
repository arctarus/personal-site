---
title: "Flocking rules"
date: 2020-04-05T23:16:08+02:00
description: A set of rules to refactor code
categories: [programming]
tags: [refactoring, testing]
---

The flocking rules are an small set of rules for refactoring code. The idea is make small incremental changes that
allows you obtein precise error messages when something goes wrong, so if you find and error, you can revert it and make
a smaller one. The steps are the following:

1. Select the things that are most alike.
2. Find the smallest difference between them.
3. Make the simplest change that will remove that difference.

## External links

* This concept was originally found at the book [99 Bottles of OOP by Sandi Metz & Katrina Owen](https://www.sandimetz.com/99bottles)

## Related notes

* [Build less]({{< relref "/notes/2011-06-03-build-less.md" >}}): Why you should use flocking rules to simplify your code?
