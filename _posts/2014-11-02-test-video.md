---
layout: post
categories: [reading]
title: "html5音视频测试"
tags: [音频, 视频, 日志]
video: true
audio: true
---

### 测试一下音视频的发布

#### 视频

<video id="example_video_1" class="video-js vjs-default-skin" data-setup='{ "controls": true, "autoplay": false, "preload": "auto", "poster": "http://video-js.zencoder.com/oceans-clip.png", "width": "100%", "height": 264 }'>
 <source src="http://video-js.zencoder.com/oceans-clip.mp4" type='video/mp4' />
 <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
</video>

要想增加视频功能，请发布文章时在md文件的头部增加一行：

```
video: true
```

然后在需要添加视频的地方增加视频代码：

{% highlight html linenos %}
<video id="视频id" class="video-js vjs-default-skin" data-setup='{ "controls": true, "autoplay": false, "preload": "auto", "poster": "http://video-js.zencoder.com/oceans-clip.png", "width": "100%", "height": <视频的高度，数字表示> }'>
 <source src="视频地址" type='video/mp4' />
 <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
</video>
{% endhighlight %}

#### 音频

<audio preload="auto" controls>
		<source src="http://osvaldas.info/examples/audio-player-responsive-and-touch-friendly/audio.mp3" />
</audio>

要想增加音频功能，请发布文章时在md文件的头部增加一行：

```
audio: true
```

然后在需要添加音频的地方增加音频代码：

{% highlight html linenos %}
<audio preload="auto" controls>
		<source src="音频地址" />
</audio>
{% endhighlight %}

