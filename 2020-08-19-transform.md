想要实现朋友圈的图片查看效果，经实验得出用 `transform` 里面的 matrix 变化图片会比较理想。然后就开始探索啦。先从种地（线性代数）开始吧。
经过一番研究得出 `AX=X'` 这样的结果，但是呢计算出来的坐标飞到外太空了。那么问题在哪里呢，尽管是第一次种地，但是辛勤是不会欺骗自己的。所以，“会不会是坐标系的问题呢？”，带着这样的疑问，终于挖到了这个属性 `transform-origin`， 定义坐标轴的东西。给老子一种真相只有一个的错觉...
那么所有的点都梳理清楚了，接下来就是如何得出变换矩阵了，待续。

> [https://dev.opera.com/articles/understanding-the-css-transforms-matrix/](https://dev.opera.com/articles/understanding-the-css-transforms-matrix/)

> [https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function)
