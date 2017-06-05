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
