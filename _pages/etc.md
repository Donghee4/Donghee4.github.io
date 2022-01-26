---
title: "etc"
layout: archive
permalink: /etc/ #categories/etc
author_profile: true
sidebar_main: true
---

### 카테고리 추가 예정 ###

{% assign posts = site.etc %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}