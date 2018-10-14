---
title: Debug the unknown with git bisect
date: 2015-12-02 21:55:06 +08:00
categories:
- Git
- Coding
- Debugging
layout: post
comments: true
---

Many of you might have been facing the problem where the few latest commits break your existing features (Y NO TESTING?).

There's a handful feature in git, [`git-bisect`](https://git-scm.com/docs/git-bisect) which could help you to quickly debug what went wrong within the good (working) and bad (broken) commits.
