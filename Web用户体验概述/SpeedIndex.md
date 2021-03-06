# SpeedIndex

Speed Index是指一个页面的可视部分完全展示出来的平均时间。它用毫秒作为计量单位，并且取决于视窗的大小。

WebPagetest在2012年4月增加了Speed Index，用来测量页面内容的展示速度（数值越小越好）。用它来比较页面之间（优化前和优化后的比较、与竞争对手的比较）的体验非常有效，并且与onload、start render等性能指标相比能更加直观地表达一个网站的性能。

以往我们一直依赖于一些关键时间点来判断web页面的快慢，他们中最常见的就是onload。onload这个事件可以在开发和正式环境中非常简单得得到。但不幸的是，这不是一个能很好地反应最终用户体验的指标。当页面上加载一些不可见或者屏幕以外的内容时，onload事件会被拉长，即使这时对于用户来说可见内容都早已渲染完成了。于是我们引入了更多的时间点，期望更好得表达加载过程（包括首次渲染时间、domready时间等等），但他们都存在根本性的缺陷，因为它们都是测量一个孤立的时间点，并且不能传达实际的用户体验。

## Speed Index 计算方法

Speed Index采用可视页面加载过程中的视觉进度，并计算一个描述内容渲染速度的总分。要做到这一点，首先需要计算页面加载过程中页面渲染的完成度。在WebPagetest中这是通过捕捉页面在浏览器中的加载过程，然后分析每一帧（目前是每秒10帧）。当前的算法下用于计算每一帧的完整性描述如下，我们假设我们可以确定视频中每一帧的完成度的百分比（数字显示在每帧的下面）：

