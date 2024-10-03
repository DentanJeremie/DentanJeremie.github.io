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

I'm a PhD candidate in ML security and privacy at École Polytechnique Paris, supervised by [Prof. Sonia Vanier](https://www.linkedin.com/in/sonia-vanier-31657061/) and [Prof. Davide Buscaldi](https://sites.google.com/site/davidebuscaldi/). I also collaborate with Crédit Agricole as part of the "Responsible and Trustworthy AI" partnership with École Polytechnique.

My research focuses on security and privacy issues in machine learning. I'm particularly interested in the robustness of Large Language Models against privacy attacks. I have developed some new adversarial attacks to reconstruct training data from multimodal models. I am now working on auditing tools to better understand and predict memorization, for practitioners to develop robust models.

I grew up in the south of France, near Aix-en-Provence. I followed the French engineering curriculum, with two years of "classe préparatoire" at [Sainte Geneviève](https://www.bginette.com) in Versailles, before attending the engineering curriculum at [École Polytechnique](https://programmes.polytechnique.edu/en/ingenieur-polytechnicien-program/ingenieur-polytechnicien-program), where I graduated in 2022. I also graduated from [ENS Paris-Saclay "MVA" Master](https://www.master-mva.com) in 2023, specializing in "Mathematics, Vision, leArning". I started my PhD at École Polytechnique Paris in 2023.

# 🔥 News
- *2024.09*: &nbsp;🗣️ I attended Google Responsible AI Summit in Paris to present some of my work, including [our last preprint](https://arxiv.org/abs/2409.18858)
- *2024.09*: &nbsp;👨‍🏫 I start teaching labs at ["Machine Learning and Deep Learning"](https://synapses.polytechnique.fr/catalogue/2022-2023/ue/565/INF554-machine-and-deep-learning) Master's course at École Polytechnique
- *2024.08*: &nbsp;🗣️ I was at Usenix Security Symposium in Philadelphie to present our paper [Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)
- *2024.06*: &nbsp;🥳 Our paper was accepted to Usenix Security 24! See our [preprint here!](https://arxiv.org/abs/2406.03182)
- *2024.03*: &nbsp;🍾 The "Responsible and Trustworthy AI" between Crédit Agricole and École Polytechnique is signed! Check out [this article here.](https://www.polytechnique.edu/en/news/inauguration-chair-trustworthy-and-responsible-artificial-intelligence)
- *2023.11*: &nbsp;🚀 I'm starting my PhD at École Polytechnique!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/predict_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predicting and analyzing memorization within fine-tuned Large Language Models](https://arxiv.org/abs/2409.18858)

**Jérémie Dentan**, Davide Buscaldi, Aymen Shabou, Sonia Vanier
- An auditing tool for practitioners to evaluate their models and predict vulnerable samples before they are memorized
- Supported by new theoretical results
- Easy to compute with a low computational budget
- Strong empirical results
- [Code available!](https://github.com/orailix/predict_llm_memorization)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Usenix Security 24</div><img src='images/cdmi_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)

**Jérémie Dentan**, Arnaud Paran, Aymen Shabou
- Presents the first reconstruction attacks against document understanding models
- Strong empirical results, with up to 4.1% of perfect reconstructions
- Focus on the impact of multimodality on the performance of the attack
</div>
</div>

- [Using Error Level Analysis to remove Underspecification](https://www.researchgate.net/publication/369315523_Using_Error_Level_Analysis_to_remove_Underspecification) Jérémie Dentan. 2023.
- [Towards a reliable detection of forgeries based on demosaicing](https://www.researchgate.net/publication/369481216_Towards_a_reliable_detection_of_forgeries_based_on_demosaicing) Jérémie Dentan. 2023.
- [Cellular Component Ontology Prediction](https://www.researchgate.net/publication/368293111_Cellular_Component_Ontology_Prediction) Jérémie Dentan, Abdellah El Mrini, Meryem Jaaidan. 2023.

# 📖 Educations
- *2022-2023*, Master of Science in Mathematics, Vision, leArning (MVA). ENS Paris-Saclay, Gif-sur-Yvette, France.
- *2019-2022*, Master of Engineering in Applied Mathematics and Computer Science. École Polytechnique, Palaiseau, France. 
- *2017-2019*, Classe préparatoire MPSI/MP*. Lycée Privé Ste Geneviève, Versailles, France. 

# 💻 Internships
- *2023.04 - 2023.09*, Research Assistant. Crédit Agricole DataLab Groupe, Montrouge, France.
- *2022.04 - 2022.09*, Research Assistant. Oracle Labs, Zurich, Switzerland.
- *2021.06 - 2021.08*, Business Analyst. BearingPoint, Paris, France.