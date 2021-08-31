---
layout: page
title: Reading
---
## これからの読書会

### Next meeting

- 2021-９月下旬 報告者：石田温美　[Tomášková, Silvia. 2007. Mapping a Future: Archaeology, Feminism, and Scientific Practice](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwj62uarl9ryAhUM62EKHewBDx8QFnoECAUQAQ&url=https%3A%2F%2Farchaeology-gender-europe.org%2Fdocs%2Fsilvia.pdf&usg=AOvVaw1zRcHXFpiqBoHzpV2GG2CF)



## これまでの読書会

### Past meetings

{% for post in site.posts %}
**{{ post.date | date: "%B %d, %Y" }}**

- [{{ post.title }}]({{ post.url | relative_url }})

  {% endfor %}
  
