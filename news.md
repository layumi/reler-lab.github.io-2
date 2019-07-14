---
title: News
permalink: /news/
---

### **Lab News**

<div class="list-item">
<p class="list-post-title">
<small>Congrats to Xuanyi to be one of the 2019 Google PhD Fellows.</small>
</p>
</div>

<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains 'blog' %}
    <div class="list-item">
    <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a> (<small>{{post.date | date: "%m/%d/%y" }}</small>)
        </p>
    </div>
    {% endif %}
  {% endfor %}
</div>
