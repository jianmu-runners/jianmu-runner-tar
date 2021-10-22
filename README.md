# jianmu-runner-tar

#### 介绍
用tar命令解压缩文件

#### 输入参数
```
JIANMU_CMD: tar压缩解压命令
```

#### 构建docker镜像
```
# 创建docker镜像
docker build -f dockerfilexxx -t jianmudev/jianmu-runner-tar:${version}

# 上传docker镜像
docker push jianmudev/jianmu-runner-tar:${version}
```

#### 用法
```
docker run --rm \
  -e JIANMU_CMD=xxx \
  jianmudev/jianmu-runner-tar:${version}
```
