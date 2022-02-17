# 短链接生成服务

## 基于spring boot + H2 数据库 + Vue

## Demo http://42.193.127.130:8090/

### 部署方式一

> 下载jar包 直接启动 默认端口 8090

```shell
java -jar -Xms128m -Xmx512m -XX:PermSize=128M -XX:MaxPermSize=256M  short-url-1.0.0.jar

```

### 部署方式二

> 使用docker方式部署  

```shell
docker run -d -p 8090:8090 --name short-url --restart=always wxyshine/short-url:latest
```