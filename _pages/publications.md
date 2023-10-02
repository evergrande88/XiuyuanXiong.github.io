---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Journal Article
**Xiuyuan Xiong**, Kuiying Deng, Jiale Wu, Yixiong Cui. Distribution pattern analysis of passing and receiving locations during the 2022 FIFA World Cup using the measure of spatial entropy. *International Journal of Performance Analysis in Sport* (Out for review).
## Conference
**Xiuyuan Xiong**, Yixiong Cui, Kuiying Deng. Performance evaluation of the 2022 FIFA World Cup teams using the measure of spatial entropy of successful passes. 28th Annual Congress of the European College of Sport Science (ECSS2023), 2023, Paris, France, Poster.      

**Xiuyuan Xiong**, Zhengliang Lin, Yanfei Shen, Kuiying Deng. Evaluation of comprehensive ability of CBA teams based on multiple regression and TOPSIS model. 13th National Sports Science Conference, 2023, Tianjing, China, Poster.         

**Xiuyuan Xiong**, Yanfei Shen, Kuiying Deng. Robustness analysis of the passing network of Chinese Super League teams in case of random failure. 18th Chinese Conference on Complex Network (CCCN2022), 2022, Zhuhai, China, Oral presentation.        

**Xiuyuan Xiong**, Wenjuan Zhang, Hua Zeng. Multi‑factor investment strategies based on support vector regression. 7th International Conference on Computational and Information Sciences (ICCIS 2019), 2019, Chengdu, China, Oral presentation.     

Yating Zhou, Yixiong Cui, **Xiuyuan Xiong**. Passing performance of teams with low ball possession in the 2022 Qatar World Cup based on social network analysis. 13th National Sports Science Conference, 2023, Tianjing, China, Poster.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
