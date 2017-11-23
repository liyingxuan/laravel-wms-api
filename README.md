## laravel-wms-api

Glossary:

后台管理系统是内容管理系统Content Manage System（简称CMS）的一个子集。  
WMS是Web Management System 的简写，简单的说：WMS是一个网站管理系统。  
一个网站管理系统是把一个网站的内容（文字，图片，等等）与网站的组件分离开来，可以将各个页面连接到一起，可以控制页面的显示。  
通过这个系统，可以方便的管理，发布，维护网站的内容，而不再需要硬性的写HTML代码或手工建立每一个页面。


#### 1. Language and framework
PHP >=7.0.0  
Laravel v5.5.*  
[laravel-admin v1.5.x-dev](http://laravel-admin.org/)
Bootstrap v3.3.7  

#### 2. Install and run
[Deploy the server environment](http://www.jianshu.com/p/1f17a69f6dcf)

Reboot server.

Go in project path :
```bash
$ cd [project path]

$ composer install
$ npm install

$ cp .env.example .env
$ php artisna key:generate 
```
After the database can be connected properly, import the database structure and data.  
确保数据库能连接正常之后，导入数据库结构和数据：

./database/sql/laravel-wms-api.sql
  
  

#### 3. Url
API Url : http://[domain]/api/doc/  
WMS Url : http://[domain]/admin/  

Super administrator:  
username: admin  
password: password  

Ordinary administrator:  
WMS-username: manager  
WMS-password: password  
  
  

#### 4. [Quick start](http://laravel-admin.org/docs/#/zh/quick-start)
To be continued.


End.