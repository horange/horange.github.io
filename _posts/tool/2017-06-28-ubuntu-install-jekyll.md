---
layout: post
title: Ubuntu14.04 安装jekyll
category: tool
tags: jekyll
keywords: 
description: 
---
﻿

* content
{:toc}

# Ubuntu14.04 安装jekyll

标签（空格分隔）： 未分类

---

# 一.安装rvm

RVM的主要作用是方便的管理系统中的多个ruby版本而不至于混乱。
用rvm官方推荐的方式安装`curl -L get.rvm.io | bash -s stable`
```
$ curl -L get.rvm.io | bash -s stable
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   194  100   194    0     0    203      0 --:--:-- --:--:-- --:--:--   202
100 24063  100 24063    0     0  12324      0  0:00:01  0:00:01 --:--:-- 82407
Downloading https://github.com/rvm/rvm/archive/1.29.2.tar.gz
Downloading https://github.com/rvm/rvm/releases/download/1.29.2/1.29.2.tar.gz.asc
Found PGP signature at: 'https://github.com/rvm/rvm/releases/download/1.29.2/1.29.2.tar.gz.asc',
but no GPG software exists to validate it, skipping.
```
```
$ source ~/.rvm/scripts/rvm
```

# 二.以上就安装好rvm了,接着安装ruby
 `rvm install 2.4`

这是安装了ruby2.4,然后配置使用ruby2.4
`rvm use 2.4`

# 三. install jekeyll
`gem install jekyll`







