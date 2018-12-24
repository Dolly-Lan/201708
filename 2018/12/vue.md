### 修饰符

#### .stop

阻止事件冒泡

    <div @click="test">
      <a @click.stop="doThis"></a>
    </div>

#### .trim

自动过滤用户输入的首尾空白字符

    <input v-model.trim="msg">

### render(createElement)

[官方文档](https://cn.vuejs.org/v2/guide/render-function.html)

类似template的编译器

#### createElement参数

[官方文档](https://cn.vuejs.org/v2/guide/render-function.html#createElement-参数)

createElement(tag, data, node) 函数返回VNode（虚拟节点），并非返回真实DOM