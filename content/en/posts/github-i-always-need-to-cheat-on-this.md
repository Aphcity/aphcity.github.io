---
title: "GitHub: I always need to cheat on this"
description: ""
summary: Stop searching, surfing and so on... Come back check what have u did before.
date: 2025-02-07T03:26:54.542Z
lastmod: 2025-02-07T04:28:57.147Z
featureimage: ""
draft: false
tags: []
categories: []
showTableOfContents: false
layout: ""
---

# Setup Git

I should know how to do apt, after apt, we need to set up the global config.

``` bash
git config --global user.name "<yourusername>"  
git config --global user.email "<youremail>"
```

# Rebase? Merge?

Basically, `Merge` and `Rebase` both give us a way to pull the published commits to local branch and keep local commits not lost. But they used different logic to make this happen, even they could come to a same endpoint.

In short, if we have unpublished local commits or changes, it prefers to use `Rebase` since it is friendly for both local repository and remote one. But if there are published commits in our branch, we should better merge or simply continue work on the existing one, and then create a PR to `Merge` into main branch. Only this way can keep the repository code clean and history readible. And under this circumstance, if we rebase the code, we might created multiple duplicated commits for those published commits, and that will lead to a chaotic commit history.