---
title: Some convenient setup for git
date: 2021-11-22 19:02:25
tags: git
---

Some useful alias setup for git commands
```shell
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.st status
```

Also, you could edit the config directly.
```shell
$ vim ~/.gitconfig
```
```text
[alias]
    co = checkout
    br = branch
    st = status
    l = log --oneline --graph
    ls = log --graph --pretty=format:"%h <%an> %ar %s"
```
