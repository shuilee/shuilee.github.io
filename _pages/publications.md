---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Conference Proceedings
====
1. Nam Van Hai Phan, Tha Thanh Le, Tuan Phu Phan, Thuy Thu Le, Phuong-Nam Tran, Nhat Truong Pham and Duc Ngoc Minh Dang, “Deep Learning-Based Automated Cashier System for Bakeries”, 9th International Conference on Intelligent Information Technology (ICIIT 2024), Feb 23-25, 2024, https://dl.acm.org/doi/abs/10.1145/3654522.3654538
2. Thu Thuy Le, Nhat Truong Pham, Phuong-Nam Tran, and Duc Ngoc Minh Dang,“Federated Learning with U-Net for Brain Tumor Segmentation: Impact of Client Numbers and Data Distribution”, The 15th International Conference on ICT Convergence (ICTC 2024), Jeju, Korea
 
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
