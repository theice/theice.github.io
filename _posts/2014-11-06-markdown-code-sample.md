---
layout: post
categories: [article]
title: "Markdown常用语法"
tags: [Markdown, 日志]
---

### 说明
网上有很多例子和说明，官方文档也写的比较清楚，以下只是自己亲手写一下熟悉语法，另外用到时拷贝方便。
参考：

[Markdown官网](http://daringfireball.net/projects/markdown/)

[Markdown中文语法说明](http://wowubuntu.com/markdown/)

---

#### 1. 一级标题

一级标题
========
	一级标题
	========

#### 2. 二级标题

二级标题
--------
	二级标题
	--------

#### 3. H1...H6

# H1

## H2

### H3

#### H4

##### H5

###### H6

	# H1
	## H2
	### H3
	#### H4
	##### H5
	###### H6
	
#### 4. 加粗

**加粗**

	**加粗**
	__加粗__

#### 5. 斜体

*斜体*

	*斜体*
	_斜体_


#### 6. 列表

1. one
2. second
3. third

---
	1. one
	2. second
	3. third

* tom
* jack
* lily

---
	* tom
	* jack
	* lily
	
#### 7. 链接

[Github](https://github.com/)

	[Github](https://github.com/)

#### 8. 图片

<img src="/img/sample1.jpg" alt="汽车" title="名车" width="100%">

	行内语法
    ![alt text](/path/to/img.jpg "Title")
	或者参考式语法
    ![alt text][id]
    [id]: /path/to/img.jpg "Title"
	
	限制：无法指定宽高
