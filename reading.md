---
layout: page
title: Reading
---

## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title }}]({{ post.url | relative_url }})

  {% endfor %}

## これからの読書会

### Next meeting

- 2021-8-31 フェミニストによる考古学の実践　報告者：西原和代
  [Wylie, A. 2007 Doing Archaeology as a Feminist: Introduction](https://link.springer.com/article/10.1007/s10816-007-9034-4)
