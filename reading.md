---
layout: page
title: Reading
---

## これからの読書会

### Next meeting

- 次回予定：2021-12月 
- 報告者：金崎　由布子
- ダナ・ハラウェイ 1991 （高橋さきの訳 2000）「状況に置かれた知：フェミニズムにおける科学という問題と、部分的視覚が有する特権」『猿と女とサイボーグ：自然の再発明』 第9章. 349-388頁. 青土社


## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title-ja }}]({{ post.url | relative_url }})

  [{{ post.title-en }}]({{ post.url | relative_url }})
  {% endfor %}
