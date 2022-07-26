# 商场管理系统

## 要求

使用pip下载：`pip install`

1. Django >= 2.2.12
2. django-apscheduler
3. mysqlclient

## 运行

在mysql中创建一个数据库mall（名字自己随便取，后面改就是）：`create database mall DEFAULT CHARACTER SET utf8;`

cd 项目根目录，

1. 首先修改数据库信息，在/shoppingmall/settings.py中，修改数据库的名称和密码：

   ![](static/img/database.png)

2. 生成迁移文件：`python manage.py makemigrations`

3. 执行迁移脚本：`python manage.py migrate`。如果结果如下，那么就没有问题。

   ![](https://cloud.fullcomb.top/private/source/image/python/django_note/image-20220428162336508.png)

4. 启动项目：`python manage.py runserver`，也可以自定义allowed hosts和port。

## 展示

### 数据库设计

![](static/img/design.png)

### 页面

![](static/img/1.png)

![](static/img/2.png)

![](static/img/3.png)

