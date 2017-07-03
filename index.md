---
layout: default.html
title: John Brumbaugh's Blog
---
# JohnBrumbaugh.GitHub.IO
  {% for post in site.posts %}
      {{ post.date | date_to_string }} » [{{ post.title }}]({{ post.url}})
      {{ post.content }}
  {% endfor %}
