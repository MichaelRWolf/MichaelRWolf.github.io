---
layout: default
title: Welcome
---

# Welcome to My Site

- [/blog](/blog)
- [blog](blog)
- [blog.md](blog.md)
- [blog.htm](blog.html)


# Welcome again

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
