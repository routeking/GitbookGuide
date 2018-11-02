# 第五章：GitBook插件

记录一些实用的插件, 如果要指定插件的版本可以使用 plugin@0.3.1。下面的插件在 GitBook 的 3.2.3 版本中可以正常工作，因为一些插件可能不会随着 GitBook 版本的升级而升级，即下面的插件可能不适用高版本的 GitBook，所以这里指定了 GitBook 的版本。另外本文记录的插件在 Linux 下都是可以正确工作的，windows 系统没有测试。这里只是列举了一部分插件，如果有其它的需求，可以到[插件官网](https://plugins.gitbook.com/ "gitbook官方插件区")区搜索相关插件。

* Disqus - Disqus 评论
* Search Plus - 支持中文搜索
* Prsim - 使用 Prism.js 高亮代码
* Advanced Emoji - 支持 emoji 表情
* Github - 添加github图标
* Github Buttons - 添加项目在 Github 上的 star、fork、watch 信息
* Ace Plugin - 支持ace
* Emphasize - 为文字加上底色
* KaTex - 支持数学公式
* Include Codeblock - 用代码块显示包含文件的内容
* Splitter - 使侧边栏的宽度可以自由调节
* Mermaid-gb3 - 支持渲染 Mermaid 图表
* Puml - 支持渲染 uml 图
* Graph - 使用 function-plot 绘制数学函数图
* Chart - 绘制图形
* Sharing-plus - 分享当前页面
* Tbfed-pagefooter - 为页面添加页脚
* Expandable-chapters-small - 使左侧的章节目录可以折叠
* Sectionx - 将页面分块显示
* GA - Google 统计
* 3-ba - 百度统计
* Donate - 打赏插件
* Local Video - 使用 Video.js 播放本地视频
* Simple-page-toc - 自动生成本页的目录结构
* Anchors - 添加 Github 风格的锚点
* Anchor-navigation-ex - 添加Toc到侧边悬浮导航以及回到顶部按钮
* Edit Link - 链接到当前页源文件上
* Sitemap-general - 生成sitemap
* Favicon - 更改网站的 favicon.ico
* Todo - 添加 Todo 功能
* Terminal - 模拟终端样式
* Copy-code-button - 为代码块添加复制按钮
* Alerts - 添加不同 alerts 样式的 blockquotes
* Include-csv - 显示 csv 文件内容
* Musicxml - 支持 musicxml 格式的乐谱渲染
* Klipse - 集成 Kplise (online code evaluator)
* Versions-select - 添加版本选择的下拉菜单
* Rss - 添加 rss 订阅功能

常用插件
editlink
内容顶部显示 编辑本页 链接。

ad
在每个页面顶部和底部添加广告或任何自定义内容。

splitter
在左侧目录和右侧内容之间添加一个可以拖拽的栏，用来调整两边的宽度。

image-captions
抓取内容中图片的 alt 或 title 属性，在图片下面显示标题。

github
在右上角显示 github 仓库的图标链接。

anchors
标题带有 github 样式的锚点。

chart
使用 C3.js 图表。

styles-sass
使用 SASS 替换 CSS。

styles-less
使用 LESS 替换 CSS。

ga
添加 Google 统计代码。

disqus
添加 disqus 评论插件。

sitemap
生成站点地图。

latex-codecogs
使用数学方程式。

mermaid
使用流程图。

book-summary-scroll-position-saver
自动保存左侧目录区域导航条的位置。

sharing
默认的分享插件。

fontsettings
默认的字体、字号、颜色设置插件。

search
默认搜索插件。

tbfed-pagefooter
自定义页脚，显示版权和最后修订时间。

prism
基于 Prism 的代码高亮。

atoc
插入 TOC 目录。

ace
插入代码高亮编辑器。

highlight
默认的代码高亮插件，通常会使用 prism 来替换。

github-buttons
显示 github 仓库的 star 和 fork 按钮。

sectionx
分离各个段落，并提供一个展开收起的按钮。

mcqx
使用选择题。

include-codeblock
通过引用文件插入代码。

fbqx
使用填空题。

spoiler
隐藏答案，当鼠标划过时才显示。

anchor-navigation
锚点导航。

youtubex
插入 YouTube 视频。

redirect
页面跳转。

expandable-chapters
收起或展开章节目录中的父节点。

baidu
使用百度统计。

duoshuo
使用多说评论。

jsfiddle
插入 JSFiddle 组件。

jsbin
插入 JSBin 组件。

开发插件
最好先查看别人的插件是怎么做的，然后再看官方文档。