---
title: "The best code you can write"
description: "Resist being clever"
date: 2020-05-03 23:22:09.776 +0200
tags:
- simplicity
---

Code is read many more times than it is written, and its ultimate cost is often very high and paid by someone else.

While it’s difficult to get exact figures for value and cost, asking the following questions will give you insight into the potential expense of a bit of code:

1. How difficult was it to write?
2. How hard is it to understand?
3. How expensive will it be to change?

## When is the code easy to understand?

Code is easy to understand when it clearly reflects the problem it’s solving, and thus openly exposes that problem’s domain.

Programmers love clever code. You must resist being clever for its own sake. If you are capable of conceiving and implementing a complex solution, you should accept the harder task and write simpler code.

## How can we do code easy to understand

### Consistency

Inconsistent styling makes code harder for humans to parse, it raises costs without providing benefits.

### Duplication

Duplication of logic suggests that there are concepts hidden in the code that are not yet visible because they haven’t been isolated and named. When you remove duplication of your code, you do it more DRY, and to do it you need to introduce some abstractions.

### Naming

Concepts in the code should be extracted and named. You should name methods not after what they do, but after what they mean, what they represent in the context of your domain. Naming the method at this slightly higher level of abstraction isolates the code from changes in the implementation details.

## External links
* This concept was originally found at the book [99 Bottles of OOP by Sandi Metz & Katrina Owen](https://www.sandimetz.com/99bottles).

## Related notes
* [Build less]({{< relref "/notes/2011-06-03-build-less.md" >}}).
* [What is refactoring]({{< relref "/notes/2020-04-11-refactoring.md" >}}).
* [DRY]({{< relref "/notes/2020-04-23-dry.md" >}}).
