<h1>Icon</h1>

目前所有icon都放到了iconfont的图标库，具体使用方法如下

<h2>使用方法1：直接导入字体</h2>

如果你直接使用文档提供的<a href="universal-style.scss" target="_blank">scss</a>，可以看到它的头部已经导入了目前正在用的图标库，直接在html中添加对应的class即可，如下


```
<!-- 单独使用图标，为元素添加两个class，一个是iconfont，另一个是icon-xxx（xxx是具体图标名字） -->
<i class="iconfont icon-add"></i>
```
<i class="iconfont icon-add"></i>

***


```
<!-- 图标作为按钮使用，下面是示例，更多说明可以查看侧边栏里的Button部分 -->
<button class="icon-close"></button>
```
<button class="icon-close"></button>


<h2>使用方法2：手动下载需要的图片格式</h2>

如果你不使用字体格式，需要其它图片格式如png，svg等，则需要登录[iconfont](https://www.iconfont.cn)，并告知我你的用户名，以便我把图标库分享给你，然后你就可以自行下载需要的图标了