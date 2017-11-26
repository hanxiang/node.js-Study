# Node.js
> 有关Node.js有关的javascript包

## 基础

* [前后端分离实践（一)](https://segmentfault.com/a/1190000009329474?_ea=2038402)
* [实现前后端分离的心得](http://blog.jobbole.com/111624/)
* [基于前后端分离的身份认证方式——JWT](http://blog.csdn.net/riddle1981/article/details/76736518)
* [前端工程化开发方案app-proto](https://zhuanlan.zhihu.com/p/24866514)

## [PM2](http://pm2.keymetrics.io/)

> pm2 是一个带有负载均衡功能的Node应用的进程管理器.

![](/static/images/pm2-logo.jpg)

* [中文文档](https://doc.webpack-china.org/concepts/)
* [使用高大上的pm2代替forever部署nodejs项目](http://www.jianshu.com/p/fdc12d82b661)
* [PM2使用介绍](https://segmentfault.com/a/1190000002539204)
* [PM2实用入门指南](https://www.cnblogs.com/chyingp/p/pm2-documentation.html)

## [npm-check](https://github.com/dylang/npm-check)

> 是一个npm包更新工具。它还可以检查项目的npm依赖包是否有更新，缺失，错误以及未使用等情况。

* [npm模块管理进阶 — npm-check + cnpm 构建完美的包更新环境](https://segmentfault.com/a/1190000011085967)
* [在中国，安装 & 升级 npm 依赖的正确方法](https://cnodejs.org/topic/581d96d5bb9452c9052e7b58)

```text
    -u, --update       显示一个交互式UI，用于选择要更新的模块，并自动更新"package.json"内包版本号信息
    -g, --global       检查全局下的包
    -s, --skip-unused  忽略对未使用包的更新检查
    -p, --production   忽略对"devDependencies"下的包的检查
    -d, --dev-only     忽略对"dependencies"下的包的检查
    -i, --ignore       忽略对指定包的检查.
    -E, --save-exact   将确切的包版本存至"package.json"(注意，此命令将存储'x.y.z'而不是'^x.y.z')
```

忽略对未使用包的更新检查

```sh
    npm-check -s
```

忽略对未使用包的更新

```sh
    npm-check -s -u
```

检测的屏幕截图

* 检测结果

![](/static/images/screen/QQ20171124-114924@2x.png)

* 更新选择提示

![](/static/images/screen/QQ20171124-115402@2x.png)

* 更新结束

![](/static/images/screen/QQ20171124-120212@2x.png)