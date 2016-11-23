# D3.js 4.x API中文手册

本文档会随官方文档同步更新。

# 说说4.x
今天（2016-05-14）打开D3的项目地址https://github.com/d3/d3 ，发现描述已经变成了：
>Bring data to life with SVG, Canvas and HTML

比以前多个了`Canvas`，也就是说D3.js的历史进入了新纪元。这是历经早期`Protovis`只支持`SVG`到后来d3.v3支持`HTML`操作，如今又进入了一个崭新的阶段将支持`Canvas`了。d3.v4的源码也有相当大的调整，最明显的是分成了很多小模块单独开发。模块化开发果然和预想的一样是要为支持`Canvas`做准备，这确实是一件让人热血澎湃的好事。D3留给我们的想象空间还很大。好吧，为了更好地拥抱新技术！本项目将通过对D3 V4官方文档的翻译对d3.v4做个全面深入的了解。本文为保持原汁原味，会采用直译，希望成为帮助大家入门d3.v4的第一手资料。

# 4.x的新功能

## 颜色，插值器，比例尺

+ 颜色有透明度（rgba，hsla等）。
+ 新增Cubehelix颜色空间。
+ 新增连续型颜色比例尺：绿松石（Viridis）和周期性的彩虹（cyclical Rainbow）。
+ 新增点比例尺和段比例尺替代以前的ordinal.rangeBands和ordinal.rangePoints。
+ 新增基本样条曲线插值器（例如连续的ColorBrewer）。

## 形状和布局。

+ 形状支持渲染成Canvas。
+ 修复了cardinal 和 monotone样条曲线。
+ 增加了参数化的 Catmull–Rom 和natural样条曲线。
+ 新的确定，可扩展的*速度Verlet*力布局。
+ 新的圆形填充布局。
+ 新的可扩展的矩形树布局；改良squarified treemaps；新增binary treemaps。
+ 新增d3.stratify用于处理行列式层次型数据（以前只支持JSON）。
+ 更快，可变的，非递归的四叉树。
+ 泰森多边形暴露有用的拓扑信息。

## 选择器，过渡，缓动和定时器。

+ 选择器和过渡现在是不变的，提供一个简洁的界面。
+ 新增selection.raise， selection.lower 和selection.dispatch 方法。
+ 时间在后台是冻结的，避免无意识的操作。
+ 定时器可以在外部停止。
+ 过渡现在支持 CSS 变换。
+ 可使用selection.interrupt取消过渡。
+ 更简单的过渡链（d3.active，transition.delay）。
+ 为同质转换提供更好的性能（例如元素间共享插值器）。
+ 更好地执行和持续过渡状态。
+ 修复松紧带缓冲函数和弹性缓冲函数。

## 其他

+ 默认的轴样式。
+ 更好的刷子交互。
+ 内置的用于并行加载数据的异步队列。
+ d3.ticks API。

# 我的感受

* 2016-5-20日下午五点左右，D3的star数超过50000次，位列所有前端库第二（仅次于boostrap）。自从2013年关注D3以来，几乎都超过每个月1000的增幅上涨着。虽然距离排名第一的前端库boostrap有些差距，但D3的这种发展速度和受欢迎程度相信会继续给我带来更多的惊喜。

* 翻译D3 V4的API发现与D3 V3的差别很大，功能也更多更完善，就力导向图就从原来的12个功能函数增加到现在的41个（包含二级函数），这势必会给我们做数据可视化带来更多的便利。

* 路径这部分的API主要用来将Canvas命令转换为SVG路径的d属性的值。本质上最后还是用SVG画图。这一点可能跟我们想要的直接用Canvas画大数据量数据的需求不一样，看来以后还是得手动来实现了，这一点略微还是有些失望的~

* D3 V4的大量API由原来的二级函数升级为一级函数（实际上就是把两级的单词合并，使用驼峰命名法重命名了），这样给使用者带来了一些记忆负担，其实以前的API设计得更好用点~

# 加群讨论

