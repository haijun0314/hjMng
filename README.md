# hjMng
后台网站管理系统
简介

ssm，即Spring+SpringMVC+MyBatis，也是本平台的核心框架组成，搭建本平台主要做学习研究之用，期望打造成一个通用的IT能力开放平台。
功能说明

    数据库：Druid数据库连接池；
    持久层：MyBatis进行数据持久化;
    MVC:基于spring mvc注解,Rest风格Controller;
    权限：springSecurity进行基于URL的权限控制；
    缓存：Redis进行数据缓存；
    文件流：apache fileupload进行通用的文件上传下载处理；
    日志：集成了Apache Log4j进行日志管理；
    微信：微信公众号基础功能及消息回复功能支持；
    定时任务：基于spring schedule，支持定时任务配置；
    项目构建：maven构建项目，mybatis generator生成mybatis映射文件和Model；
    工具类：常用日期时间处理、通用异常处理机制、Jackson进行json数据处理、redis缓存、参数检查、加密、线程池等；
    前端：前端采用bootstrap+jQuery框架；

项目配置说明

    项目配置：config.properties，主要包含数据库配置、文件上传目录配置和redis服务器配置等；
    日志配置：log4j.properties，进行日志相关参数配置；
    数据初始化：init.sql，创建数据库表及初始数据；
    系统首页：http://localhost:8037/admin/index.jsp，初始登录名密码（admin/111）；
    本系统使用maven进行构建，web服务器默认使用maven plugin tomcat，详情请查看pom.xml文件；

