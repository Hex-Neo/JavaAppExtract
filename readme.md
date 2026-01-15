

## JavaAppExtract


[TOC]

### 基础介绍：

用来扫描java项目中开源组件是否存在漏洞，注意：使用本工具需要联网

通过https://mvnrepository.com/站点获取组件是否存在漏洞

大版本更新2.0，添加数据库进行本地缓存
大版本更新3.0，支持解析pom，并且可以输出excel报告

<img width="1482" height="419" alt="微信图片_20251216175606_19_15" src="https://github.com/user-attachments/assets/701be2b3-c5c5-419f-ba21-26b7e7f0d41b" />

<img width="1166" height="637" alt="屏幕截图 2025-12-17 110611" src="https://github.com/user-attachments/assets/9e38cf00-ad29-42dd-8cfd-68b0f7e3b04a" />

### 使用方法：

java -jar xxx.jar查看参数

根据提示指定项目的lib目录即可

<img src="img/1.png" style="zoom: 50%;" >

下图中 1 1 1 2 2，代表获取组件版本时，是在数据库进行读取，1是存在漏洞，2是不存在漏洞，0是本地数据库不存在该组件，并且加载缓存到本地数据库

<img src="img/2.png" style="zoom: 50%;" >

当前提供数据库内存在1000条组件版本信息

<img width="1022" height="676" alt="屏幕截图 2025-12-17 105704" src="https://github.com/user-attachments/assets/4dba6e35-2da9-4fd9-af0b-da7ef2fa1c29" />


### 下载建议：

编译环境：jdk8u471

最小化工具，数据库中不存在任何数据：JavaAppExtract-2.0-Minimum.7z

标准工具，数据库中存在1000条数据：JavaAppExtract-2.0-Standard.7z


源码：src.zip


