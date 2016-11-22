
## [集合](https://github.com/d3/d3-collection)

便捷的数据结构，元素的键是字符串类型。

#### [对象](https://github.com/d3/d3-collection#objects)

将对象转为数组的方法。

* [d3.keys](https://github.com/d3/d3-collection#keys) - 列举关联数组的键。
* [d3.values](https://github.com/d3/d3-collection#values) - 列举关联数组的值。
* [d3.entries](https://github.com/d3/d3-collection#entries) - 列举关联数组的键值对实体。

#### [映射](https://github.com/d3/d3-collection#maps)

类似ES6 Map，但是键时字符类型的，并且有点其他区别。

* [d3.map](https://github.com/d3/d3-collection#map) - 创建一个空的map。
* [*map*.has](https://github.com/d3/d3-collection#map_has) - 返回map中是否包含某个值。
* [*map*.get](https://github.com/d3/d3-collection#map_get) - 获取值。
* [*map*.set](https://github.com/d3/d3-collection#map_set) - 设置值。
* [*map*.remove](https://github.com/d3/d3-collection#map_remove) - 移除值。
* [*map*.clear](https://github.com/d3/d3-collection#map_clear) - 移除所有值。
* [*map*.keys](https://github.com/d3/d3-collection#map_keys) - 获取键数组。
* [*map*.values](https://github.com/d3/d3-collection#map_values) - 获取值数组。
* [*map*.entries](https://github.com/d3/d3-collection#map_entries) - 获取键值对数组。
* [*map*.each](https://github.com/d3/d3-collection#map_each) - 为每个元素调用一次指定的方法。
* [*map*.empty](https://github.com/d3/d3-collection#map_empty) - 返回map是否为空。
* [*map*.size](https://github.com/d3/d3-collection#map_size) - 计算值的数量。

#### [集合](https://github.com/d3/d3-collection#sets)

类似ES6 Set，但是键时字符类型的，并且有点其他区别。

* [d3.set](https://github.com/d3/d3-collection#set) - 创建一个空的set。
* [*set*.has](https://github.com/d3/d3-collection#set_has) - 返回set中是否包含某个值。
* [*set*.add](https://github.com/d3/d3-collection#set_add) - 添加指定值。
* [*set*.remove](https://github.com/d3/d3-collection#set_remove) - 删除指定值。
* [*set*.clear](https://github.com/d3/d3-collection#set_clear) - 移除所有值。
* [*set*.values](https://github.com/d3/d3-collection#set_values) - 获取值数组。
* [*set*.each](https://github.com/d3/d3-collection#set_each) - 为每个元素调用一次指定的方法。
* [*set*.empty](https://github.com/d3/d3-collection#set_empty) - 返回set是否为空。
* [*set*.size](https://github.com/d3/d3-collection#set_size) - 计算值的数量。

#### [嵌套](https://github.com/d3/d3-collection#nests)

将数据组织成任意层次。

* [d3.nest](https://github.com/d3/d3-collection#nest) - 创建一个嵌套生成器。
* [*nest*.key](https://github.com/d3/d3-collection#nest_key) - 在嵌套层级中加一级。
* [*nest*.sortKeys](https://github.com/d3/d3-collection#nest_sortKeys) - 当前层级按键排序。
* [*nest*.sortValues](https://github.com/d3/d3-collection#nest_sortValues) - 叶子层级按值排序。
* [*nest*.rollup](https://github.com/d3/d3-collection#nest_rollup) -为叶子层指定汇总函数。
* [*nest*.map](https://github.com/d3/d3-collection#nest_map) - 生成一个嵌套，返回一个map。
* [*nest*.object](https://github.com/d3/d3-collection#nest_object) - 生成一个嵌套，返回一个关联数组。
* [*nest*.entries](https://github.com/d3/d3-collection#nest_entries) - 生成一个嵌套，返回一个键值对数组。


