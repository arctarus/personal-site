---
title: Zero Bug Software Development
date: 2020-04-07T23:31:00+02:00
description: A procedure for dealing with bugs
tags:
- bugs
- agile
- quality
---

Zero Bug Software Development is a policy to archive an state of zero known bugs. The first step to reach this state is label the issues using a very strict classification:

* *Critical issues*: The user is not receiving the value that is supposed to receive. You should stop what you are doing and fix it inmediatelly.
* *Bugs*: The app is not working as expected but the users can receive the value that is supposed to. You should finish what you are doing and then fix it.
* *Features*: New functionality that doesn't exist on the sytem.
* *Improvements*: An enhacement to an existing functionality of the system.

The important thing about this policy is:

* All bugs take priority over all new feature development or improvements.
* If you can live with a bug, it’s not a bug, it’s an improvement and you can prioritize it in the backlog.

Therefore is very important that you classify correctly each issue. Being consistent with the classification system implicitly creates the team quality standards.

## External links
* [Zero bug software development by Sam Hatoum](https://medium.com/qualityfaster/the-zero-bug-policy-b0bd987be684)
* [Hacker news thread about the post](https://news.ycombinator.com/item?id=11659994)

## Related notes
* [What is refactoring]({{< relref "/notes/2020-04-11-refactoring.md" >}}).
* [When to refactor]({{< relref "/notes/2020-04-12-when-to-refactor.md" >}}).
* [Flocking rules]({{< relref "/notes/2020-04-05-flocking-rules.md" >}}).
