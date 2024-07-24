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

* Song, Z., & Jung, J. H. (2020). The exact formula of the optimal penalty parameter value of the spectral penalty method for differential equations. Applied Mathematics and Computation, 381, 125313
![image](https://github.com/user-attachments/assets/00e5d097-7ba9-4216-8cc7-5982da92bf06)
* ¬	Song, Z., & Taylor, D. (2023). Coupling Asymmetry Optimizes Collective Dynamics over Multiplex Networks. IEEE Transactions on Network Science and Engineering 11 (2), 1524-1541.
![image](https://github.com/user-attachments/assets/1e70d3d7-d9b5-4f10-afa6-6758b7f28fce)

* ¬	Song, Z., & Taylor, D. (2024). Laplacian Spectra of Multiplex Networks with Asymmetric Coupling. To be submitted in 2024.
![image](https://github.com/user-attachments/assets/01467f5d-5af9-476b-8cc2-30e2d71f4701)

* ¬	Boyd, Z., Lee, E., Song, Z., & Mucha, P. (2024). You Need to Explain How You Thresholded. To be submitted in 2024.
![image](https://github.com/user-attachments/assets/de1b7be7-101e-4ddb-ac50-df5122492c0e)



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
