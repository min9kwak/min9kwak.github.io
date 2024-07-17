---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## In Preparation or Submitted
* Kwak, M. G., Mao, L., Zheng, Z., Su, Y., Lure, F., & Li, J. (2024). A Mutual Knowledge Distillation Framework for Alzheimer's Disease Diagnosis Using Incomplete Multi-Modal Images. <i>IEEE Transactions on Automation Science and Engineering</i>, **under revision**.
* Lee, Y., Kwak, M. G., Chen, R. Q., Yan, H., Mupparapu, M., Lure, F., Setzer, F. C., & Li, J. (2024). Oral-Anatomical Knowledge-Informed Semi-Supervised Learning for 3D Dental CBCT Segmentation and Lesion Detection. <i>IEEE Transactions on Automation Science and Engineering</i>, **under revision**.
* Heo, J., Lee, Y. J., Kim, J., Kwak, M., Park, Y. J., & Kim, S. B. (2024). Mixing Corrupted Preferences for Robust and Feedback-Efficient Preference-Based Reinforcement Learning. <i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i>, **submitted**.
* Lee, Y. J., Kim, J., Park, Y. J., Kwak, M., & Kim, S. B. (2024). Masked and Inverse Dynamics Modeling for Data-Efficient Reinforcement Learning. <i>IEEE Transactions on Neural Networks and Learning Systems</i>, **under revision**.
* Kwak, M., Kahng, H., & Kim, S. B. (2023). Safe Semi-Supervised Contrastive Learning Using In-Distribution Data as Positive Examples. <i>IEEE Transactions on Knowledge and Data Engineering</i>, **under revision**.

## Published
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
