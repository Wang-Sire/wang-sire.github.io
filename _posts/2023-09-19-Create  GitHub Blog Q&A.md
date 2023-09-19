---
layout: post
title:  " 2023 - 09 - 19 创建Github Q&A  Case Image "
date:   2023-09-19 
categories: 思考我自己  十年后的我 
tags:
    - GitHub Blog
    - Blog Image
---
### Project  Description：
	创建自己的github blog ,这个事最早要从2019年说起，等哪天有空了我写个随笔记上去，现在在公司Working 中；今天主要登记的问题是：
		Github Blog 不能加载 图片
		1. 自己的图片在本地如何加载到Blog 中？
		2. Upload self github Project ，如何正常加载成功？
---

---
### Question 1 自己的图片在本地如何加载到Blog 中？
		当看到第二个问题也就大概懂了第一个问题，加载图片需要加载的一定是github能访问到的地址，如果是本地的内网一定是不行了，需要上传到自己项目的github的图片存放的目录的位置，然后打开看链接地址使用。
		借用一个大神的Blog :https://blog.51cto.com/lexsaints/5094325
		如果借用成功，直接能使用那就不用浪费看第二步骤了，我就是因为怎么也不行惭愧 ，所以有了下面一步

### Question 2 Upload self github Project ，如何正常加载成功？
		当图片也存好了，也上传到了咱们的目录下，打开blog后依然失败 例如页面如下提示：
---
![error_img](https://github.com/Wang-Sire/wang-sire.github.io/raw/master/img/img_Error_2023-09-19_13.32.45.png)

---
###  控制台问题：
		控制台提示：
		可能是黄色⚠️ 或者 红色 提示 Cross跨域问题，就是本该在一个img信息插入了一个Html调用就会出现
		这种情况我吧 我本来的blob 修改为 raw 就解决了
---
![error_img](https://github.com/Wang-Sire/wang-sire.github.io/raw/master/img/cross_question_023-09-19_13.55.49.png)




