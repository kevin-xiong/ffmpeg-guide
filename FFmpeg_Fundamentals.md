###1。FFmpeg基础  
&nbsp;&nbsp;&nbsp;&nbsp;用最适当的的FFmpeg组件对于理解基本概念和特性有很大帮助。如果开始觉得太专业化,你可以先读下一章,之后再回头阅读。  
####FFmpeg的介绍  
&nbsp;&nbsp;&nbsp;&nbsp;FFmpeg是一个处理多媒体的自由软件项目的名称，使用GNU的许可证。  
&nbsp;&nbsp;&nbsp;&nbsp;其中被使用最多的是用来对视频和音频编码/解码的ffmpeg命令行工具，主要特点是高速、高质量的输出和文件小。  
&nbsp;&nbsp;&nbsp;&nbsp;FFmpeg中的'FF'意味着快进-媒体播放器上的控制按钮,“mpeg”是动态图像专家组的缩写。  
&nbsp;&nbsp;&nbsp;&nbsp;FFmpeg的logo包含了一个模式提取,图中是以8×8的矩阵来表示熵编码。

| FFmpeg 命令行工具  | | 
| ------------- |:-------------:| 
| ffmpeg      | 音频和视频的快速 编码/解码 | 
| ffplay      | 媒体播放器      |
| ffprobe | 展示文件的特性     |
| ffserver | 使用HTTP和RTSP协议的流媒体的广播服务     |

| FFmpeg 类库  | | 
| ------------- |:-------------:| 
| libavcodec      | 多种媒体解码类库 | 
| libavdevice      | 多媒体设备交互的类库      |
| libavfilter | 滤镜类库     |
| libavformat | 格式化流媒体类库    |
| libavutil | 包含很多实用程序的类库    |
| libpostproc | 后加工类库    |
| libswresample | 用来音频重新采样的类库    |
| libswscale | 用来对流媒体转化/缩放的类库    |  

&nbsp;&nbsp;&nbsp;&nbsp;所有组件都是C语言实现的，源代码可以在Linux/Unix/Windows/Mac OS X等系统上编译通过,
本书内容是在Windows上使用官方二进制构建的,但几乎所有指令和例子都无需任何修改就可以运行在其他操作系统。  
&nbsp;&nbsp;&nbsp;&nbsp;请参见FFmpeg术语表中的配置条目的详细信息选项。








