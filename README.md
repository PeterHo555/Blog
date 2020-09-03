## Blog

#### 前端

* Vue(Vuex+Vue router)
* Element-UI

#### 后端

* Springboot
* Mybatis
* Spring security
* JWT
* Redis
* RabbitMQ
* Swagger-UI

#### 项目目录

* blog-springboot              后端工程 [后端文档](blog-springboot/README.md)
* blog-vue                           前端工程 [前端文档](blog-vue/README.md)
* img                                    文档相关图片
* other                                 其他文档
  * prototype.md		   原型文档
  * 踩坑整理.docx           写本项目遇到的坑
  * 博客缓存.png            redis博客缓存说明
  * 后端功能说明.png     后端功能说明
* conf                                   已配置的项目压缩文件
  * nginx.conf                 nginx配置文件，已配置好
* blog.sql                             mysql数据库结构

#### 预览

* 主页![主页](img/index_demo.png)
* 博客 ![博客](img/blog_demo.png)
* 后台 ![后台](img/admin_demo.png)

#### docker 部署教程
[Docker 部署本站 详细全过程 附代码](https://blog.22xcode.com/post/12)

##### Tips

1. 水平所限，部分代码可能有坑
2. 管理员账号 admin 密码 1

... 

# 

#### 项目启动

* 消息队列 RabbitMQ启动

  >路径：/usr/local/Cellar/rabbitmq/3.8.7/sbin/
  >
  >打开此文件终端：
  >
  >sudo rabbitmq-server
  >
  >浏览器内输入 http://localhost:15672
  >
  >账号：guest
  >
  >密码：guest

* Redis启动

  > 终端：redis-server

* SpringBoot Application 启动

* vue项目启动

  > 终端 ：npm run dev

