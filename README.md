# jianmu-runner-tar

#### 介绍
用tar命令解压缩文件

#### 发布到建木Hub

通过建木CI执行[pack_tar.yml](https://gitee.com/jianmu-runners/jianmu-runner-list/blob/master/release_dsl/pack_tar.yml) ，可发布到建木Hub

#### 输入参数
```
cmd: tar压缩解压命令
```

#### 用法
```
docker run --rm alpine:3.13.6 $cmd
```
