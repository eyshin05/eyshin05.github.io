---
layout: post
title:  "Disqus Test"
date:   2020-07-03 15:07:00 +0900
comments: true
categories: blog settings
---

깃헙 블로그를 셋업한 기념으로 Disqus 설치해보았습니다.

잘 작동하는지 확인하기 위해 포스트를 올려봅니다.

{% if site.disqus.shortname %}
  {% include disqus_comments.html %}
{% endif %}
