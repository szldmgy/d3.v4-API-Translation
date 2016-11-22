## [比例尺](https://github.com/d3/d3-scale)

映射抽象数据为可视化表示所需要的形式。

### [连续型比例尺](https://github.com/d3/d3-scale#continuous-scales)

将连续的，数量的定义域映射为连续的值域上。

* [*continuous*](https://github.com/d3/d3-scale#_continuous) - 计算对应于给定的定义域的值域。
* [*continuous*.invert](https://github.com/d3/d3-scale#continuous_invert) - 计算对应于给定的值域的定义域。
* [*continuous*.domain](https://github.com/d3/d3-scale#continuous_domain) - 设置输入的定义域。
* [*continuous*.range](https://github.com/d3/d3-scale#continuous_range) - 设置输出的值域。
* [*continuous*.rangeRound](https://github.com/d3/d3-scale#continuous_rangeRound) - 设置取整后的值域
* [*continuous*.clamp](https://github.com/d3/d3-scale#continuous_clamp) - 启用闭合。
* [*continuous*.interpolate](https://github.com/d3/d3-scale#continuous_interpolate) - 设置输出插值器。
* [*continuous*.ticks](https://github.com/d3/d3-scale#continuous_ticks) - 计算定义域中有代表性的刻度值。
* [*continuous*.tickFormat](https://github.com/d3/d3-scale#continuous_tickFormat) - 格式化刻度值。
* [*continuous*.nice](https://github.com/d3/d3-scale#continuous_nice) - 优化定义域。
* [*continuous*.copy](https://github.com/d3/d3-scale#continuous_copy) - 创建比例尺的副本。
* [d3.scaleLinear](https://github.com/d3/d3-scale#scaleLinear) - 创建定量线性比例尺。
* [d3.scalePow](https://github.com/d3/d3-scale#scalePow) - 创建定量幂比例尺。
* [*pow*](https://github.com/d3/d3-scale#_pow) - 计算对应于给定的定义域的值域。
* [*pow*.invert](https://github.com/d3/d3-scale#pow_invert) - 计算对应于给定的值域的定义域。
* [*pow*.exponent](https://github.com/d3/d3-scale#pow_exponent) - 设置幂指数。
* [*pow*.domain](https://github.com/d3/d3-scale#pow_domain) - 设置输入的定义域。
* [*pow*.range](https://github.com/d3/d3-scale#pow_range) - 设置输出的值域。
* [*pow*.rangeRound](https://github.com/d3/d3-scale#pow_rangeRound) - 设置取整后的值域
* [*pow*.clamp](https://github.com/d3/d3-scale#pow_clamp) - 启用闭合。
* [*pow*.interpolate](https://github.com/d3/d3-scale#pow_interpolate) - 设置输出插值器。
* [*pow*.ticks](https://github.com/d3/d3-scale#pow_ticks) - 计算定义域中有代表性的刻度值。
* [*pow*.tickFormat](https://github.com/d3/d3-scale#pow_tickFormat) - 格式化刻度值。
* [*pow*.nice](https://github.com/d3/d3-scale#pow_nice) - 优化定义域。
* [*pow*.copy](https://github.com/d3/d3-scale#pow_copy) - 创建比例尺的副本。
* [d3.scaleSqrt](https://github.com/d3/d3-scale#scaleSqrt) - 创建一个幂比例尺，指数是0.5。
* [d3.scaleLog](https://github.com/d3/d3-scale#scaleLog) - 创建定量对数比例尺。
* [*log*](https://github.com/d3/d3-scale#_log) - 计算对应于给定的定义域的值域。
* [*log*.invert](https://github.com/d3/d3-scale#log_invert) - 计算对应于给定的值域的定义域。
* [*log*.base](https://github.com/d3/d3-scale#log_base) - 设置对数基底。
* [*log*.domain](https://github.com/d3/d3-scale#log_domain) - 设置输入的定义域。
* [*log*.range](https://github.com/d3/d3-scale#log_range) - 设置输出的值域。
* [*log*.rangeRound](https://github.com/d3/d3-scale#log_rangeRound) - 设置取整后的值域
* [*log*.clamp](https://github.com/d3/d3-scale#log_clamp) - 启用闭合。
* [*log*.interpolate](https://github.com/d3/d3-scale#log_interpolate) - 设置输出插值器。
* [*log*.ticks](https://github.com/d3/d3-scale#log_ticks) - 计算定义域中有代表性的刻度值。
* [*log*.tickFormat](https://github.com/d3/d3-scale#log_tickFormat) - 格式化刻度值。
* [*log*.nice](https://github.com/d3/d3-scale#log_nice) - 优化定义域。
* [*log*.copy](https://github.com/d3/d3-scale#log_copy) - 创建比例尺的副本。
* [d3.scaleIdentity](https://github.com/d3/d3-scale#identity) - 创建定量恒等比例尺。
* [d3.scaleTime](https://github.com/d3/d3-scale#scaleTime) - 创建时间线性比例尺。
* [*time*](https://github.com/d3/d3-scale#_time) - 计算对应于给定的定义域的值域。
* [*time*.invert](https://github.com/d3/d3-scale#time_invert) - 计算对应于给定的值域的定义域。
* [*time*.domain](https://github.com/d3/d3-scale#time_domain) - 设置输入的定义域。
* [*time*.range](https://github.com/d3/d3-scale#time_range) - 设置输出的值域。
* [*time*.rangeRound](https://github.com/d3/d3-scale#time_rangeRound) - 设置取整后的值域
* [*time*.clamp](https://github.com/d3/d3-scale#time_clamp) - 启用闭合。
* [*time*.interpolate](https://github.com/d3/d3-scale#time_interpolate) - 设置输出插值器。
* [*time*.ticks](https://github.com/d3/d3-scale#time_ticks) - 计算定义域中有代表性的刻度值。
* [*time*.tickFormat](https://github.com/d3/d3-scale#time_tickFormat) - 格式化刻度值。
* [*time*.nice](https://github.com/d3/d3-scale#time_nice) - 优化定义域。
* [*time*.copy](https://github.com/d3/d3-scale#time_copy) - 创建比例尺的副本。
* [d3.scaleUtc](https://github.com/d3/d3-scale#scaleUtc) - 创建UTC时间的线性比例尺。

### [连续颜色比例尺](https://github.com/d3/d3-scale#scaleSequential)

将连续的，数量的定义域映射为连续的，固定的颜色插值器。

* [d3.scaleSequential](https://github.com/d3/d3-scale#scaleSequential) - 创建一个顺序比例尺。create a sequential scale.
* [*sequential*.interpolator](https://github.com/d3/d3-scale#sequential_interpolator) - 设置比例尺的输出插值器。
* [d3.interpolateViridis](https://github.com/d3/d3-scale#interpolateViridis) - 暗到明的颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/viridis.png" width="100%" height="40" alt="viridis">

* [d3.interpolateInferno](https://github.com/d3/d3-scale#interpolateInferno) - 暗到明的颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/inferno.png" width="100%" height="40" alt="inferno">

* [d3.interpolateMagma](https://github.com/d3/d3-scale#interpolateMagma) - 暗到明的颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/magma.png" width="100%" height="40" alt="magma">

* [d3.interpolatePlasma](https://github.com/d3/d3-scale#interpolatePlasma) - 暗到明的颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/plasma.png" width="100%" height="40" alt="plasma">

* [d3.interpolateWarm](https://github.com/d3/d3-scale#interpolateWarm) - 色相环颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/warm.png" width="100%" height="40" alt="warm">

* [d3.interpolateCool](https://github.com/d3/d3-scale#interpolateCool) - 色相环颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/cool.png" width="100%" height="40" alt="cool">

* [d3.interpolateRainbow](https://github.com/d3/d3-scale#interpolateRainbow) - 循环的色相环颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/rainbow.png" width="100%" height="40" alt="rainbow">

* [d3.interpolateCubehelixDefault](https://github.com/d3/d3-scale#interpolateCubehelixDefault) - 暗到明的色相环颜色组合。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/cubehelix.png" width="100%" height="40" alt="cubehelix">

### [量化比例尺](https://github.com/d3/d3-scale#quantize-scales)

将连续的数量的定义域映射为离散的值域。

* [d3.scaleQuantize](https://github.com/d3/d3-scale#scaleQuantize) - 创建一个均匀的量化的线性比例尺。
* [*quantize*](https://github.com/d3/d3-scale#_quantize) - 计算对应于给定的定义域的值域。
* [*quantize*.invertExtent](https://github.com/d3/d3-scale#quantize_invertExtent) - 计算对应于给定的值域的定义域。
* [*quantize*.domain](https://github.com/d3/d3-scale#quantize_domain) - 设置输入的定义域。
* [*quantize*.range](https://github.com/d3/d3-scale#quantize_range) - 设置输出的值域。
* [*quantize*.nice](https://github.com/d3/d3-scale#quantize_nice) - 优化定义域。
* [*quantize*.ticks](https://github.com/d3/d3-scale#quantize_ticks) - 计算定义域中有代表性的刻度值。
* [*quantize*.tickFormat](https://github.com/d3/d3-scale#quantize_tickFormat) - 格式化刻度值。
* [*quantize*.copy](https://github.com/d3/d3-scale#quantize_copy) - 创建比例尺的副本。
* [d3.scaleQuantile](https://github.com/d3/d3-scale#scaleQuantile) - 创建一个分位数的量化的线性比例尺。
* [*quantile*](https://github.com/d3/d3-scale#_quantile) - 计算对应于给定的定义域的值域。
* [*quantile*.invertExtent](https://github.com/d3/d3-scale#quantile_invertExtent) - 计算对应于给定的值域的定义域。
* [*quantile*.domain](https://github.com/d3/d3-scale#quantile_domain) - 设置输入的定义域。
* [*quantile*.range](https://github.com/d3/d3-scale#quantile_range) - 设置输出的值域。
* [*quantile*.quantiles](https://github.com/d3/d3-scale#quantile_quantiles) - 设置分位数的阈值。
* [*quantile*.copy](https://github.com/d3/d3-scale#quantile_copy) - 创建比例尺的副本。
* [d3.scaleThreshold](https://github.com/d3/d3-scale#scaleThreshold) - 创建一个任意的量化的线性比例尺。
* [*threshold*](https://github.com/d3/d3-scale#_threshold) - 计算对应于给定的定义域的值域。
* [*threshold*.invertExtent](https://github.com/d3/d3-scale#threshold_invertExtent) - 计算对应于给定的值域的定义域。
* [*threshold*.domain](https://github.com/d3/d3-scale#threshold_domain) - 设置输入的定义域。
* [*threshold*.range](https://github.com/d3/d3-scale#threshold_range) - 设置输出的值域。
* [*threshold*.copy](https://github.com/d3/d3-scale#threshold_copy) - 创建比例尺的副本。

### [序数比例尺](https://github.com/d3/d3-scale#ordinal-scales)

定义域和值域都是离散的。

* [d3.scaleOrdinal](https://github.com/d3/d3-scale#scaleOrdinal) - 创建一个序数比例尺。
* [*ordinal*](https://github.com/d3/d3-scale#_ordinal) - 计算对应于给定的定义域的值域。
* [*ordinal*.domain](https://github.com/d3/d3-scale#ordinal_domain) - 设置输入的定义域。
* [*ordinal*.range](https://github.com/d3/d3-scale#ordinal_range) - 设置输出的值域。
* [*ordinal*.unknown](https://github.com/d3/d3-scale#ordinal_unknown) - 设置未知输入域的输出值。
* [*ordinal*.copy](https://github.com/d3/d3-scale#ordinal_copy) - 创建比例尺的副本。
* [d3.scaleImplicit](https://github.com/d3/d3-scale#scaleImplicit) - 隐域的一个特殊的未知值。
* [d3.scaleBand](https://github.com/d3/d3-scale#scaleBand) - 创建序数段比例尺。
* [*band*](https://github.com/d3/d3-scale#_band) - 计算对应于给定的定义域的值域。
* [*band*.domain](https://github.com/d3/d3-scale#band_domain) - 设置输入的定义域。
* [*band*.range](https://github.com/d3/d3-scale#band_range) - 设置输出的值域。
* [*band*.rangeRound](https://github.com/d3/d3-scale#band_rangeRound) - 设置输出的值域并取整。
* [*band*.round](https://github.com/d3/d3-scale#band_round) - 取整。
* [*band*.paddingInner](https://github.com/d3/d3-scale#band_paddingInner) - 段间距。
* [*band*.paddingOuter](https://github.com/d3/d3-scale#band_paddingOuter) - 外边距。
* [*band*.padding](https://github.com/d3/d3-scale#band_padding) - 设置间距（段间距和外边距）。
* [*band*.align](https://github.com/d3/d3-scale#band_align) - 设置段对齐。
* [*band*.bandwidth](https://github.com/d3/d3-scale#band_bandwidth) - 获取每段宽度。
* [*band*.step](https://github.com/d3/d3-scale#band_step) - 开始相邻段之间的距离。
* [*band*.copy](https://github.com/d3/d3-scale#band_copy) - 创建比例尺的副本。
* [d3.scalePoint](https://github.com/d3/d3-scale#scalePoint) - 创建序数点比例尺。
* [*point*](https://github.com/d3/d3-scale#_point) - 计算对应于给定的定义域的值域。
* [*point*.domain](https://github.com/d3/d3-scale#point_domain) - 设置输入的定义域。
* [*point*.range](https://github.com/d3/d3-scale#point_range) - 设置输出的值域。
* [*point*.rangeRound](https://github.com/d3/d3-scale#point_rangeRound) - 设置输出的值域并取整。
* [*point*.round](https://github.com/d3/d3-scale#point_round) - 取整。
* [*point*.padding](https://github.com/d3/d3-scale#point_padding) - 外边距。
* [*point*.align](https://github.com/d3/d3-scale#point_align) - 设置点对齐。
* [*point*.bandwidth](https://github.com/d3/d3-scale#point_bandwidth) - 返回0。
* [*point*.step](https://github.com/d3/d3-scale#point_step) - 开始相邻点之间的距离。
* [*point*.copy](https://github.com/d3/d3-scale#point_copy) - 创建比例尺的副本。
* [d3.schemeCategory10](https://github.com/d3/d3-scale#scaleCategory10) - 10种分类颜色。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/category10.png" width="100%" height="40" alt="category10">

* [d3.schemeCategory20](https://github.com/d3/d3-scale#scaleCategory20) - 20种分类颜色。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/category20.png" width="100%" height="40" alt="category20">

* [d3.schemeCategory20b](https://github.com/d3/d3-scale#scaleCategory20b) - 20种分类颜色。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/category20b.png" width="100%" height="40" alt="category20b">

* [d3.schemeCategory20c](https://github.com/d3/d3-scale#scaleCategory20c) - 20种分类颜色。
<img src="https://raw.githubusercontent.com/d3/d3-scale/master/img/category20c.png" width="100%" height="40" alt="category20c">
