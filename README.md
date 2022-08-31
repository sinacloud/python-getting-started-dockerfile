# Dockerfile创建Python应用示例

## 本地运行

```sh
$ git clone https://github.com/sinacloud/python-getting-started-dockerfile.git
$ cd python-getting-started-dockerfile
$ python main.py
```

现在，本示例应用已经跑在了你的 localhost:5050 端口上了。

## 部署到sinacloud

首先，提交代码到你的sinacloud应用的git仓库。

登陆sinacloud容器云的管理页面，在运行环境管理-代码管理-如何部署查看部署代码方式。

部署完成之后，你就可以通过 http://$APPNAME.saelinzi.com 来访问你的应用了。
```
如果您的应用显示未激活，您需要设置host才能访问，设置方法参见应用的管理页面
```


## 相关文档

- [Python应用部署指南](http://www.sinacloud.com/doc/sae/docker/python-getting-started.html)