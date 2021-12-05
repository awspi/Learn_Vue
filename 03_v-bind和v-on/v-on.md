**在前端开发中，我们需要经常和用户进行各种各样的交互：**

p这个时候，我们就必须监听用户发生的事件，比如点击、拖拽、键盘事件等等

p在Vue中如何监听事件呢？使用v-on指令。

**v-on的用法**

n **v-on的使用：**

**缩写**：@ 

**预期**：Function | Inline Statement | Object

! 目的是绑定不是为了调用函数，所以不需要加（）

**参数**：event

**修饰符**： 

stop - 调用 event.stopPropagation()。 

prevent - 调用 event.preventDefault()。 

capture - 添加事件侦听器时使用 capture 模式。

self - 只当事件是从侦听器绑定的元素本身触发时才触发回调。

{keyAlias} - 仅当事件是从特定键触发时才触发回调。

once - 只触发一次回调。

left - 只当点击鼠标左键时触发。

right - 只当点击鼠标右键时触发。

middle - 只当点击鼠标中键时触发。

passive - { passive: true } 模式添加侦听器

**用法**：绑定事件监听