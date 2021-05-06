## sandbox-web


#### 克隆部署仓库
```
git clone --depth 1 https://github.com/smallsaas/sandbox-web.git --single-branch web
```

#### 准备 dist
把构建好的dist放至 `web` 目录下 (替换原dist/)
```
$ ls web
dist/
docker-compose.yml
```

#### 构建并运行
```
docker-compose up --build --detach
```

#### 访问
> 端口默认设置为 `8000`
>
获取容器服务器的IP，如本机执行，在浏览器中输入地址 `http://localhost:8000`

#### 变更端口
替换docker-compose.yml里定义默认`8000`端口即可


#### 一键运行
```
curl -OL https://raw.githubusercontent.com/smallsaas/sandbox/master/tag/web/docker-run.sh | bash -
```
