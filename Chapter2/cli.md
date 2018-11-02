# 第二章：GitBook CLI常用命令

常用命令有：

``` C
/* 常用操作 */
gitbook init    // 初始化目录文件
gitbook build   // 生成静态网页
gitbook build --log=debug --debug   // 构建过程同时输出log和错误信息
gitbook build --gitbook=X.X.X // 生成时指定gitbook的版本, 本地没有会先下载
gitbook serve   // 生成静态网页并运行服务器

/* 帮助类 */
gitbook help    // 列出gitbook所有的命令
gitbook --help  // 输出gitbook-cli的帮助信息

/* 版本类 */
gitbook ls      // 列出本地所有的gitbook版本
gitbook ls-remote // 列出远程可用的gitbook版本
gitbook fetch 标签/版本号 // 安装对应的gitbook版本
gitbook update  // 更新到gitbook的最新版本
gitbook uninstall 2.0.1     // 卸载对应的gitbook版本
```