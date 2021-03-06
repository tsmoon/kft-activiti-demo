# 简介

本项目旨在让初学者快速入门Activiti。

**作者**：[咖啡兔|http://www.kafeitu.me]

**项目主页**：[http://www.kafeitu.me/activiti/2012/05/26/kft-activiti-demo.html](http://www.kafeitu.me/activiti/2012/05/26/kft-activiti-demo.html)

**在线演示（亚马逊EC2）**：[http://aws.kafeitu.me:8080/kft-activiti-demo](http://aws.kafeitu.me:8080/kft-activiti-demo)

# 框架版本

* Activiti: **5.10**

* Spring: **3.1.1.RELEASE**

* Hibernate: **4.1.4.Final**

# 分支选择

Demo提供Maven版本和no-maven版本，分别适用于会用mavne和不会用maven的同学。

* **maven**分支：对应与git的`master`分支，便于安装和数据库初始化
* **no-maven**分支：直接是一个eclipse工程，包含eclipse的项目配置文件和WEB-INF/lib下面的所有的jar文件

# 演示说明文档

* [配置说明](https://github.com/henryyan/kft-activiti-demo/wiki/%E9%85%8D%E7%BD%AE%E8%AF%B4%E6%98%8E)
* [功能演示](https://github.com/henryyan/kft-activiti-demo/wiki/%E5%8A%9F%E8%83%BD%E6%BC%94%E7%A4%BA)
 
![kft-activiti-demo截图](http://www.kafeitu.me/files/2012/05/kft-activiti-demo.png)

## Changelog

### 1.4.1 (2012-12-01)

1.升级jquery.portlet.js解决把一列的portlet拖走后不能再拖回问题

2.升级:jquery -> 1.83，jquery ui -> 1.9.2, jquery.layout -> 1.3，html头部声明用html标准代替xhtml

### 1.4 (2012-11-27)

1.表单名称重构，portlet添加关于作者和表单概念模块

2.首页用jquery.portlet插件显示信息，并添加一个待办任务列表的portlet