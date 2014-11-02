---
layout: post
categories: [reading]
title: "html5音视频测试"
tags: [音频, 视频, 日志]
video: true
---

### 测试一下音视频的发布

#### 视频

<video id="example_video_1" class="video-js vjs-default-skin" data-setup='{ "controls": true, "autoplay": false, "preload": "auto", "poster": "http://video-js.zencoder.com/oceans-clip.png", "width": "100%", "height": 264 }'>
 <source src="http://video-js.zencoder.com/oceans-clip.mp4" type='video/mp4' />
 <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
</video>

要想增加视频功能，请发布文章时在md文件的头部增加一行：
{% highlight html linenos %}
video: true
{% endhighlight %}

#### 音频
暂无
