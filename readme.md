

## JavaAppExtract

！！！注意：2026年1月15日发现需要修改源码：如下，新的请求不存在referer请求头了，否则无法正常使用，目前未同步更新
    .url("https://mvnrepository.com/artifact/com.alibaba/fastjson/1.2.47")
    .header("accept", "text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7")
    .header("accept-language", "zh-CN,zh;q=0.9,en;q=0.8,en-GB;q=0.7,en-US;q=0.6")
    .header("cache-control", "max-age=0")
    .header("priority", "u=0, i")
    .header("sec-ch-ua", "\"Microsoft Edge\";v=\"143\", \"Chromium\";v=\"143\", \"Not A(Brand\";v=\"24\"")
    .header("sec-ch-ua-arch", "\"x86\"")
    .header("sec-ch-ua-bitness", "\"64\"")
    .header("sec-ch-ua-full-version", "\"143.0.3650.139\"")
    .header("sec-ch-ua-full-version-list", "\"Microsoft Edge\";v=\"143.0.3650.139\", \"Chromium\";v=\"143.0.7499.193\", \"Not A(Brand\";v=\"24.0.0.0\"")
    .header("sec-ch-ua-mobile", "?0")
    .header("sec-ch-ua-model", "\"\"")
    .header("sec-ch-ua-platform", "\"Windows\"")
    .header("sec-ch-ua-platform-version", "\"19.0.0\"")
    .header("sec-fetch-dest", "document")
    .header("sec-fetch-mode", "navigate")
    .header("sec-fetch-site", "none")
    .header("sec-fetch-user", "?1")
    .header("upgrade-insecure-requests", "1")
    .header("user-agent", "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/143.0.0.0 Safari/537.36 Edg/143.0.0.0")
    .header("cookie", "_ga=GA1.1.1207561839.1762217761; _gcl_au=1.1.803291174.1762217761; _sharedID=33485772-196f-4b1f-a849-f90357aecbb6; _sharedID_cst=zix7LPQsHA%3D%3D; _cc_id=bab0c47b17ff641863383bf5e7837fb7; 33acrossIdTp=wTB4mxeJlGFsoOorBdG4eFbdGuVYVpYy%2FL%2FdXLgLE6c%3D; cto_bundle=qMcwyl9rcjZPTXd2VzFtdiUyQnRleUZVRTJBQXJBNldRNXE5d0tnWjZyUXU3cyUyQmpibjFZc1N3WEpib3ZmRW56U1dPZkQ5b2gyUHBPUXdmYmMxTFNpS3d6QnR6NThXNVlZVG1vSzIlMkJCQkZyQ3BKRUxrc3FIRldMY3JUdVA1SHNpeFBsVjU0SjlFTzBCNiUyQjA5QWdHYzk5RlJoUiUyRkNRJTNEJTNE; FCCDCF=%5Bnull%2Cnull%2Cnull%2Cnull%2Cnull%2Cnull%2C%5B%5B32%2C%22%5B%5C%22ff0a2efc-cde7-4bc4-ad49-9b248139abfc%5C%22%2C%5B1765446443%2C258000000%5D%5D%22%5D%5D%5D; FCNEC=%5B%5B%22AKsRol8gf_b2kxJU5kLsKdI3gOzITUWkY1FWVPw1r1hm7eKOQpjLHRFr6BCbObmbNm98iuKGlAb7dckPaJmJvPtKl_cAuVqYxoapgP3DFLfJEEd4jX5_gy68IHUzuufA9xbGU1aLrU78bg3zFxP4ddYoBOLiqtJvOg%3D%3D%22%5D%5D; _ga_0ECPK48KPK=GS2.1.s1766034912$o7$g0$t1766034912$j60$l0$h0; cf_chl_rc_ni=8; cf_clearance=8pT38fLyqVIQ43NHDcmnhumeWfPnapQ.QEGt9D9fIiY-1768451172-1.2.1.1-64C0UupH0ZE8qK4ubKIOr.VFruX0aXlYTefGVho9trOWQVXFLxTI7TdF4BLmpvp_al4R4_vkELc33JH69ujDghGEr6CxoJhTPfPJw2Wv4.5vD4gZYlS5V71jhulww36LljBTYPCwS057h1m4N.P1oP5bvuTVPR4dcfxnEmQWcdn1cEbEbgloT1Qde6vBaVU_.zgW9TcXy_TQIKu66k1ioKxGUzKtlZSGXJOyVfZ7VnmmlbJ2WF2sMgLq2L08De1I; __gads=ID=c82e342f55d66341:T=1762217790:RT=1768451172:S=ALNI_MYxzwiUxsB9tyoe29RIALzJOqANqA; __gpi=UID=000011ad5bf469d5:T=1762217790:RT=1768451172:S=ALNI_MYJUGHD7FuMFvlshnazHB1E81sKQg; __eoi=ID=8ba371b32dbcfb67:T=1762217790:RT=1768451172:S=AA-AfjZR38HgVOlgJcCV9zmnbYKZ; AWSALB=XN6INGxD1/plMeieQDX/ktn6c84RgoyrvNPwhvCM5uXGgQ2GRzOdTh3C4A6L1Zjyw5UGo+PZ1LXwTbfRbLxOmIhfIXqHcf+WoU12Xo6OKk4t/Z27WUcKYNsRcQ2F; AWSALBCORS=XN6INGxD1/plMeieQDX/ktn6c84RgoyrvNPwhvCM5uXGgQ2GRzOdTh3C4A6L1Zjyw5UGo+PZ1LXwTbfRbLxOmIhfIXqHcf+WoU12Xo6OKk4t/Z27WUcKYNsRcQ2F; MVN_SESSION=eyJhbGciOiJIUzI1NiJ9.eyJkYXRhIjp7InVpZCI6IjAxOWE0YzUwLWFmNWYtNzRhMy05NmViLTUyNjA0NDMwMzI1YiJ9LCJleHAiOjE3OTk5ODcxNzUsIm5iZiI6MTc2ODQ1MTE3NSwiaWF0IjoxNzY4NDUxMTc1fQ.BHlILSklIaie5vLw0sP9G7S-SJ1Z6hKgifIE9KEKPkE; _ga_3WZHLSR928=GS2.1.s1768451165$o30$g1$t1768451169$j56$l0$h0")
    .build();

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

