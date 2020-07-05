# web-components-demo
相比于react和vue等第三方框架，web-components原生框架更直接，符合直觉，
不用加载任何外部模块，代码量小。

### 一、 自定义元素
根据规范，自定义的元素的名称必须包含连词线
```html
<baidu-know></baidu-know>
```

### 二、customElements.define()
将元素和类相连

### 三、template 
用js创建元素的方式写起来特别麻烦，web components 提供了template，
可以在里面用html定义DOM

### 四、添加样式
1、可以给自定义元素提供全局样式
```css
    baidu-know{
        /* 样式内容 */
    }
```
2、写在template里面，不影响全局，只对自定义元素生效

### 五、自定义元素的参数
可以利用参数来改变元素内容

### 六、自定义事件
可以添加各种监听事件

### 七、template注入
可以将template写在js文件中，然后注入网页



