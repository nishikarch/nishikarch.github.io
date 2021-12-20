---
layout: page
title: Topics
---

読書会で話題に上がったトピックについてのメモ

{% for topic in site.topics %}

- [{{ topic.title-ja }}]({{ topic.url | relative_url }})

  [{{ topic.title-en }}]({{ topic.url | relative_url }})
  {% endfor %}
