---
layout: page
title: Reading
---

## これからの読書会

### Next meeting

- 次回予定：2022年2月20日（日）　9時　オンライン（Zoom）
- 報告者：石田 温美
- 報告内容：<a href="http://hokuryukan-ns.co.jp/cms/books/%e8%80%83%e5%8f%a4%e5%ad%a6%e3%82%b8%e3%83%a3%e3%83%bc%e3%83%8a%e3%83%ab%e3%80%802021%e5%b9%b412%e6%9c%88%e5%8f%b7-%e3%82%b8%e3%82%a7%e3%83%b3%e3%83%80%e3%83%bc%e3%81%a8%e8%80%83%e5%8f%a4%e5%ad%a6/">『考古学ジャーナル』2021年12月号 特集：ジェンダーと考古学
</a>

## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title-ja }}]({{ post.url | relative_url }})

  [{{ post.title-en }}]({{ post.url | relative_url }})
  {% endfor %}
