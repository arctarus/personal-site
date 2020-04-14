---
title: How to Refactor
description: Follow the Open/Close principle
date: 2020-04-14T23:01:39+02:00
tags:
- refactoring
- code smells
- flocking rules
- solid
---
When you have to add a new requirement to an existing code, first you should check if the code is open to the new change. Open means that the code is following the SOLID principle *open for extension and closed for modification*.

If the code isn't open yet, you should first refactor it to make it open, and once done you can add the new code.

To refactor to make it open, you should be guided by the code smells. Identify the code smells in the code and remove them using the refactoring recipes. Remember always fix the easier problem first.

To do the refactoring you should always rely on the test, so you can be sure you never introduce a bug in the code. Do just one change at a time, and refactor always under green.

If you are not able to identify the abstractions that will make your code open, you should use the [flocking rules]({{< relref "/notes/2020-04-05-flocking-rules.md" >}}) to iteratively identify and extract them.

Once identified the new abstraction you should name it, so the code can be easily understood. The rule here is that the name of a thing should be one level of abstraction higher than the thing itself.

When you remove all the code smells in your code, it should be open to the new requirement, so will be time to add the new code.

## External links

* [99 Bottles of OOP book by Sandi Metz & Katrina Owen](https://www.sandimetz.com/99bottles).
* Refactoring [web](https://www.refactoring.com/) and [book](https://www.amazon.com/Refactoring-Improving-Design-Existing-Code/dp/0201485672) by Martin Fowler.

## Related notes
* [What is refactoring]({{< relref "/notes/2020-04-11-refactoring.md" >}}).
* [When to refactor]({{< relref "/notes/2020-04-12-when-to-refactor.md" >}}).
* [Flocking rules]({{< relref "/notes/2020-04-05-flocking-rules.md" >}}).
