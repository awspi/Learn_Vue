## v-bind的绑定属性

前端讲的一系列指令，主要是将值插入到模板内容中。

但是，除了内容需要动态来决定外，某些属性我们也希望动态来绑定。 

比如动态绑定a元素的href属性

比如动态绑定img元素的src属性

------

**绑定属性我们使用v-bind：** 

**缩写**：: 

**预期**：any (with argument) | Object (without argument) 

**参数**：attrOrProp (optional) 

**修饰符**： camel - 将 kebab-case attribute 名转换为 camelCase。 

**用法**：动态地绑定一个或多个 attribute，或一个组件 prop 到表达式。

------

------

**绑定基本属性**

v-bind用于绑定一个或多个属性值，或者向另一个组件传递props值（这个学到组件时再介绍）； 

有哪些属性需要动态进行绑定呢？ 

比如图片的链接src、网站的链接href、动态绑定一些类、样式等等

v-bind有一个对应的**语法糖**，也就是简写方式。 在开发中，我们通常会使用语法糖的形式，因为这样更加简洁。