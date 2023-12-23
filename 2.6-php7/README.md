制作镜像包

```bash
# 进入镜像目录
cd 2.6-php7

# 制作镜像
sudo DOCKER_BUILDKIT=1 docker build . -f ./Dockerfile -t registry.cn-hangzhou.aliyuncs.com/macaiyun0629/composer --no-cache
```
