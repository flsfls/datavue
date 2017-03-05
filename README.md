# 数据可视化

> 将数据通过图表的形式展现出来将大大的提升可读性和阅读效率

> 本例包含柱状图、折线图、散点图、热力图、复杂柱状图、预览面板等


# 技术栈

- vue2.x
- vuex _存储公共变量，如色值等_
- vue-router _路由_
- element-ui _饿了么基于vue2开发组件库，本例使用了其中的datePicker_
- echarts _一款丰富的图表库_
- webpack、ES6、Babel、Stylus...

# 演示

<div align=center style="margin-top:30px">此项目为PC端数据可视化，请在电脑端查看</div>
<div align=center><a href="https://flsfls.github.io/datavue" target=_blank>在线演示戳我</a></div>



整体的思想为：

- 使用百分比布局，这样才能在不能大小的屏幕做到自适应
- 确定图表显示比例，长宽比
- 只做一个transform变换，这样才能提高性能



## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8081
npm run dev

# build for production with minification
npm run build
```



