<h1>Text</h1>

目前定义的text样式包括：h1, h2,h3和a，可用的class包括grey,和description，见下面的示例

```
<h1>这是h1字段</h1>
<h2>这是h2字段</h2>
<h3>这是h3字段</h3>
<p>不添加其它样式，就是默认的14px大小的正文</p>
<p class="grey">颜色更浅的正文</p>
<p class="description">说明文字更小一些</p>
<a class="h3">添加了链接的h3文字样式</a>


```
<h1>这是h1字段</h1>
<h2>这是h2字段</h2>
<h3>这是h3字段</h3>
<p>不添加其它样式，就是默认的14px大小的正文</p>
<p class="grey">颜色更浅的正文</p>
<p class="description">说明文字更小一些</p>
<a class="h3">添加了链接的h3文字样式</a>


***


<h3>关于文字的截断</h3>

对于常规正文不做截断处理，自动换行，界面也会根据文字高度调整整体高度；对于菜单等组件中的文字，默认从末尾截断；如果文字是文件名称，则默认倒数第7个字符开始截断；如字段“qwertyuiopasdfghjkl.jpg”,截断后为“qwertyuio...jkl.jpg”

<h3>关于时间字段</h3>

有太多的地方需要反复进行时间字段说明，这里统一说明：

**一个时间字段由“时钟”和“星期”和“年月日”中的1个或多个个字段组成，如下**

- 时钟：24小时制，精确到分钟，具体字段如"15:32","07:01"

- 星期：
    - 日期为今天，则该字段为"今天"，或省略该字段
    - 日期为昨天，则该字段为"昨天"
    - 日期为明天，则该字段为"明天"
    - 日期为其它，则正常显示，如"周三"；英文可使用缩写如"Mon"
    
- 年月日：
    - 日期为今年，显示如"01-03"
    - 日期不是今年，则显示年份，如"2018 06-21"

如果同时显示多个字段，则显示顺序为星期>年月日>时钟

下面是一些常见的时间字段功能：

邮件/笔记事项等
- 当天的时间点，仅显示**时钟**，如"14:33" "07:06"
- 一周之内的时间点，显示**星期+年月日+时钟**，如"昨天 01-17 14:36"
- 其它时间，仅显示**日期**

会议等时间段
- 会议为时间段，显示两个时间字段，并用“ - ”连接；每个时间字段显示规则和上面的邮件/笔记相同
- 如果两个时间字段在同一天，则第二个时间字段不显示仅显示**时钟**字段，如“昨天 01-17 12:00 - 14:00”

天气
- 天气字段显示**星期+年月日**，如"周三 01-19"



