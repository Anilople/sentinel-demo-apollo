# sentinel-demo-apollo

演示应用使用Apollo作为Sentinel数据源

## 构建

```bash
mvn clean package -DskipTests
```

在target路径下会产生文件`xxx.zip`

将.zip文件放到linux上解压

## 修改配置

.zip文件解压后

有文件`config/application.properties`

可以修改里面的配置，例如更换apollo.meta的地址等

## 启动

```bash
sh scripts/startup.sh
```

## 查看日志

在console.log文件中

## 停止

```bash
sh scripts/shutdown.sh
```