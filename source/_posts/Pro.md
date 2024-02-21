---
layout: share
title: My Portfolio Share
tags:


---



## 内容视频作品：

{% for i in range(1, 16) %}

 <video width="360" height="240" controls style="margin: 0 auto;">
  <source src="https://raw.githubusercontent.com/Laihiujin/Laihiujin.github.io/master/source/videos/A/A{{ i }}.MP4" type="video/mp4">
  您的浏览器不支持视频标签。
</video>



{% endfor %}



## 品宣视频作品：



{% for i in range(1, 5) %}

<video width="360" height="240" controls>
  <source src="https://raw.githubusercontent.com/Laihiujin/Laihiujin.github.io/master/source/videos/P/P{{ i }}.MP4" type="video/mp4">
  您的浏览器不支持视频标签。
</video>



{% endfor %}

