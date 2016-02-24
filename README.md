## 原生JS实现CSS样式的get与set，兼容主流浏览器与 IE678

### 初始化方法
###### 1) 提供 var cc = new CC() 构造函数，构建 cssControl 实例，然后 cc.getStyle(elem, style) 调用
###### 2) 或者直接 CC().getStyle(elem, style) 进行调用

### 核心方法
###### 1) getStyle(elem, style) -- 用于获取结点为 elem 的 style 样式
###### 2) setStyle(elem, style, value) -- 用于设置结点为 elem 的 style 样式为 value 

## 博客园相关blog 
[【CSS进阶】原生JS getComputedStyle等方法解析](http://www.cnblogs.com/coco1s/p/5210667.html)
 
 
