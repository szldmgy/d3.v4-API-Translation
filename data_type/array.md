## [数组](https://github.com/d3/d3-array)

数组操作，排序，查找，汇总等。

#### [统计](https://github.com/d3/d3-array#statistics)

计算基本汇总统计的一些方法。

* [d3.min](https://github.com/d3/d3-array#min) - 计算数组中的最小值。
* [d3.max](https://github.com/d3/d3-array#max) - 计算数组中的最大值。
* [d3.extent](https://github.com/d3/d3-array#extent) - 计算数组的范围。
* [d3.sum](https://github.com/d3/d3-array#sum) - 数组中所有元素求和。
* [d3.mean](https://github.com/d3/d3-array#mean) - 计算数组的算术平均值。
* [d3.median](https://github.com/d3/d3-array#median) - 计算数组的中位数。
* [d3.quantile](https://github.com/d3/d3-array#quantile) - 计算一个数字数组排序后的分位数。
* [d3.variance](https://github.com/d3/d3-array#variance) - 数组中数字的方差。
* [d3.deviation](https://github.com/d3/d3-array#deviation) - 数组中数字的标准差。

#### [直方图](https://github.com/d3/d3-array#histograms)

将离散样本分成连续的无重叠的间隔。

* [d3.histogram](https://github.com/d3/d3-array#histogram) - 创建一个新的直方图生成器。
* [*histogram*](https://github.com/d3/d3-array#_histogram) - 对给定的样本数组计算直方图。
* [*histogram*.value](https://github.com/d3/d3-array#histogram_value) - 为每个样本指定一个值访问器。
* [*histogram*.domain](https://github.com/d3/d3-array#histogram_domain) - 指定可观测值的间隔。
* [*histogram*.thresholds](https://github.com/d3/d3-array#histogram_thresholds) - 指定值划分成不同箱的方法。
* [d3.thresholdFreedmanDiaconis](https://github.com/d3/d3-array#thresholdFreedmanDiaconis) - Freedman–Diaconis装箱规则。
* [d3.thresholdScott](https://github.com/d3/d3-array#thresholdScott) - Scott’s normal reference装箱规则。
* [d3.thresholdSturges](https://github.com/d3/d3-array#thresholdSturges) - Sturges’装箱准则。

#### [查找](https://github.com/d3/d3-array#search)

检索数组中特定的值。

* [d3.scan](https://github.com/d3/d3-array#scan) - 使用比较器线查找。
* [d3.bisect](https://github.com/d3/d3-array#bisect) - 二分查找排序数组中的值。
* [d3.bisectRight](https://github.com/d3/d3-array#bisectRight) - 二分查找排序数组中的值。
* [d3.bisectLeft](https://github.com/d3/d3-array#bisectLeft) - 二分查找排序数组中的值。
* [d3.bisector](https://github.com/d3/d3-array#bisector) - 使用访问器和比较器二分查找。
* [*bisector*.left](https://github.com/d3/d3-array#bisector_left) - 使用给定的比较器的bisectLeft。
* [*bisector*.right](https://github.com/d3/d3-array#bisector_right) - 使用给定的比较器的bisectRight。
* [d3.ascending](https://github.com/d3/d3-array#ascending) - 升序排序。
* [d3.descending](https://github.com/d3/d3-array#descending) - 降序排序。

#### [转换](https://github.com/d3/d3-array#transformations)

转换数组并返回一个新的数组。

* [d3.merge](https://github.com/d3/d3-array#merge) - 将多个数组合并成一个。
* [d3.pairs](https://github.com/d3/d3-array#pairs) - 创建一个相邻对数组。
* [d3.permute](https://github.com/d3/d3-array#permute) - 安装指定的索引数组重排数组。
* [d3.shuffle](https://github.com/d3/d3-array#shuffle) - 数组随机排序。
* [d3.ticks](https://github.com/d3/d3-array#ticks) - 从一个数组间隔生成有代表的值。
* [d3.tickStep](https://github.com/d3/d3-array#tickStep) - 从一个数组间隔生成有代表的值。
* [d3.range](https://github.com/d3/d3-array#range) - 生成一组数值。
* [d3.transpose](https://github.com/d3/d3-array#transpose) - 数组转置。
* [d3.zip](https://github.com/d3/d3-array#zip) - 转置多个数组。
