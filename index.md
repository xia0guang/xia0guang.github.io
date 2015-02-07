---
layout: default
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    {{ post.excerpt }}

    <a href="{{ BASE_PATH }}{{ post.url }}">More » </a>
    </li>
  {% endfor %}
</ul>


