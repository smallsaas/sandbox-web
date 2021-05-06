## sandbox-web
> 通过代码直接构建

#### 克隆部署仓库
```
git clone --depth 1 https://github.com/smallsaas/sandbox-web.git --single-branch web
```

#### 构建并运行
> 进入 `app` 目录, 基于源代码进行构建
```
cd app
docker-compose up --build --detach
```

#### 访问
> 端口默认设置为 `8000`
>
获取容器服务器的IP，如本机执行，在浏览器中输入地址 `http://localhost:8000`

#### 变更端口
替换 `docker-compose.yml` 里定义默认 `8000` 端口即可
