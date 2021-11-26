---
layout: page
title: Reading
---

## これからの読書会

### Next meeting

- 次回予定：2021-12月〜2022　1月 報告者：未定

## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title-ja }}]({{ post.url | relative_url }})

  [{{ post.title-en }}]({{ post.url | relative_url }})
  {% endfor %}
