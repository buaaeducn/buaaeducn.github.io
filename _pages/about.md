---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student at the [School of Transportation Science and Engineering](https://transportation.buaa.edu.cn/), [Beihang University](https://www.buaa.edu.cn/) (2023.06 – Present), majoring in Intelligent Transportation Engineering.

My research spans the tasks of autonomous driving perception and artificial intelligence ethics. Specifically, I focus on Bird's-Eye-View (BEV) architectures (such as BEVFormer and SparseBEV) for accurate perception on nuScenes and UAV datasets, as well as AI value alignment aimed at evaluating and improving LLM moral performance and Agent architectures.

**Fields:** Intelligent Transportation Engineering, Autonomous Driving Perception, AI Ethics & Alignment

**Topics:** Bird's-Eye-View (BEV) Architectures, Deep Learning Models, AI Value Alignment, LLM Moral Performance, Agent Architectures

Primary Email: [23374261@buaa.edu.cn](mailto:23374261@buaa.edu.cn)
Secondary Email: [1832541406@qq.com](mailto:1832541406@qq.com)


---

## Publications {#publications}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Projects & Portfolio {#portfolio}
{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

## Talks & Presentations {#talks}
{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

## Teaching {#teaching}
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}