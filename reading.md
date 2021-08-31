---
layout: page
title: Reading
---

## これからの読書会

### Next meeting

- [2021-９月下旬 報告者：石田温美](https://archaeology-gender-europe.org/docs/silvia.pdf)

  [Tomášková, Silvia. 2007. Mapping a Future: Archaeology, Feminism, and Scientific Practice](https://archaeology-gender-europe.org/docs/silvia.pdf)

## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title-ja }}]({{ post.url | relative_url }})

  [{{ post.title-en }}]({{ post.url | relative_url }})
  {% endfor %}
