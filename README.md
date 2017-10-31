# Node Alpine Docker

[![Docker Stars](https://img.shields.io/docker/stars/wolfdeng/node.svg)](https://hub.docker.com/r/wolfdeng/node/)
[![Docker Pulls](https://img.shields.io/docker/pulls/wolfdeng/node.svg)](https://hub.docker.com/r/wolfdeng/node/)
[![Image Size](https://img.shields.io/imagelayers/image-size/wolfdeng/node/latest.svg)](https://imagelayers.io/?images=wolfdeng/node:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/wolfdeng/node/latest.svg)](https://imagelayers.io/?images=wolfdeng/node:latest)

基于Alpine系统的Node镜像。

## 使用说明

### 获取镜像
```bash
docker pull wolfdeng/node
```

### 启动容器
```bash
docker run --name node -it -d wolfdeng/node
```

### 使用容器内容的jdk
```bash
docker exec -it node node -version
```
