# web-sandbox

### 克隆
登录具备docker容器环境的服务器, 克隆部署方案
```
git clone https://github.com/smallsaas/web-sandbox.git
```

### 准备 dist
把构建好的dist放至`web-sandbox`目录下 (替换原dist/)
```
$ ls
dist/
docker-compose.yml
README.md
```

#### 运行
> 或后台运行 `docker-compose up -d`
```
docker-compose up
```

#### 访问
> 端口默认设置为 `8000`
>
获取容器服务器的IP，如本机执行，在浏览器中输入地址 `http://127.0.0.1:8000`


#### 变更端口
替换docker-compose.yml里定义默认`8000`端口即可
