docker-compose构建nginx负载均衡
========================
docker-compose一键构建nginx负载均衡

## 运行
```bash
git clone https://github.com/docker-box/nginx-cluster.git
cd nginx-cluster
docker-compose up
```

## 访问测试
```bash
http://localhost:2200
```
可以尝试多刷新几次看看结果

## 相关命令

#### 查看docker-compose运行日志
```
docker-compose logs
```

#### 查看运行的docker容器
```
docker-compose ps
```

#### 进入容器

```
docker exec -it nginx-cluster1 sh
```

```
docker exec -it nginx-cluster2 sh
```
