

<h1>这个文档是什么？是给谁看的？</h1>

建立这个文档的目的是给出一个不同软件通用的设计规范和组件，比如UI上的文字是什么字号，按钮是什么颜色，点击下去是什么反应，也包括更复杂（但依然是由简单元素构成的）对话框的样式等；

> 这份文档是给软件的前端开发看的，测试也可以参考；如果你既不是前端开发也不是测试工程师，就没有必要看


***

<h1>怎么用这个文档？</h1>

总的来说，这个文档基本上是一个**CSS框架**，和市面上常见的css框架，如tailwind，bulma类似，你导入一个统一的CSS文件，直接在html页面的标签中加入对应的class，即可直接应用对应的UI组件和样式

下面是按钮组件的一个示例，查看html部分，可以看到组件的结构，以及使用了什么class

***

```
<button class="secondary">Secondary Button</button>
```
<button class="secondary">Secondary Button</button>


***
<a href="universal-style.scss" target="_blank">点击这里</a>查看需要导入或粘贴的CSS code

<h2>如果你使用html和css构建UI，这样使用：</h2>

1. 粘贴上面的css code到项目中
2. 根据项目修改code顶部的变量
3. 在html中使用对应的标签和class，如上面的button标签和secondary class

<h2>如果你不使用html和css构建UI，那这样使用：</h2>

1. 查看组件使用了什么标签和class，如上面的button标签和secondary class
2. 在scss code中找到对应的code，我也在code旁添加了样式说明

