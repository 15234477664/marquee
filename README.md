# marquee标签实现跑马灯效果--无缝滚动

## 一、marquee标签的几个重要属性：
```html
1.direction：滚动方向(包括4个值：up、down、left、right)

说明：up：从下向上滚动；down：从上向下滚动；left：从右向左滚动；right：从左向右滚动。

语法：<marquee direction="滚动方向">...</marquee>

2.behavior：滚动方式(包括3个值：scroll、slide、alternate)

说明：scroll：循环滚动，默认效果；slide：只滚动一次就停止；alternate：来回交替进行滚动。

语法：<marquee behavior="滚动方式">...</marquee>

3.scrollamount：滚动速度(滚动速度是设置每次滚动时移动的长度，以像素为单位)

语法：<marquee scrollamount="5">...</marquee>

4.scrolldelay:设定滚动两次之间的延迟时间，值大了会有一步一停顿的效果(设置滚动的时间间隔，单位是毫秒)

语法：<marquee scrolldelay="100">...</marquee>

5.loop：设定滚动循环的次数(默认值是-1，滚动会不断的循环下去)

语法：<marquee loop="2">...</marquee>                        

 <marquee loop="-1" bgcolor="#CCCCCC">我会不停地走。</marquee>

 <marquee loop="2" bgcolor="#CCCCCC">我只走两次哦</marquee>

6.width、height：设定滚动字幕的宽度、高度

语法：<marquee width="500" height="200">...</marquee>

7.bgcolor：设定滚动字幕的背景颜色(可以是颜色值，也可以是rgb()或rgba()函数)

语法：<marquee bgcolor="rgba(0,0,0,0.2)">...</marquee>

8.hspace、vspace：空白空间(相当于设置margin值)

 说明：hspace：设定活动字幕里所在的位置距离父容器水平边框的距离，如hspace=“10”，即等同于：margin：0 10px；

 vspace：设定活动字幕里所在的位置距离父容器垂直边框的距离，如vspace=“10”，即等同于：margin：10px 0；

 语法：<marquee hspace="10"  vspace="10">...</marquee>(等同于：margin：10px；)

9.align：设定滚动字幕内容的对齐方式(包括9个值：absbottom、absmiddle、baseline、bottom、left、middle、right、                                  texttop、top)

说明：absbottom：绝对底部对齐（与g、p等字母的最下端对齐）
      absmiddle：绝对中央对齐
      baseline：底线对齐
      bottom：底部对齐（默认）
      left：左对齐
      middle：中间对齐
      right：右对齐
      texttop：顶线对齐
      top：顶部对齐
语法：<marquee align="对齐方式">...</marquee>

10.face：设定滚动字幕的文字字体

语法：<marquee font="楷体_GB2312"></marquee>

11.color：设定滚动字幕的文字颜色

语法：<marquee color="#333"></marquee>

12.size：设定滚动字幕的文字字号

语法：<marquee size="3"></marquee>

13.STRONG：设定滚动字幕的文字加粗

语法：<marquee STRONG></marquee>
```
