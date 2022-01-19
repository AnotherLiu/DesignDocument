<h1>Button</h1>

从内容上区分，按钮的内容可以是一个字段，一个图标，也可以是一个图标加一个字段；从尺寸上区分，按钮可以是默认大小，也可以是小按钮或大按钮；从样式上区分，按钮可以有不同的底色和文字/图标颜色；看下面的code示例，总共可用的class包括：secondary, clear, big, extra-big, full, 如果按钮中有图标，直接添加对应图标的class，如icon-add





```
<button>Default Button</button>
```
<button>Default Button</button>

***


```
<button class="secondary">Secondary Button</button>
```
<button class="secondary">Secondary Button</button>

***
```
<button class="clear">Clear Button</button>
```
<button class="clear">Clear Button</button>
***

```
<!-- 直接添加icon名称的class，即可添加icon在左边 -->
<button class="icon-add">button with icon</button>
```
<button class="icon-add">button with icon</button>

***

```
<!-- 如果是icon在上边，添加vertical -->
<button class="icon-delete vertical">icon on top</button>
```
<button class="icon-delete vertical">icon on top</button>

***

```
<!-- 不写文字就是单独的icon button -->
<button class="icon-add"></button>
<button class="icon-add big clear"></button>
<button class="icon-add extra-big secondary"></button>
```
<button class="icon-add"></button>
<button class="icon-add big clear"></button>
<button class="icon-add extra-big secondary"></button>

***

```
<button class="icon-add big full">big icon button with full width</button>
```
<button class="icon-add big full">big icon button with full width</button>

***