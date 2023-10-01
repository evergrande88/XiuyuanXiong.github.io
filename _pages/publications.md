---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Journal Article
**Xiuyuan Xiong**, Kuiying Deng, Jiale Wu, Yixiong Cui. Distribution pattern analysis of passing and receiving locations during the 2022 FIFA World Cup using the measure of spatial entropy. *International Journal of Performance Analysis in Sport* (Out for review).
## Conference
**Xiuyuan Xiong**, Yixiong Cui, Kuiying Deng. Performance evaluation of the 2022 FIFA World Cup teams using the measure of spatial entropy of successful passes. 28th Annual Congress of the European College of Sport Science (ECSS2023), 2023, Paris, France, Poster


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
