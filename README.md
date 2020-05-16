# myfirstasp
## 环境
* centos  
* .net3.1
## 环境搭建
[centos搭建.net环境](https://www.cnblogs.com/navysummer/p/12889472.html)
## 运行项目
>1.下载本项目
```
git clone https://github.com/navysummer/myfirstasp.git
```
>2.上传至服务器里  
>3.进入这个项目里，执行以下命令
```
dotnet restore
```
>4.构建项目,其中/app是构建后的目录
```
cd aspnetapp
dotnet publish -c release -o /app --no-restore
```
>5.运行项目
```
dotnet aspnetapp.dll
```