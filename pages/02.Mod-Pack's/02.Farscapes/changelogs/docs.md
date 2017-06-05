---
title: Change Logs
process:
    markdown: true
    twig: true
theme: learn2
content:
    items: @self.siblings
    order:
        by: date
        dir: desc
    limit: 10
    pagination: true
---

## Beyond-Reality: Farscapes Versions

{% for p in page.collection %}
<h2>{{ p.title }}</h2>
{{ p.summary }}
{% endfor %}
