<h1>Badge</h1>

为元素添加一个角标，也就是所谓的小红点，里面可以填充一个字段，比如数字或者其它文字；使用方法是，为添加badge的元素增加badged这个class，然后添加badge-text这个attribute，传入一个string

```
<!-- 几个添加了badge的元素，放到了一个bar里面 -->
<div class="bar space-between">
<span class="badged" badge-text="badge">some text with a badge in the corner</span>
<button class="secondary badged" badge-text="new">A Badged Button</button>
<button class="icon-list clear grey badged" badge-text="12"></button></div>
```

<div class="bar space-between">
<span class="badged" badge-text="badge">some text with a badge in the corner</span>
<button class="secondary badged" badge-text="new">A Badged Button</button>
<button class="icon-list clear grey badged" badge-text="12"></button></div>