||新手群|专业群|研究群|
|---|---|---|---|
|说明|免费（暂时）|付费|免费（新手别加）|
|群名|D3.js|D3数据可视化|大数据可视化|
|群号|437278817|205076374|436442115|
|二维码| <img src="http://img.blog.csdn.net/20161105095608477" width = "300" height = "300" alt="D3.js" align=center />|<img src="http://img.blog.csdn.net/20161105095649087" width = "300" height = "300" alt="D3数据可视化" align=center />|<img src="http://img.blog.csdn.net/20161105095514714" width = "300" height = "300" alt="大数据可视化" align=center />|

-----------

下面是译文，欢迎一起翻译，探讨~

-----------

# D3: 数据驱动文档（Data-Driven Documents）

<a href="https://d3js.org"><img src="https://d3js.org/logo.svg" align="left" hspace="10" vspace="6"></a>

**D3** (或**D3.js**) 是一个用来使用Web标准做数据可视化的JavaScript函数库。

D3帮助我们可以融合SVG, Canvas 和 HTML操作技术让数据变得生动有趣。

D3将强大的**可视化**，**动态交互**和**数据驱动的DOM操作方法**完美结合，让我们可以充分发挥现代浏览器的功能，自由地设计正确的可视化界面。



## 资料

* [API参考](https://github.com/d3/d3/blob/master/API.md)
* [发行版](https://github.com/d3/d3/releases)
* [展廊](https://github.com/d3/d3/wiki/Gallery)
* [案例](http://bl.ocks.org/mbostock)
* [Wiki](https://github.com/d3/d3/wiki)

## 安装

最近的稳定版是 (4.x.0), 可以按照wiki里的 [安装介绍 ](https://github.com/d3/d3/wiki#installing) 安装使用。如果你使用NPM, 可执行`npm install d3`命令。不然的话可以下载[最新版](https://github.com/d3/d3/releases/latest)。 发布包支持AMD, CommonJS, 和 vanilla 环境。自定义编译可以使用 [Rollup](https://github.com/rollup/rollup) 或者其他打包工具。也可以直接从[d3js.org](https://d3js.org)引用:

```html
<script src="https://d3js.org/d3.v4.min.js"></script>
```

非压缩版移除上面的`.min`即可。

## API 总览

选择元素
* [选择](#selections) ([选择](#selecting-elements), [修改](#modifying-elements), [数据](#joining-data), [事件](#handling-events), [控制](#control-flow), [命名空间](#namespaces))

数据类型
* [数组](#arrays) ([统计](#statistics), [直方图](#histograms), [查找](#search), [转换](#transformations))
* [集合](#collections) ([对象](#objects), [映射（map）](#maps), [集合（set）](#sets), [嵌套](#nests))
* [颜色](#colors)
* [DSV（分隔符分割的值）](#delimiter-separated-values)
* [随机值](#random-numbers)
* [时间序列](#time-intervals)

格式化
* [数字格式化](#number-formats)
* [时间格式化](#time-formats)

加载数据
* [队列](#queues)
* [请求](#requests)

数据映射
* [比例尺](#scales) ([连续型](#continuous-scales), [颜色序数型](#sequential-color-scales), [数值型](#quantize-scales), [序数型](#ordinal-scales), [分类颜色型](#categorical-color-scales))

图形几何
* [形状](#shapes) ([弧](#arcs), [饼](#pies), [线](#lines), [面积](#areas), [曲线](#curves), [符号](#symbols), [堆叠](#stacks))
* [轴](#axes)
* [泰森多边形](#voronoi-diagrams)
* [路径](#paths)
* [多边形](#polygons)
* [四叉树](#quadtrees)

布局
* [力布局](#forces)
* [层次布局](#hierarchies)

动态交互
* [定时器](#timers)
* [过渡](#transitions)
* [插值器](#interpolators)
* [缓动](#easings)
* [事件分派](#dispatches)
* [拖动](#dragging)
* [缩放](#zooming)

D3 使用 [语义命名](http://semver.org/)。可使用d3.version获取当前版本号。