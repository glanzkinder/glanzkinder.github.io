---
layout: post
title: "SaltStack: 'Unsupported URL protocol' exception"
description: ""
category: 
tags: []
---
{% include JB/setup %}

If you should ever come across 

	Exception 'Unsupported URL protocol' caught while fetching gitfs remote ssh:git@mgithub.com/username/repository.git

 errors in your log file please check twice if your libgit2 is linked to libssh2...