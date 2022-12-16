# BXC_RtspServer_study
@author 北小菜 https://space.bilibili.com/487906612

## 本次实战项目系列视频，分为如下5个：
1. 从零开始编写一个RTSP服务器（1）RTSP协议讲解及代码实现 [BiliBili视频教程地址](https://www.bilibili.com/video/BV1xd4y147Fb) 
2. 从零开始编写一个RTSP服务器（2）实现一个基于UDP的RTP传输h264的RTSP服务器，并能够进行rtsp拉流播放 [BiliBili视频教程地址](https://www.bilibili.com/video/BV18P4y1X78w) 
3. 从零开始编写一个RTSP服务器（3）实现一个基于UDP的RTP传输aac的RTSP服务器，并能够进行rtsp拉流播放 [BiliBili视频教程地址](https://www.bilibili.com/video/BV1P44y1U7F1) 
4. 从零开始编写一个RTSP服务器（4）实现一个基于TCP的RTP同时传输h264和aac的RTSP服务器，并能够进行rtsp拉流播放
5. 从零开始编写一个RTSP服务器（5） 基于我的开源项目BXC_RtspServer进行详细的源码讲解，这是一个完整可用，支持多线程，基于socket编写的IO多路复用的RTSP流媒体服务器

### windows系统编译运行
~~~
只需要使用vs2019打开 BXC_RtspServer_study.sln
选择 x64/Debug 或 x64/Release都能够直接运行，没有任何第三方依赖库
vs2017,vs2022 没有试，应该都没有问题
 
~~~

### 为什么要讲这个系列？
~~~
因为我自己在入行C++音视频开发时，首先就是学习的rtsp协议。但由于rtsp比较复杂，
当时在网上也看了许多相关文章，或模棱两可，或复制粘贴，即便时至今日，网上的资料也是大抵如此。
所以想录制这样一个系列，来帮助想要入行音视频开发的朋友。
（补充一点：这个系列不仅仅能够帮助到使用C++开发的朋友，其他编程语言的开发者也可以参考和学习RTSP服务器的实现思路）
~~~

### 这个系列适合那些人？
~~~
对音视频开发感兴趣的，有一定编程基础的，或想要转行音视频开发的其他开发岗，
想要了解RTSP协议交互逻辑的，或学生，或程序员，或其他相关行业的岗位。
~~~




