### 高仿bilibili视频网站项目实例
包含论坛， 购物商城  网页  后台管理的java项目集成
(论坛/购物/网页/后台)

### 运行步骤：
1.建立数据库，导入sql文件
2.更改数据源db.properties设置
3.启动Tomcat
4.浏览器访问：http://localhost:8080/bilibili
PS:
项目流程:
下载数据库备份并导入数据库
下载static静态文件放到webapp下面(注: static这个文件一定要放在webapp下面 这样项目才可以访问)
视频可下载可不下载,如果下载了放到 webapp/static/videolook 这个目录下面
