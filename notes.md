## section标签
    语义标签，独立的一块

## css
1、box-sizing: border-box;
    设置的边框和内边距的值是包含在width内的。
    border-box不包含margin
2、-webkit-user-drag: none;
    设置用户无法拖拽页面的东西
3、CSS中的px、em、rem三种单位的关系
    px：绝对单位，1个单位的px在不同设备上表示是有区别的；有的设备几个颜色点表示1个像素单位。
    em：是font-size的倍数；当然font-size的值也有几种情况。
    rem：是相对于根元素html的font-size来计算的。
4、:root    
    伪类匹配文档树的根元素，相当于<html>，但优先级更高；
    声明全局 CSS 变量时 :root 会很有用：
    例如    :root {
                --main-color: hotpink;
                --pane-padding: 5px 42px;
            }
5、user-select: none;
    设置页面字不可选
6、display: inline-block;
    与 display: inline 相比，主要区别在于 display: inline-block 允许在元素上设置宽度和高度。
7、filter:invert(1);
    CSS属性 filter 将模糊或颜色偏移等图形效果应用于元素。滤镜通常用于调整图像、背景和边框的渲染。
    invert() 函数反转输入图像。amount 的值定义转换的比例。值为 100% 则图像完全反转。
8、transition: 0.5s;
    过渡效果，一个元素在不同状态之间切换的时候定义不同的过渡效果。
9、<video src="" autoplay muted loop></video>
    muted 静音
    loop 循环播放
10、clip-path: ellipse(0% 0% at 0% 50%);
    使用裁剪方式创建元素的可显示区域。区域内的部分显示，区域外的隐藏。
    ellipse(0% 0% at 0% 50%)
    定义一个椭圆（使用两个半径和一个圆心位置）。
        示例：
            .main-structure .content video{
                object-fit: cover;
                clip-path: ellipse(0% 0% at 0% 50%);
                padding: 0;
                margin: 0;
            }
            .main-structure .content video.active{
                clip-path: ellipse(150% 70% at 0% 50%);
            }

11、animation: menu_logo ease-in 1s infinite;

12、overflow: hidden;





