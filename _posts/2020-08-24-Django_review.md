---
layout: post
title:  "Django - Introduction"
date:   2020-08-24 
categories: Python3  Django 
---
### Django  Description：
   python 的一种流行、开源的大型网站开框架，2005年发布带有强大的后台管理 。


---

<h3> 创建项目指令


```python
django-admin startproject mydjango.   # 命令行创建第一个项目
```

<h4> 一、Django项目目录结构</h4>

1. <span style='color:red' >manager.py  </span>
   功能：包含项目管理的子命令

   如：启动服务：runserver

   ​	   创建应用：s tartapp

   ​		数据迁移：migrate

2. <span style='color:red' >__init__.py  </span>
   项目初始化文件，服务器启动自动运行

3. <span style='color:red' >wsgi.py </span>
   WEB服务网关配置接口的配置文件，部署项目时使用

4. <span style='color:red' >urls.py </span>
   项目的基础路由配置文件，所有的动态路径必须先走该文件进行匹配。

5. <span style='color:red' >settings.py </span>

功能：项目的配置文件，启动项目的时自动调用

   

