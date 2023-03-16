---
layout: page
title: Reading
---

## これからの読書会

### Next meeting

- 次回予定：2023年4月以降（詳細未定）
- 内容：未定（提案受付中）

## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title-ja }}]({{ post.url | relative_url }})

  [{{ post.title-en }}]({{ post.url | relative_url }})
  {% endfor %}
