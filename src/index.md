---
title: My first page - Azzam
layout: base.njk
---
Hello selamat datang - Azzam

{% include "postlist.njk" %}

{% for fact in facts | randomItem %}
{% endfor %}


## Blog Posts

<img src="{{ catpic }}" />
<!--{% for post in collections.posts %}
{{ post.data.title }}
{% endfor %}-->

<!-- templateEngineOverride: njk,md -->



