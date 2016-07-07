# PSWithJava
数字图像处理期末作业
#主要界面
##启动界面
仿照PS CC 2015启动界面
![Alt text](https://raw.githubusercontent.com/jacobba/PSWithJava/master/screenshots/5.png)
##主界面
![Alt text](https://raw.githubusercontent.com/jacobba/PSWithJava/master/screenshots/4.png)
##图像混合界面
![Alt text](https://raw.githubusercontent.com/jacobba/PSWithJava/master/screenshots/3.png)
##直方图查看界面
![Alt text](https://raw.githubusercontent.com/jacobba/PSWithJava/master/screenshots/2.png)
##边缘提取界面
![Alt text](https://raw.githubusercontent.com/jacobba/PSWithJava/master/screenshots/1.png)
#主要功能
##主界面功能
###菜单栏功能
####文件
- 打开：打开图像
- 保存：保存图像

####编辑
- 重置图像：把图像还原为初始状态
- 图像反转：负片效果，反转图像颜色
- 图像混合：打开图像混合界面


####缩放
- 最近邻内插法：运用最近邻内插法进行缩放，弹出小窗口可以输入缩放系数。0-1为缩小，1以上是放大。
- 双线性内插法：运用双线性内插法进行缩放，弹出小窗口可以输入缩放系数。0-1为缩小，1以上是放大。


####旋转
- 最近邻内插法：运用最近邻内插法进行旋转，弹出小窗口可以输入旋转角度,大于360度也可以，会自动计算最小旋转角度。
- 双线性内插法：运用双线性内插法进行缩放，弹出小窗口可以输入旋转角度,大于360度也可以，会自动计算最小旋转角度。


####变换
- 灰度拉伸：把图像灰度范围拉伸为0-255，不仅可以拉伸灰度，对彩色图像RGB三色也适用，不过彩色图像拉伸后失真。
- RGB 2 GRAY：把RGB彩色图像转换为灰度图像。
- Gamma变换：进行Gamma变换，可以输入参数。效果不好

####查看
- 图像直方图：打开图像直方图界面。
- 直方图均衡化(RGB)：进行图像直方图均衡化的操作。

####滤波器
- 均值滤波器：运用均值滤波器进行图像处理。
- 中值滤波器：运用中值滤波器进行图像处理。
- 加权均值滤波器：运用加权均值滤波器进行图像处理，效果不好。
- 图像边缘提取：打开图像边缘提取界面。
- 拉普拉斯滤波器：运用拉普拉斯算子进行图像处理，效果不好。

###其他功能
- 退出询问是否退出。
- 主界面自使用屏幕分辨率，在屏幕中心启动。
- 打开图像不是有效图像文件时进行提示。
- 打开图像有四种后缀名过滤器：all,jpg,png,bmp
- 保存图像时自动加后缀名jpg。

##图像混合界面功能
- 可以实时预览混合效果。
- 可以调整混合图片在底层图片的位置，可以用鼠标进行拖拽。
- 可以通过鼠标选取需要扣去的背景颜色，并且可以调整抠图的阈值。

##边缘提取界面功能
- 可以实施预览边缘提取的四种算子效果。
- 可以调整边缘提取的阈值。
- 可以保存四种算子效果图。


##图像直方图界面功能
- 可以查看图像灰度、红色、绿色、蓝色直方图。

#问题与不足
- 拉普拉斯滤波器现在看不出效果。
- 加权中值滤波器和Gamma变换效果异常。
- 边缘提取的效果图不是那种用白线显示轮廓，而是背景为黑色，前景为白色。
- 图像混合时如果选取分辨率太大的图像可能会报错。


#致谢
纪秀花

#License

MIT License
