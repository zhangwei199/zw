# 计算器APP
>本项目是一个给用户提供计算、保存计算历史记录以及加入收藏夹功能的安卓软件。

>本项目分为3个活动页面，分别是计算器、历史记录和收藏夹页面。

>计算器界面布局，采用垂直线性布局；上方计算器的显示屏（TextView），字数超出可滚动，
中间嵌套网格布局（GridLayout）用于存放计算器的操作按钮（Button），
下方为跳转至历史记录页面的按钮。

>历史记录和收藏夹的界面布局，采用相对布局；布局中含有一个列表（ListView）和一个按钮，
列表的item中有图片（ImageView）和文本框（TextView）,使用SimpleAdapter适配器能适配列表的图片和文本的显示

>主要功能有:
>>实现加减乘除运算、连续运算、判断计算是否符合逻辑，<br>
自动将运算记录和当前时间存入数组，在历史记录页面显示，<br>
intent实现页面跳转，并用bundle传递数据，<br>
SimpleAdapter适配器适配列表的图片和文本的显示，<br>
列表控件长按事件，长按一条记录可存入收藏夹。<br>

> 想了解更多详情请观看本项目其他文档
## 运行效果图：
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/1.png)
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/2.png)
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/3.png)
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/4.png)
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/5.png)
![image](https://github.com/zhangwei199/Android_Calculator/raw/master/preview/6.png)

