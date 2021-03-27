# sentinel-demo-apollo

演示应用使用Apollo作为Sentinel数据源

## 构建

```bash
mvn clean package -DskipTests
```

在target路径下会产生文件`xxx.zip`

将.zip文件放到linux上解压

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