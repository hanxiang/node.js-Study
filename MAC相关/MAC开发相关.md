# MAC开发相关
> MAC下开发相关的资料或说明

## 在Mac OS X启动和停止MySQL服务的命令

> 摘要：在Mac OS X启动和停止MySQL服务的命令

启动MySQL服务

```sh
sudo /usr/local/mysql/support-files/mysql.server start
```

停止MySQL服务

```sh
sudo /usr/local/mysql/support-files/mysql.server stop
```

重启MySQL服务

```sh
sudo /usr/local/mysql/support-files/mysql.server restart
```

## mac 如何显示隐藏文件和.点开头文件？

隐藏文件和.开头文件（比如.Trash，.DS_Store），在Unix系统下都被认作是隐藏文件。
快速的查看，可以使用系统带的--- 终端----程序，在命令行定位到想要查看的目录（cd && ls）
然后在目录下  ls  -la   就能看到所有隐藏文件了，如果想进一步如copy,mv等操作，网上搜索命令行工具就可以了。
如果想在Finder中就能直观看到隐藏文件，那么在终端中输入以下下命令：

```sh
    defaults write com.apple.Finder AppleShowAllFiles YES
    killall Finder
```

要关闭显示隐藏文件的话就把上面的命令中YES改为NO就行了
