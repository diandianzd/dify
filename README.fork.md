# fork仓库修改说明


## 本地构建镜像

api 构建
```
docker build . -t dify-api:1.3.2 -f ./Dockerfile.fork
```
web 构建

docker build . -t dify-web:1.3.2 -f ./Dockerfile.fork
docker tag dify-web:1.3.2 g-wizl0946-docker.pkg.coding.net/ai/docker/dify-web:1.3.2


## 启动文件

docker/docker-compose.fork.yaml