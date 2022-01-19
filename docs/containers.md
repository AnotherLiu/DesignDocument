<h1>Containers</h1>

这里定义了若干最常见的容器样式，见下文的group，bar，list

指的就是通常位于界面顶部以及底部的标题栏，操作栏等，以及类似的布局，见下面的示例

<h2>Group</h2>
最简单的将按钮或者其它元素横向排列的容器，直接为容器添加“group”这个class即可

```
<!-- 这是一个包括了2个按钮的一个group -->
<div class="group">
<button>Button here</button>
<button class="secondary">Button here</button>
</div>
```

<div class="group">
<button>Button here</button>
<button class="secondary">Button here</button>
</div>

***

<h2>Bar</h2>
和group很类似，但由于场景不同还是分成了2个组件；一个bar是那种常见的，在界面顶部或底部占据一横条的容器，如顶部/底部导航栏，工具栏等，可用的class包括调整背景颜色的“bg-clear”，和调整其中子元素排列的“center”,“end”和“space-between”

```
<!-- 通过添加space-between，让bar的两个子元素分列于两边 -->
<div class="bar space-between">
这里是一个标题或者文字字段
<div class="group">
<button class="icon-add clear"></button>
<button class="icon-minus clear"></button>
<button class="icon-delete clear"></button>
</div>
</div>
```

<div class="bar space-between">
这里是一个标题或者文字字段
<div class="group">
<button class="icon-add clear"></button>
<button class="icon-minus clear"></button>
<button class="icon-delete clear"></button>
</div>
</div>

***
```
<!-- 将不同样式的按钮，通过为bar添加center的class，就形成了一个简易的tab -->
<div class="bar center">
<button>Button1</button>
<button class="clear">Button2</button>
<button class="clear">Button3</button>
</div>
```


<div class="bar center">
<button>Button1</button>
<button class="clear">Button2</button>
<button class="clear">Button3</button>
</div>

