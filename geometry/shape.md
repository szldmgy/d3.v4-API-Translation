
## [形状](https://github.com/d3/d3-shape)

可视化的图形原语。

### [弧](https://github.com/d3/d3-shape#arcs)

圆形或环形扇区，如饼图或甜甜圈图。

* [d3.arc](https://github.com/d3/d3-shape#arc) - 创建一个新的弧生成器。
* [*arc*](https://github.com/d3/d3-shape#_arc) - 创建给定数据的弧。
* [*arc*.centroid](https://github.com/d3/d3-shape#arc_centroid) - 弧中心。
* [*arc*.innerRadius](https://github.com/d3/d3-shape#arc_innerRadius) - 设置内径。
* [*arc*.outerRadius](https://github.com/d3/d3-shape#arc_outerRadius) - 设置外径。
* [*arc*.cornerRadius](https://github.com/d3/d3-shape#arc_cornerRadius) - 设置圆角半径。
* [*arc*.startAngle](https://github.com/d3/d3-shape#arc_startAngle) - 设置起始角度。
* [*arc*.endAngle](https://github.com/d3/d3-shape#arc_endAngle) - 设置结束角度。
* [*arc*.padAngle](https://github.com/d3/d3-shape#arc_padAngle) - 设置相邻弧之间的夹角。
* [*arc*.padRadius](https://github.com/d3/d3-shape#arc_padRadius) - 设置线性填充半径。
* [*arc*.context](https://github.com/d3/d3-shape#arc_context) - 设置渲染上下文。

### [饼](https://github.com/d3/d3-shape#pies)

计算用于展示饼图或甜环形图的必要的角度值。

* [d3.pie](https://github.com/d3/d3-shape#pie) - 创建一个饼生成器。
* [*pie*](https://github.com/d3/d3-shape#_pie) - 计算给定数据集的角度值。
* [*pie*.value](https://github.com/d3/d3-shape#pie_value) - 设置值访问器。
* [*pie*.sort](https://github.com/d3/d3-shape#pie_sort) - 设置排序比较器。
* [*pie*.sortValues](https://github.com/d3/d3-shape#pie_sortValues) - 设置排序比较器。
* [*pie*.startAngle](https://github.com/d3/d3-shape#pie_startAngle) - 设置整体的起始角度。
* [*pie*.endAngle](https://github.com/d3/d3-shape#pie_endAngle) - 设置整体的结束角度。
* [*pie*.padAngle](https://github.com/d3/d3-shape#pie_padAngle) - 设置相邻弧间隔角度。

### [线](https://github.com/d3/d3-shape#lines)

用于绘制线图的样条曲线或者折线。

* [d3.line](https://github.com/d3/d3-shape#line) - 创建一个新的线生成器。
* [*line*](https://github.com/d3/d3-shape#_line) - 生成给定数据的线。
* [*line*.x](https://github.com/d3/d3-shape#line_x) - 设置*x*访问器。
* [*line*.y](https://github.com/d3/d3-shape#line_y) - 设置*y*访问器。
* [*line*.defined](https://github.com/d3/d3-shape#line_defined) - 设置定义访问器。
* [*line*.curve](https://github.com/d3/d3-shape#line_curve) - 设置曲线插值器。
* [*line*.context](https://github.com/d3/d3-shape#line_context) - 设置渲染上下文。
* [d3.radialLine](https://github.com/d3/d3-shape#radialLine) - 创建一个新的径向线生成器。
* [*radialLine*](https://github.com/d3/d3-shape#_radialLine) - 生成给定数据的线。
* [*radialLine*.angle](https://github.com/d3/d3-shape#radialLine_angle) - 设置角度访问器。
* [*radialLine*.radius](https://github.com/d3/d3-shape#radialLine_radius) - 设置半径访问器。
* [*radialLine*.defined](https://github.com/d3/d3-shape#radialLine_defined) - 设置定义访问器。
* [*radialLine*.curve](https://github.com/d3/d3-shape#radialLine_curve) - 设置曲线插值器。
* [*radialLine*.context](https://github.com/d3/d3-shape#radialLine_context) - 设置渲染上下文。

### [面积](https://github.com/d3/d3-shape#areas)

由顶线基线构成，用于面积图。

* [d3.area](https://github.com/d3/d3-shape#area) - 创建一个新的面积生成器。
* [*area*](https://github.com/d3/d3-shape#_area) - 为给定数据集生成面积。
* [*area*.x](https://github.com/d3/d3-shape#area_x) - 设置 *x0* 和 *x1* 访问器。
* [*area*.x0](https://github.com/d3/d3-shape#area_x0) - 设置 基线的 *x* 访问器。
* [*area*.x1](https://github.com/d3/d3-shape#area_x1) - 设置顶线的 *x* 访问器。
* [*area*.y](https://github.com/d3/d3-shape#area_y) - 设置 *y0* 和 *y1* 访问器。
* [*area*.y0](https://github.com/d3/d3-shape#area_y0) - 设置基线的 *y* 访问器。
* [*area*.y1](https://github.com/d3/d3-shape#area_y1) - 设置顶线的 *y* 访问器。
* [*area*.defined](https://github.com/d3/d3-shape#area_defined) - 设置定义点访问器。
* [*area*.curve](https://github.com/d3/d3-shape#area_curve) - 设置曲线插值器。
* [*area*.context](https://github.com/d3/d3-shape#area_context) - 设置渲染上下文。
* [*area*.lineX0](https://github.com/d3/d3-shape#area_lineX0) - 为区域左边缘得到一条线。
* [*area*.lineX1](https://github.com/d3/d3-shape#area_lineX1) - 为区域右边缘得到一条线。
* [*area*.lineY0](https://github.com/d3/d3-shape#area_lineY0) - 为区域上边缘得到一条线。
* [*area*.lineY1](https://github.com/d3/d3-shape#area_lineY1) - 为区域下边缘得到一条线。
* [d3.radialArea](https://github.com/d3/d3-shape#radialArea) - 创建一个新的径向面积生成器。
* [*radialArea*](https://github.com/d3/d3-shape#_radialArea) - 为给定数据集生成面积。
* [*radialArea*.angle](https://github.com/d3/d3-shape#radialArea_angle) - 设置起始角度/结束角度访问器。
* [*radialArea*.startAngle](https://github.com/d3/d3-shape#radialArea_startAngle) - 设置起始角度访问器。
* [*radialArea*.endAngle](https://github.com/d3/d3-shape#radialArea_endAngle) - 设置结束角度访问器。
* [*radialArea*.radius](https://github.com/d3/d3-shape#radialArea_radius) - 设置内半径/外半径访问器。
* [*radialArea*.innerRadius](https://github.com/d3/d3-shape#radialArea_innerRadius) - 设置内半径访问器。
* [*radialArea*.outerRadius](https://github.com/d3/d3-shape#radialArea_outerRadius) - 设置外半径访问器。
* [*radialArea*.defined](https://github.com/d3/d3-shape#radialArea_defined) - 设置定义点访问器。
* [*radialArea*.curve](https://github.com/d3/d3-shape#radialArea_curve) - 设置曲线插值器。
* [*radialArea*.context](https://github.com/d3/d3-shape#radialArea_context) - 设置渲染上下文。
* [*radialArea*.lineStartAngle](https://github.com/d3/d3-shape#area_lineStartAngle) - 为区域起始边缘得到一条线。
* [*radialArea*.lineEndAngle](https://github.com/d3/d3-shape#area_lineEndAngle) - 为区域结束边缘得到一条线。
* [*radialArea*.lineInnerRadius](https://github.com/d3/d3-shape#area_lineInnerRadius) - 为区域内边缘得到一条线。
* [*radialArea*.lineOuterRadius](https://github.com/d3/d3-shape#area_lineOuterRadius) - 为区域外边缘得到一条线。

### [曲线](https://github.com/d3/d3-shape#curves)

通过在点间插值生成一条曲线。

* [d3.curveBasis](https://github.com/d3/d3-shape#curveBasis) - 立方基本样条，终点循环。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/basis.png" width="888" height="240" alt="basis" style="max-width:100%;" class="">

* [d3.curveBasisClosed](https://github.com/d3/d3-shape#curveBasisClosed) - 闭合立方基本样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/basisClosed.png" width="888" height="240" alt="basisClosed" style="max-width:100%;">

* [d3.curveBasisOpen](https://github.com/d3/d3-shape#curveBasisOpen) - 开放立方基本样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/basisOpen.png" width="888" height="240" alt="basisOpen" style="max-width:100%;">

* [d3.curveBundle](https://github.com/d3/d3-shape#curveBundle) - 直立方基本样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/bundle.png" width="888" height="240" alt="bundle" style="max-width:100%;">

* [d3.curveCardinal](https://github.com/d3/d3-shape#curveCardinal) - 三次C样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/cardinal.png" width="888" height="240" alt="cardinal" style="max-width:100%;">

* [d3.curveCardinalClosed](https://github.com/d3/d3-shape#curveCardinalClosed) - 闭合三次C样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/cardinalClosed.png" width="888" height="240" alt="cardinalClosed" style="max-width:100%;">

* [d3.curveCardinalOpen](https://github.com/d3/d3-shape#curveCardinalOpen) - 开放三次C样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/cardinalOpen.png" width="888" height="240" alt="cardinalOpen" style="max-width:100%;">

* [*cardinal*.tension](https://github.com/d3/d3-shape#cardinal_tension) - 设置基数样条曲线的张力。
* [d3.curveCatmullRom](https://github.com/d3/d3-shape#curveCatmullRom) - 立方Catmull-Rom样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/catmullRom.png" width="888" height="240" alt="catmullRom" style="max-width:100%;">

* [d3.curveCatmullRomClosed](https://github.com/d3/d3-shape#curveCatmullRomClosed) - 闭合立方Catmull-Rom样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/catmullRomClosed.png" width="888" height="330" alt="catmullRomClosed" style="max-width:100%;">

* [d3.curveCatmullRomOpen](https://github.com/d3/d3-shape#curveCatmullRomOpen) - 开放立方Catmull-Rom样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/catmullRomOpen.png" width="888" height="240" alt="catmullRomOpen" style="max-width:100%;">

* [*catmullRom*.alpha](https://github.com/d3/d3-shape#catmullRom_alpha) - 设置Catmull–Rom的*alpha*参数。
* [d3.curveLinear](https://github.com/d3/d3-shape#curveLinear) - 折线。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/linear.png" width="888" height="240" alt="linear" style="max-width:100%;">

* [d3.curveLinearClosed](https://github.com/d3/d3-shape#curveLinearClosed) - 闭合折线。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/linearClosed.png" width="888" height="240" alt="linearClosed" style="max-width:100%;">

* [d3.curveMonotoneX](https://github.com/d3/d3-shape#curveMonotoneX) - 立方样条。假设y是单调的，保持x的单调性。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/monotoneX.png" width="888" height="240" alt="monotoneX" style="max-width:100%;">

* [d3.curveMonotoneY](https://github.com/d3/d3-shape#curveMonotoneY) - 立方样条。假设x是单调的，保持y的单调性。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/monotoneY.png" width="888" height="240" alt="monotoneY" style="max-width:100%;">

* [d3.curveNatural](https://github.com/d3/d3-shape#curveNatural) - 自然三次样条。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/natural.png" width="888" height="240" alt="natural" style="max-width:100%;">

* [d3.curveStep](https://github.com/d3/d3-shape#curveStep) - 分段常值函数。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/step.png" width="888" height="240" alt="step" style="max-width:100%;">

* [d3.curveStepAfter](https://github.com/d3/d3-shape#curveStepAfter) - 分段常值函数。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/stepAfter.png" width="888" height="240" alt="stepAfter" style="max-width:100%;">

* [d3.curveStepBefore](https://github.com/d3/d3-shape#curveStepBefore) - 分段常值函数。
<img src="https://raw.githubusercontent.com/d3/d3-shape/master/img/stepBefore.png" width="888" height="240" alt="stepBefore" style="max-width:100%;">

* [*curve*.areaStart](https://github.com/d3/d3-shape#curve_areaStart) - 开始一个面积片段。
* [*curve*.areaEnd](https://github.com/d3/d3-shape#curve_areaEnd) - 结束一个面积片段。
* [*curve*.lineStart](https://github.com/d3/d3-shape#curve_lineStart) - 开始一条新的线段。
* [*curve*.lineEnd](https://github.com/d3/d3-shape#curve_lineEnd) - 结束一条新的线段。
* [*curve*.point](https://github.com/d3/d3-shape#curve_point) - 给当前线段加一个点。

### [符号](https://github.com/d3/d3-shape#symbols)

一些内置形状，用于散点图。

* [d3.symbol](https://github.com/d3/d3-shape#symbol) - 创建一个新的形状生成器。
* [*symbol*](https://github.com/d3/d3-shape#_symbol) - 为给定数据生成符号。
* [*symbol*.type](https://github.com/d3/d3-shape#symbol_type) - 设置符号类型。
* [*symbol*.size](https://github.com/d3/d3-shape#symbol_size) - 设置符号尺寸。
* [*symbol*.context](https://github.com/d3/d3-shape#symbol_context) - 设置渲染上下文。
* [d3.symbols](https://github.com/d3/d3-shape#symbols) - 符号类型数组。
* [d3.symbolCircle](https://github.com/d3/d3-shape#symbolCircle) - 圆形。
* [d3.symbolCross](https://github.com/d3/d3-shape#symbolCross) - 十字。
* [d3.symbolDiamond](https://github.com/d3/d3-shape#symbolDiamond) - 菱形。
* [d3.symbolSquare](https://github.com/d3/d3-shape#symbolSquare) - 方形。
* [d3.symbolStar](https://github.com/d3/d3-shape#symbolStar) - 五角星。
* [d3.symbolTriangle](https://github.com/d3/d3-shape#symbolTriangle) - 上三角。
* [d3.symbolWye](https://github.com/d3/d3-shape#symbolWye) - Y形。
* [*symbolType*.draw](https://github.com/d3/d3-shape#symbolType_draw) - 在给定的容器中绘制符号。

### [堆叠](https://github.com/d3/d3-shape#stacks)

将形状堆叠起来，就像分段条形图那样。

* [d3.stack](https://github.com/d3/d3-shape#stack) - 创建一个新的堆叠生成器。
* [*stack*](https://github.com/d3/d3-shape#_stack) - 为给定数据生成堆叠数据。
* [*stack*.keys](https://github.com/d3/d3-shape#stack_keys) - 设置键访问器。
* [*stack*.value](https://github.com/d3/d3-shape#stack_value) - 设置值访问器。
* [*stack*.order](https://github.com/d3/d3-shape#stack_order) - 设置排序访问器。
* [*stack*.offset](https://github.com/d3/d3-shape#stack_offset) - 设置偏移访问器。
* [d3.stackOrderAscending](https://github.com/d3/d3-shape#stackOrderAscending) - 将最小值放在底部。
* [d3.stackOrderDescending](https://github.com/d3/d3-shape#stackOrderDescending) - 将最大值放在底部。
* [d3.stackOrderInsideOut](https://github.com/d3/d3-shape#stackOrderInsideOut) - 将最大值放在中部。
* [d3.stackOrderNone](https://github.com/d3/d3-shape#stackOrderNone) - 使用给定的系列顺序。
* [d3.stackOrderReverse](https://github.com/d3/d3-shape#stackOrderReverse) - 系列给定的系列相反的顺序。
* [d3.stackOffsetExpand](https://github.com/d3/d3-shape#stackOffsetExpand) - 标准化为0=1之间。
* [d3.stackOffsetNone](https://github.com/d3/d3-shape#stackOffsetNone) - 应用零基准。
* [d3.stackOffsetSilhouette](https://github.com/d3/d3-shape#stackOffsetSilhouette) - 将流图居中在0附近。
* [d3.stackOffsetWiggle](https://github.com/d3/d3-shape#stackOffsetWiggle) - 流图最小摆动。
