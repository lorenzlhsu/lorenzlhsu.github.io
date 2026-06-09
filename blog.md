---
layout: default
title: Blog
---

It is my pleasure to share my technical reviews and perspectives toward chemical biology<br>
<a href="https://junction715.substack.com/?utm_campaign=profile_chips" target="_blank" style="color: #333; text-decoration: underline;"><strong><em>Link to my blog</em></strong></a>



{% for post in site.posts %}

  {{ post.date | date: "%b %d, %Y" }}
  {{ post.title }}

{% endfor %}
