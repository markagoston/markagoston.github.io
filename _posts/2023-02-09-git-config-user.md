---
layout: post
title: Configure git username and email
date: 2023-02-0 8:05:00
categories: [git]
tags: [git,github,config]
---

## How to set git username and email 
<pre>

</pre>


![Git](/assets/img/git-github.png "Git")
<pre>

</pre>
### From command line

*This command will change the username and email globally*

```bash
git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"
```
---
### To change the username and email only for the current repository change into the *current repo directory* and use the following commands:


```bash
git config user.name "FIRST_NAME LAST_NAME"
git config user.email "MY_NAME@example.com"
```

After these commands your `.git/config` file should have these lines

```bash
[user]
	name = FIRST_NAME LAST_NAME
	email = MY_NAME@example.com
```
