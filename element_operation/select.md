
## [选择器](https://github.com/d3/d3-selection)

通过选择元素和加入数据来转换DOM。

### [选择元素](https://github.com/d3/d3-selection#selecting-elements)

* [d3.selection](https://github.com/d3/d3-selection#selection) - 选择根文档元素。
* [d3.select](https://github.com/d3/d3-selection#select) - 从文档中选择一个元素。
* [d3.selectAll](https://github.com/d3/d3-selection#selectAll) - 从文档中选择多个元素。
* [*selection*.select](https://github.com/d3/d3-selection#selection_select) - 选择每个选中元素的一个后代元素。
* [*selection*.selectAll](https://github.com/d3/d3-selection#selection_selectAll) - 选择每个选中元素的多个后代元素。
* [*selection*.filter](https://github.com/d3/d3-selection#selection_filter) - 基于数据过滤元素。
* [*selection*.merge](https://github.com/d3/d3-selection#selection_merge) - 合并两个选择。
* [d3.matcher](https://github.com/d3/d3-selection#matcher) - 测试一个元素是否匹配选择器。
* [d3.selector](https://github.com/d3/d3-selection#selector) - 选择一个元素。
* [d3.selectorAll](https://github.com/d3/d3-selection#selectorAll) - 选择多个元素。
* [d3.window](https://github.com/d3/d3-selection#window) - 得到节点的所有者窗口。

### [修改元素](https://github.com/d3/d3-selection#modifying-elements)

* [*selection*.attr](https://github.com/d3/d3-selection#selection_attr) - 设置或获取特性。
* [*selection*.classed](https://github.com/d3/d3-selection#selection_classed) - 获取，添加或移除CSS类。
* [*selection*.style](https://github.com/d3/d3-selection#selection_style) - 设置或获取样式。
* [*selection*.property](https://github.com/d3/d3-selection#selection_property) - 设置或获取行内属性。
* [*selection*.text](https://github.com/d3/d3-selection#selection_text) - 设置或获取文本内容。
* [*selection*.html](https://github.com/d3/d3-selection#selection_html) - 设置或获取inner HTML。
* [*selection*.append](https://github.com/d3/d3-selection#selection_append) - 创建，添加或选择新的元素。
* [*selection*.remove](https://github.com/d3/d3-selection#selection_remove) - 移除文档中的元素。
* [*selection*.sort](https://github.com/d3/d3-selection#selection_sort) - 基于数据给文档中的元素排序。
* [*selection*.order](https://github.com/d3/d3-selection#selection_order) - 重排列文档中的元素以匹配选择中的顺序。
* [*selection*.raise](https://github.com/d3/d3-selection#selection_raise) - 重新排列每个元素为父元素的最后一个子节点。
* [*selection*.lower](https://github.com/d3/d3-selection#selection_lower) - 重新排列每个元素为父元素的第一个子节点。
* [d3.creator](https://github.com/d3/d3-selection#creator) - 通过名称创建元素。

### [数据绑定](https://github.com/d3/d3-selection#joining-data)

* [*selection*.data](https://github.com/d3/d3-selection#selection_data) - 元素和数据绑定。
* [*selection*.enter](https://github.com/d3/d3-selection#selection_enter) - 获得进入（enter）选择器（数据无元素）。
* [*selection*.exit](https://github.com/d3/d3-selection#selection_exit) - 获得退出（exit）选择器（元素无数据）。 
* [*selection*.datum](https://github.com/d3/d3-selection#selection_datum) - 获取或设置元素的数据（不绑定）。

### [事件处理](https://github.com/d3/d3-selection#handling-events)

* [*selection*.on](https://github.com/d3/d3-selection#selection_on) - 添加或移除事件监听器。
* [*selection*.dispatch](https://github.com/d3/d3-selection#selection_dispatch) - 分发自定义事件。
* [d3.event](https://github.com/d3/d3-selection#event) - 交互中的当前用户事件。
* [d3.customEvent](https://github.com/d3/d3-selection#customEvent) - 暂时定义一个自定义事件。
* [d3.mouse](https://github.com/d3/d3-selection#mouse) - 获取相对给定容器的鼠标位置。
* [d3.touch](https://github.com/d3/d3-selection#touch) - 获取相对给定容器的单点触控位置。
* [d3.touches](https://github.com/d3/d3-selection#touches) - 获取相对给定容器的多点触控位置。

### [控制语句](https://github.com/d3/d3-selection#control-flow)

* [*selection*.each](https://github.com/d3/d3-selection#selection_each) - 为每个元素调用一次指定的方法。
* [*selection*.call](https://github.com/d3/d3-selection#selection_call) - 选择器调用指定的方法。
* [*selection*.empty](https://github.com/d3/d3-selection#selection_empty) - 返回是否是空选择。
* [*selection*.nodes](https://github.com/d3/d3-selection#selection_nodes) - 返回所有选中元素的数组。
* [*selection*.node](https://github.com/d3/d3-selection#selection_node) - 返回第一个非空元素。
* [*selection*.size](https://github.com/d3/d3-selection#selection_size) - 返回元素数量。

### [命名空间](https://github.com/d3/d3-selection#namespaces)

* [d3.namespace](https://github.com/d3/d3-selection#namespace) - 限定XML命名空间，如“xlink:href "。
* [d3.namespaces](https://github.com/d3/d3-selection#namespaces) - 内置的XML命名空间。
