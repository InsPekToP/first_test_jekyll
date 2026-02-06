---
layout: post
title: Video
video: /assets/video/L2jMobius_first_Server.mp4
---

Какой-то текст видео


{% if page.video %}
  <video controls width="100%">
    <source src="{{ page.video | relative_url }}" type="video/mp4">
  </video>
{% endif %}

