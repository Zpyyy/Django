# Day1 Django入门
## 1、搭建环境：
Python 3.7
Django 3.1.5
搭建环境变量
## 2、创建工作空间
## 3、分析项目目录结构
  * Tester：工程总目录
    * Template：存放html文件 所有前端页面信息都放在template目录下
    * Tester:项目录包
      * Settings:存放配置信息之类，指定数据库等等。服务器一启动就会加载该文件信息
      * Urls:根路由文件 配置页面跳转
      * Wsgi:网关接口，内置服务器走的一个标准（能够在服务器内找到该应用程序，无需配置）
    * Manager.py:关键主程序 django内置服务器，启动服务器需要执行manager的程序才可以启动
    * db.sqlite3: 默认的脚本文件数据库


   * pps:127.0.0.1:8000:8000为django内置服务器默认端口

## 4、启动服务器
 1. 在终端中执行python manage.py. runserver 127.0.0.1 如图则启动成功 
		默认服务器地址是127.0.0.1 可在django工程目录下Edit Configurations进行修改 

 2. 直接start 运行该工程

