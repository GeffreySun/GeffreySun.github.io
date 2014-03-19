---
layout: post
title:  (Node)Use npm in China.
---

## {{ page.title }}

### 1.BackGroud
As you know, the GFW  is very unconfortable for our engineers in china. When I want to use 'npm install', it ofthe gets stuck.

### 2.Solution
There are some useful  npm's mirrors in china, such as ' http://registry.cnpmjs.org'. so we can use them,
	 the syntax is :
	    Once Use:
			npm --registry http://registry.cnpmjs.org  install
		Forever:
			modify or create '~/.npmrc' , and then add a new line 'registry = http://registry.cnpmjs.org '

### 3.Issue
If you get some errors about cache ,you can try the command 'npm cache clean'.