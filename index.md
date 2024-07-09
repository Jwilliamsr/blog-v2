---
layout: home
title: "Home"
---

<div class="intro">
  <h2>Welcome to My Awesome Blog</h2>
  <p>This is the greatest blog on the planet.</p>
</div>

<div class="posts">
  <h3>Recent Posts</h3>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>
</div>
