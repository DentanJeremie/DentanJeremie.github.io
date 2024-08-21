---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I'm Jérémie 👋

I'm a first year PhD candidate at École Polytechnique Paris, supervised by Prof. Sonia Vanier and Prof. Davide Buscaldi. I also collaborate with Crédit Agricole as part of the "Responsible and Trustworthy AI" partnership with École Polytechnique.

I grew up in the south of France, near Aix-en-Provence. I followed the French engineering curriculum, with two years of "classe préparatoire" in Versailles, before attending École Polytechnique, where I graduated in 2022. I also graduated from ENS Paris-Saclay MVA Master in 2023, specializing in "Mathematics, Vision, leArning". I started my PhD at École Polytechnique Paris at the end of 2023.

My research focuses on security and privacy issues in machine learning. I'm particularly interested in the robustness of Large Language Models against privacy attacks. I have developed some new adversarial attacks to reconstruct training data from multimodal models. I am now focusing on the mechanism of training data memorization itself, to better understand what makes a model robust to such privacy attacks.

# 🔥 News
- *2024.09*: &nbsp;👨‍🏫 I will start teaching labs at "Machine Learning and Deep Learning" Master's course at École Polytechnique
- *2024.08*: &nbsp;🗣️ I was at Usenix Security Symposium in Philadelphie to present our paper [Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)
- *2024.06*: &nbsp;🥳 Our paper was accepted to Usenix Security 24! See our [preprint here!](https://arxiv.org/abs/2406.03182)
- *2023.11*: &nbsp;🚀 I'm starting my PhD at École Polytechnique!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Usenix Security 24</div><img src='images/teaser_zoom.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)

**Jérémie Dentan**, Arnaud Paran, Aymen Shabou
- Presents the first reconstruction attacks against document understanding models
- Strong empirical results, with up to 4.1% of perfect reconstructions
</div>
</div>

- `Data Challenge` [Using Error Level Analysis to remove Underspecification](https://www.researchgate.net/profile/Jeremie-Dentan/publication/369315523_Using_Error_Level_Analysis_to_remove_Underspecification/links/641465e0315dfb4cce89bda9/Using-Error-Level-Analysis-to-remove-Underspecification.pdf)

# 📖 Educations
- *2022-2023*, Master of Science in Mathematics, Vision, leArning (MVA). ENS Paris-Saclay, Gif-sur-Yvette, France.
- *2019-2022*, Master of Engineering in Applied Mathematics and Computer Science. École Polytechnique, Palaiseau, France. 
- *2017-2019*, Classe préparatoire MPSI/MP*. Lycée Privé Ste Geneviève, Versailles, France. 

# 💻 Internships
- *2023.04 - 2023.09*, Research Assistant. Crédit Agricole DataLab Groupe, Montrouge, France.
- *2022.04 - 2022.09*, Research Assistant. Oracle Labs, Zurich, Switzerland.
- *2021.06 - 2021.08*, Business Analyst. BearingPoint, Paris, France.