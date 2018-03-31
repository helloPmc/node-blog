## Docker构建博客镜像

使用Node.js搭建，Win10系统上构建Docker镜像

### 构建Docker镜像：

```sh
docker build -t yunterry/node-blog:latest .
```

### 镜像部署：

```sh
docker pull yunterry/node-blog

docker run -d -p 5230:3000 yunterry/node-blog
```

浏览器打开 http://192.168.99.100:5230

镜像地址: https://store.docker.com/community/images/yunterry/node-blog
