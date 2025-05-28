# fork仓库修改说明


## 本地构建镜像

api 构建
```
docker build . -t dify-api:1.4.1 -f ./Dockerfile.fork
docker tag dify-api:1.4.1 g-wizl0946-docker.pkg.coding.net/ai/docker/dify-api:1.4.1
```
web 构建

docker build . -t dify-web:1.4.1 -f ./Dockerfile.fork
docker tag dify-web:1.4.1 g-wizl0946-docker.pkg.coding.net/ai/docker/dify-web:1.4.1


## 启动文件

docker/docker-compose.fork.yaml