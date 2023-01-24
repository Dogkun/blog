---
layout: page
title: About
description: 打码改变世界
keywords: 阿狗君的博客
comments: true
menu: 关于
permalink: /about/
---
欢迎来到阿狗君的小窝，欢迎你们来van~

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
