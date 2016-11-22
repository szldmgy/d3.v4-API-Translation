
## [力导向图](https://github.com/d3/d3-force)

力导向图使用velocity Verlet整合算法实现。

* [d3.forceSimulation](https://github.com/d3/d3-force#forceSimulation) - 创建一个力模拟。
* [*simulation*.restart](https://github.com/d3/d3-force#simulation_restart) - 重启力模拟。
* [*simulation*.stop](https://github.com/d3/d3-force#simulation_stop) - 停止力模拟。
* [*simulation*.tick](https://github.com/d3/d3-force#simulation_tick) - 将力模拟向前推进一步。
* [*simulation*.nodes](https://github.com/d3/d3-force#simulation_nodes) - 设置力模拟的节点。
* [*simulation*.alpha](https://github.com/d3/d3-force#simulation_alpha) - 设置当前的`α`值。
* [*simulation*.alphaMin](https://github.com/d3/d3-force#simulation_alphaMin) -设置`α`最小阈值。
* [*simulation*.alphaDecay](https://github.com/d3/d3-force#simulation_alphaDecay) - 设置`α`指数衰减率。
* [*simulation*.alphaTarget](https://github.com/d3/d3-force#simulation_alphaTarget) - 设置目标`α`。
* [*simulation*.drag](https://github.com/d3/d3-force#simulation_drag) - 设置曳引系数。
* [*simulation*.force](https://github.com/d3/d3-force#simulation_force) - 添加或移除力。
* [*simulation*.fix](https://github.com/d3/d3-force#simulation_fix) - 固定节点位置。
* [*simulation*.unfix](https://github.com/d3/d3-force#simulation_unfix) - 释放固定的节点。
* [*simulation*.find](https://github.com/d3/d3-force#simulation_find) - 查找给定位置最近的节点。
* [*simulation*.on](https://github.com/d3/d3-force#simulation_on) - 添加或移除事件监听器。
* [*force*](https://github.com/d3/d3-force#_force) - 应用力模拟。
* [*force*.initialize](https://github.com/d3/d3-force#force_initialize) - 使用给定的节点初始化力布局。
* [d3.forceCenter](https://github.com/d3/d3-force#forceCenter) - 创建一个力中心。
* [*center*.x](https://github.com/d3/d3-force#center_x) - 设置中心的*x*-坐标。
* [*center*.y](https://github.com/d3/d3-force#center_y) - 设置中心的*y*-坐标。
* [d3.forceCollide](https://github.com/d3/d3-force#forceCollide) - 创建一个圆碰撞力。
* [*collide*.radius](https://github.com/d3/d3-force#collide_radius) - 设置圆的半径。
* [*collide*.strength](https://github.com/d3/d3-force#collide_strength) - 设置碰撞检测强度。
* [*collide*.iterations](https://github.com/d3/d3-force#collide_iterations) - 设置迭代次数。
* [d3.forceLink](https://github.com/d3/d3-force#forceLink) - 创建连接力。
* [*link*.links](https://github.com/d3/d3-force#link_links) - 设置连接数组。
* [*link*.id](https://github.com/d3/d3-force#link_id) - 连接数组。
* [*link*.distance](https://github.com/d3/d3-force#link_distance) - 设置连接距离。
* [*link*.strength](https://github.com/d3/d3-force#link_strength) - 设置连接强度。
* [*link*.iterations](https://github.com/d3/d3-force#link_iterations) - 设置迭代次数。
* [d3.forceManyBody](https://github.com/d3/d3-force#forceManyBody) - 创建多体力。
* [*manyBody*.strength](https://github.com/d3/d3-force#manyBody_strength) - 设置力强度。
* [*manyBody*.theta](https://github.com/d3/d3-force#manyBody_theta) - 设置Barnes-Hut近似精度。
* [*manyBody*.distanceMin](https://github.com/d3/d3-force#manyBody_distanceMin) - 当节点关闭限制力。
* [*manyBody*.distanceMax](https://github.com/d3/d3-force#manyBody_distanceMax) - 当节点太远限制力。
* [d3.forceX](https://github.com/d3/d3-force#forceX) - 创建*x*-定位力。
* [*x*.strength](https://github.com/d3/d3-force#x_strength) - 设置力强度。
* [*x*.x](https://github.com/d3/d3-force#x_x) - 设置目标*x*-坐标。
* [d3.forceY](https://github.com/d3/d3-force#forceY) - 创建*y*-定位力。
* [*y*.strength](https://github.com/d3/d3-force#y_strength) - 设置力强度。
* [*y*.y](https://github.com/d3/d3-force#y_y) - 设置目标*y*-坐标。
