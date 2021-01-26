# sandbox-web

### 克隆部署编排仓库 `sandbox-web`
登录服务器[预安装docker环境](https://github.com/kequandian/dev_docs/blob/master/ops/%E5%9F%BA%E4%BA%8ECentOS%E7%B3%BB%E7%BB%9F%E7%9A%84docker%E5%AE%B9%E5%99%A8%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4.md)
```
git clone https://github.com/smallsaas/sandbox-web.git web
```

### 准备 dist
把构建好的dist放至 `web` 目录下 (替换原dist/)
```
$ ls
dist/
docker-compose.yml
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
