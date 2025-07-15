---
title: "카테고리"
layout: archive
permalink: /categories/
author_profile: true
sidebar:
  nav: sidebar-categories # 1단계에서 만든 파일명 (확장자 제외)
---

{% include base_path %}
{% include group-by-array collection="posts" field="categories" %}