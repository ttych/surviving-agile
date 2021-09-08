---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Welcome to My Home Page

{% assign date = '2021-09-08T01:02:03Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}
