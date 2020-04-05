---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

##Journal Papers

1. **J. Chen**, C. Touati and Q. Zhu, "A Dynamic Game Approach to Strategic Design of Secure and Resilient Infrastructure Network," IEEE Transactions on Information Forensics and Security, vol. 15, pp. 462 - 474, 2020. [PDF](https://arxiv.org/pdf/1906.07185.pdf)
1. **J. Chen**, C. Touati and Q. Zhu, "Optimal Secure Design of Two-Layer IoT Network," IEEE Transactions on Control of Network Systems, vol, 7 no 1,  pp. 398 - 409, 2020. [PDF](https://arxiv.org/pdf/1707.07046v2.pdf)
1. **J. Chen** and Q. Zhu, "Control of Multi-Layer Mobile Autonomous Systems in Adversarial Environments: A Games-in-Games Approach," IEEE Transactions on Control of Network Systems, accepted, 2019. [PDF](https://arxiv.org/pdf/1912.04082.pdf)
1. Y. Huang, **J. Chen**, L. Huang and Q. Zhu, "Dynamic Games for Secure and Resilient Control System Design," National Science Review, accepted, 2019.
1. **J. Chen** and Q. Zhu, "Interdependent Strategic Security Risk Management with Bounded Rationality in the Internet of Things," IEEE Transactions on Information Forensics and Security, vol. 14, no. 11, pp. 2958 - 2971, 2019. [PDF](https://arxiv.org/pdf/1905.09341.pdf)
1. J. Pawlick, **J. Chen** and Q. Zhu, "iSTRICT: An Interdependent Strategic Trust Mechanism for the Cloud-Enabled Internet of Controlled Things," IEEE Transactions on Information Forensics and Security, vol. 14, no. 6, pp. 1654 - 1669, 2019. [PDF](https://arxiv.org/pdf/1805.00403.pdf)
1. **J. Chen** and Q. Zhu, "A Stackelberg Game Approach for Two-Level Distributed Energy Management in Smart Grids," IEEE Transactions on Smart Grid, vol. 9, no. 6, pp. 6554-6565, 2018. [PDF](https://arxiv.org/pdf/1608.08253.pdf)
1. **J. Chen** and Q. Zhu, "Security as a Service for Cloud-Enabled Internet of Controlled Things Under Advanced Persistent Threats: A Contract Design Approach," IEEE Transactions on Information Forensics and Security, vol. 12, no. 11, pp. 2736-2750, 2017. [PDF](https://drive.google.com/open?id=12aJbLe3V2SpeZKQkI2H5vjCfH9Y0pdYf)
1. **J. Chen** and Q. Zhu, "A Game-Theoretic Framework for Resilient and Distributed Generation Control of Renewable Energies in Microgrids," IEEE Transactions on Smart Grid, vol. 8, no. 1, pp. 285-295, 2017. [PDF](https://arxiv.org/pdf/1601.04583.pdf)
1. **J. Chen**, C. Touati and Q. Zhu, "A Dynamic Game Analysis and Design of Infrastructure Network Protection and Recovery," ACM SIGMETRICS Performance Evaluation Review, vol. 45, no. 2, pp. 125-128, 2017. [PDF](https://arxiv.org/pdf/1707.07054.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
