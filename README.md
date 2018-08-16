# radial-gradient-and-cubic-bezier
径向渐变、矩阵与贝塞尔曲线


线性渐变（linear-gradient）与径向渐变（radial-gradient）
https://www.zhangxinxu.com/wordpress/2017/11/css3-radial-gradient-syntax-example/
linear-gradient线性渐变，它控制的是背景容器直线平面的渐变
radial-gradient径向渐变控制的是背景容器曲线平面的渐变
它们的语法相似

语法：
radial-gradient(
    <shape>,
    <range>,
    <position>,
    <color-stop>
)
其中 
<shape>：渐变形状； 
<range>：渐变范围； 
<position>：渐变中心点； 
<color-stop>：渐变颜色分布
  
CSS3中的矩阵
书写为matrix()和matrix3d()，前者是元素2D平面的移动变换(transform)，后者则是3D变换。2D变换矩阵为3*3；3D变换则是4*4的矩阵。其默认是绕着中心点旋转的，而这个中心点就是transform-origin属性对应的点


贝塞尔曲线cubic-bezier（）
cubic-bezier 又称三次贝塞尔，主要是为 animation 生成速度曲线的函数，是 animation-timing-function 和 transition-timing-function 中的一个重要值。
语法：
cubic-bezier(x1,y1,x2,y2)
http://cubic-bezier.com贝塞尔曲线在线制作工具
