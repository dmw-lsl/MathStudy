# YouTube视频下载教程

## 一、yt-dlp

下载地址： https://github.com/yt-dlp/yt-dlp

下载好后，将`yt-dlp.exe`文件直接拖拽到需要下载视频的文件夹中，在搜索栏输入`cmd`回车

然后输入 yt-dlp.exe "视频地址"即可下载。默认最高画质webm.



## 二、ffmpeg

命令格式：

```
 ffmpeg -i [输入文件名] [参数选项] -f [格式] [输出文件]
    ffmpeg [[options][`-i' input_file]]... {[options] output_file}...
    (1) h264: 表示输出的是h264的视频裸流
    (2) mp4: 表示输出的是mp4的视频
    (3)mpegts: 表示ts视频流
```

主要参数：

```
    -i 设定输入流    
    -f 设定输出格式
    -ss 开始时间
    视频参数：
    -b 设定视频流量，默认为200Kbit/s
    -r 设定帧速率，默认为25
    -s 设定画面的宽与高
    -aspect 设定画面的比例
    -vn 不处理视频
    -vcodec 设定视频编解码器，未设定时则使用与输入流相同的编解码器，一般后面加copy表示拷贝
```

webm格式文件转mp4文件

```
ffmpeg -i video.webm -crf 17 -c:v libx264 video.mp4
```

