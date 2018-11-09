---
layout: page
title: About Me
description: hhdy
keywords: hhdy
comments: true
menu: 关于
permalink: /about/
---


## 说明

考研 

闭关修炼中

自己选择的路，再艰难，跪着也要走下去

---

## 个人介绍

蒻鶸一只，对嵌入式开发，算法，网络安全，机器学习有着极大的兴趣

<center>
<img src="/res/img/aboutme/myself.jpg" width="35%" height="35%" />
</center>

---

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

## 友情链接

{% for link in site.data.links %}
* [{{ link.name }}]({{ link.url }})
{% endfor %}
