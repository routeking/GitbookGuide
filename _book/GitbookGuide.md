# GitBook指导手册

## GitBook环境准备

首先安装note.js，下载地址：<https://nodejs.org/en/download/>
找到对应的版本下载安装即可

现在安装 Node.js 都会默认安装 npm（node 包管理工具），所以我们不用单独安装 npm，打开命令行，执行以下命令安装 gitbook-cli：

> npm install -g gitbook-cli

安装完之后，就会多了一个 gitbook 命令（如果没有，请确认上面的命令是否加了 -g）。如果觉得gitbook-cli不方便使用，则可以安装官方的Gitbook工具进行书籍管理。

安装完成之后就可以开始使用了，但是为了方便实用，建议再安装以下软件：
> 文本编辑 Typora 下载地址：https://typora.io/  
> 版本管理 Git 下载地址：https://git-scm.com/downloads
> 官方工具 GitBook 下载地址：

## GitBook CLI常用命令

* 常用命令汇总

``` C
gitbook init    // 初始化目录文件
gitbook help    // 列出gitbook所有的命令
gitbook --help  // 输出gitbook-cli的帮助信息
gitbook build   // 生成静态网页
gitbook build --gitbook=2.0.1 // 生成时指定gitbook的版本, 本地没有会先下载
gitbook serve   // 生成静态网页并运行服务器
gitbook ls      // 列出本地所有的gitbook版本
gitbook ls-remote // 列出远程可用的gitbook版本
gitbook fetch 标签/版本号 // 安装对应的gitbook版本
gitbook update  // 更新到gitbook的最新版本
gitbook uninstall 2.0.1     // 卸载对应的gitbook版本
gitbook build --log=debug   // 指定log的级别
gitbook build --debug       // 输出错误信息
gitbook build --log=debug --debug   // 同时输出log和错误信息
```

## GitBook目录结构及说明

## GitBook配置

## GitBook插件

### 添加插件

### 删除插件

### 常用插件介绍

## 生成电子书

## 常见问题