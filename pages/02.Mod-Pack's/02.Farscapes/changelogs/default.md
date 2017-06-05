---
title: Change Logs
process:
    markdown: true
    twig: true
theme: learn2
content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 10
    pagination: true
---

## Beyond-Reality: Farscapes Versions

<table>
  <thead>
    <tr>
      <th>Version</th>
      <th>Summary</th>
    </tr>
  </thead>
  <tbody>
{% for p in page.collection %}
    <tr>
      <td><a href="{{p.url}}">{{p.title}}</a></td>
      <td style="font-size:1em!important">{{p.summary}}</td>
    </tr>
{% endfor %}
  </tbody>
</table>
