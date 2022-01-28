---
layout: post
author: "me"
date: 2022-01-28
---


{% for post in site.blogposts %}
- {{ post.date | date_to_string }}: [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
