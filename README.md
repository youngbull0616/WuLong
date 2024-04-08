<h1 align="center">👋 个人健康管理前后端 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-v1.0-blue.svg?cacheSeconds=2592000" />
</p>
> 开发环境：

| 项目    |  版本 |
|-------|----:|
| Node  |  12 |
| JAVA  | 1.8 |
| MySQL | 8.0 |


> 基于vue+springboot+mysql开发
## 1.结构说明
> sql文件夹：SQL语句存放目录
>
> x-admin-web文件夹：前端源码
>
> x-admin文件夹：后端代码
> 
> WordLists文件夹：爬虫源代码（不影响正常运行，爬虫得到的文件已经整合在SQL语句里了）
>
> 默认配置：前端端口9528，后端端口8080，数据库端口55001，账号root，密码123456，数据库名称db_health
***
## 2.安装说明
### （1）前端启动
在前端vue项目根目录(x-admin-web文件夹)运行下面的指令
```sh
npn install
```
运行下面指令👇启动前端项目
```sh
npn run dev
```
### （2）后端启动

```sh
运行XAdminApplication.java
```

### (3)数据库导入
```sh
运行db_health.sql
```
***
## 作者赠言

喜欢点个小心心⭐️ 有BUG在ISSUE里反馈

***
