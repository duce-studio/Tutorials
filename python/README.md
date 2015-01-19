# Python简明实践教程

主要是Python语言的基本介绍, 一些好用的类库介绍和简单的示例.

水平有限, 难免有错漏, 欢迎指正. 谢谢!

目录

## 1. 基本语法介绍

着重介绍语法中与其他语言不同的部分, 其他部分简单介绍, 不包含所有的语法, 但是基本涵盖所有常用的语法.

## 2. 高级语法介绍

包含list comprehension(列表推导式), dict comprehension(字典推导式), with-statement, 运算符重载等方面.

## 3. 常用的类库介绍

目前暂定
开发辅助: pip, virtualenv
web框架: web.py(简单的web框架), tornado(异步web框架), 
数据库相关: sqlalchemy(ORM), pymongo(MongoDB驱动), 
其他: requests(http请求), BeautifulSoup(html的解析), Schedule(周期调度), gunicorn(wsgi部署), supervisord(进程控制), ipython, chardet(编码检测), paramiko(ssh实现), nosetests(单测框架), coverage.py(覆盖率收集)

额外一些自己写的或者从库里抽取的部分简单好用的代码

## 4. 小项目实战

互相有点关联的一个实战
a. 写一个简单的web页面, 几个表单功能, 提供一些页面展示
b. 使用pymongo作为后端存储和sqlalchemy(sqlite)作为后端存储(两种方式)
c. 进行网页爬取
d. 改造, 使用pip, supervisord和gunicorn来部署web
