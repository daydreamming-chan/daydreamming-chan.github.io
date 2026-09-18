---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: /assets/images/empty_300x200.png
  title: 照片一
  desc: 在此放置说明
- src: /assets/images/empty_300x200.png
  title: 照片二
  desc: 在此放置说明
- src: /assets/images/empty_300x200.png
  title: 照片三
  desc: 在此放置说明
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
