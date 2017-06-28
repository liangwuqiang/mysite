http://www.cnblogs.com/feixuelove1009/p/5823135.html

## 2.创建Django项目

采用国际惯例的项目名称mysite

Django自动生成的目录结构：

![](images/1_目录结构.png)

templates目录是html文件存放也就是MTV中的T

manage.py是django项目管理文件

![](images/2_配置文件.png)

## 3.创建APP

python manage.py startapp cmdb

创建了一个叫做cmdb的APP，django自动生成“cmdb”文件夹

## 4.编写路由

![](images/3_路由文件.png)

## 5.编写业务处理逻辑

![](images/4_业务处理逻辑.png)

## 6.运行Web服务

![](images/5_运行Web服务.png)

python manage.py runserver 127.0.0.1:8000

![](images/6_打开网页.png)

## 7.返回HTML文件

![](images/7_1_添加index.png)

![](images/7_2_修改views.png)

>指定HTML目录
![](images/7_3_修改settings.png)
>默认情况下不用修改

## 使用静态文件

![](images/8_1_静态目录.png)
>用于存放CSS,JS和各种插件

![](images/8_2_配置settings.png)

![](images/8_3_index中引入.png)

## 9.接收用户发送的数据

![](images/9_1_index表单.png)

![](images/9_2_修改views.png)

![](images/9_3_设置settings.png)

![](images/9_4_刷新浏览器.png)

## 10. 返回动态页面

![](images/10_1_改造views.png)

![](images/10_2_改造index.png)


---------------------

