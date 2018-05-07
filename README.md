# svg-wave
Wave animation.

svg的波浪动画。

![image](https://raw.githubusercontent.com/CODE-FOR-INTEREST/svg-wave/master/demo.gif)

## 实现

### 一，依赖[d3.js](https://d3js.org/)
见demo.html

### 二，无依赖，运算更简单，性能更好（2017-11-23更新）
利用path绘制贝塞尔曲线，仅改变贝塞尔曲线的起点既能实现移动（波动）效果，运算量极小。

见demo2.html