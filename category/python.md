---
layout: default
category: 
    - python 
    - jekyll 
    - kyuran
tags: [a, b, c]
---

# python 에 관련된 카테고리 

<ol>
{% for tag in page.tags %}
    <li>{{ tag }}</li>
{% endfor %}
</ol>
{{ page.category[0] }}
{% for post in site.posts %}
    {{ post.title }}
{% endfor %}

