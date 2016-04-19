---
layout: page
title: Race Reports and Announcements
permalink: /news/
---

![reports](../images/reports.jpg)

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
  <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
  <div class="preview">
        {{ post.excerpt }}
      </div>
  <pre><code>  &lt;a href="{{ site.baseurl }}{{ post.url }}" class="read-more"&gt;Read More&lt;/a&gt;
&lt;/article&gt;
</code></pre>
  <p>  {% endfor %}
</p>
</article></div>
