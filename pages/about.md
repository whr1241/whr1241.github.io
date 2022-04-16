---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

思考的快乐是人类生命的意义所在，善待自己是维持自我的方法。

学而思，思而行，行而省，省而学，环环相扣，缺一不可。

信息传递是有一定滞后性的，永远去关注去探索最新的信息，才能站在风口浪尖把握方向。

记忆的高效性是以理解为基础的。

把娱乐的时间用来冥想，
把懒散的时间用来运动，
把独处的时间用来读书，
把热闹的环境用来交际。

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ assets_base_url }}/assets/images/qrcode.jpg" alt="闷骚的程序员" />
</li>
{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
