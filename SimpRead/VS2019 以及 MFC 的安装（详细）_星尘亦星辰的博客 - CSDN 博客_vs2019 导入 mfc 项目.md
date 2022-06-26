> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/Mrweng1996/article/details/103202297)

注：

考虑到网友的评论，若出现 MSB8041 错误，请参照：[https://blog.csdn.net/evan369/article/details/100150685](https://blog.csdn.net/evan369/article/details/100150685)

若出现：c2065 未声明的标识符，请参照：[https://blog.csdn.net/whbo111/article/details/52232123](https://blog.csdn.net/whbo111/article/details/52232123)

一：安装过程：
-------

### 1、搜索 visual studio 进入官网。

![](https://img-blog.csdnimg.cn/20191122155430159.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 2、选择 community 2019 下载。

![](https://img-blog.csdnimg.cn/20191122155430212.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 3、现在完成后点击安装，等待安装完成

![](https://img-blog.csdnimg.cn/20191122155430213.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 4、自动弹出一下界面，工作负载这里勾选使用 C++ 的桌面开发和 Visual Studio 扩展开发。另外，在使用 C++ 的桌面开发选中后的右侧安装详细信息栏中勾选适用于最新的 v142 生成工具的 C++MFC（x86 和 x64）这一项。选中后点击安装。（一共勾选 3 个地方，如下图）

![](https://img-blog.csdnimg.cn/20191124110758830.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

 ![](https://img-blog.csdnimg.cn/20191124111155363.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 5、等待下载安装完成

![](https://img-blog.csdnimg.cn/20191124111750419.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 6、安装完成后重启，于下图中找到 visual studio 2019 打开文件位置，发送到桌面快捷方式，安装完成。

![](https://img-blog.csdnimg.cn/20191124111817428.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

二：验证是否安装正确
----------

### 1、点击 vs 图标进入界面，直接搜索 mfc，选中 MFC 应用。

![](https://img-blog.csdnimg.cn/20191124111908699.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 2、点击下一步，名称随意，位置最好自己选个能找到的（方便删除），并点击创建。

![](https://img-blog.csdnimg.cn/20191124111937788.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 3、在应用程序类型这一项选择**基于对话框**。其他的别动，点击完成。

![](https://img-blog.csdnimg.cn/20191124111955254.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

### 4、直接点击 Ctrl+F5，或者在调试窗口中点击**开始执行**选项。若未报错直接弹出最后一图对话框则安装成功。

![](https://img-blog.csdnimg.cn/20191124112021778.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)

![](https://img-blog.csdnimg.cn/20191124112053774.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yd2VuZzE5OTY=,size_16,color_FFFFFF,t_70)