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

My research focuses on security and privacy in machine learning, with a particular interest in the robustness of Large Language Models against privacy attacks. I have developed [new adversarial attacks](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan) to reconstruct training data from multimodal models, designed [an auditing method](https://arxiv.org/abs/2409.18858) to predict LLM memorization in classification settings, and proposed [a new taxonomy of memorization](https://arxiv.org/abs/2508.02573) that aligns with attention mechanisms and enables fine-grained localization. I am currently working on new techniques for uncertainty quantification in LLM outputs, and I published [a new benchmark on that topic](https://arxiv.org/abs/2511.17081).

I grew up near Aix-en-Provence, France, and followed the French engineering curriculum, including two years of "classe préparatoire" at [Sainte Geneviève](https://www.bginette.com) in Versailles. I then joined the engineering program at [École Polytechnique](https://programmes.polytechnique.edu/en/ingenieur-polytechnicien-program/ingenieur-polytechnicien-program), graduating in 2022. I also graduated from [ENS Paris-Saclay "MVA" Master](https://www.master-mva.com) in 2023, specializing in Mathematics, Vision, and Learning. I started my PhD at École Polytechnique Paris in 2023.

📄 [Download my CV (PDF)](assets/files/JDentan_resume.pdf)

# 🔥 News
- *2025.11*: &nbsp;🥳 Our paper was accepted for an oral presentation at AAAI-26! See our [preprint here!](https://arxiv.org/abs/2508.02573)
- *2025.07*: &nbsp;🥳 Our paper was accepted to ECAI 2025! See our [preprint here!](https://arxiv.org/abs/2409.18858)
- *2025.04*: &nbsp;👨‍🏫 I was at [SaTML 2026 conference](https://satml.org/2025/) in Copengagen. Very interesting papers and presentations!
- *2024.08*: &nbsp;🗣️ I was at Usenix Security Symposium in Philadelphie to present our paper [Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)
- *2024.03*: &nbsp;🍾 The "Responsible and Trustworthy AI" between Crédit Agricole and École Polytechnique is signed! Check out [this article here.](https://www.polytechnique.edu/en/news/inauguration-chair-trustworthy-and-responsible-artificial-intelligence)

# 🔈 Invited talks

- *2025.11.24*: AMIAD, Paris. *AI Safety at Scale*. Jérémie Dentan.
- *2025.10.23*: PIAF, Palaiseau. *Scaling Trustworthiness in the Era of Large Language Models*. Jérémie Dentan.  <a href="https://piaf-saclay.org/groupe-de-lecture.html">[Website of the association]</a>
- *2025.01.28*: FIIA 2025, Paris. *Measuring and understanding ivacy risks in Language Models*. Sonia Vanier and Jérémie Dentan. <a href="assets/files/2025_01_28__Vanier_Denta_FIIA.pdf">[Slides]</a> <a href="https://www.linkedin.com/posts/jeremiedentan_i-attended-the-9th-industrial-forum-of-the-activity-7291128297063686144-Ix54">[LinkedIn Post]</a> 
- *2024.10.02*: Google Responsible AI Summit, Paris. *Towards security and privacy in document understanding models*. Sonia Vanier and Jérémie Dentan. <a href="assets/files/2024_10_02__Vanier_Denta_Google-1.pdf">[Slides]</a> <a href="https://www.linkedin.com/posts/jeremiedentan_last-week-i-attended-google-responsible-ai-activity-7249833934304292864-l0R6">[LinkedIn Post]</a> 
- *2024.10.02*: Google Responsible AI Summit, Paris. *Trust and Security in AI*. Sonia Vanier and Jérémie Dentan. <a href="assets/files/2024_10_02__Vanier_Denta_Google-2.pdf">[Slides]</a> <a href="https://www.linkedin.com/posts/jeremiedentan_last-week-i-attended-google-responsible-ai-activity-7249833934304292864-l0R6">[LinkedIn Post]</a> 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/much_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MUCH: A Multilingual Claim Hallucination Benchmark](https://arxiv.org/abs/2511.17081)

*ArXiv Preprint - November 2025*

**Jérémie Dentan**, Alexi Canesse, Davide Buscaldi, Aymen Shabou, Sonia Vanier
- A new claim-level benchmark for uncertainty quantification for LLM
- Design to mimic production monitoring of LLMs' outputs via a fast claim segmenter
- Open-source all generation scripts and logits to facilitate future research 
- <a href="https://huggingface.co/datasets/orailix/MUCH">[Hugging Face]</a> 
- <a href="https://github.com/orailix/much">[GitHub]</a> 
- <a href="https://pypi.org/project/much-segmenter/">[PyPI]</a> 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI-26</div><img src='images/guess_recall_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Guess or Recall? Training CNNs to Classify and Localize Memorization in LLMs](https://arxiv.org/abs/2508.02573)

*Association for the Advancement of Artificial Intelligence (AAAI) - January 2026*

**Jérémie Dentan**, Davide Buscaldi, Sonia Vanier
- Analyzing attention weights with CNNs to identify patterns in verbatim-memorized samples  
- Introducing a data-driven taxonomy of memorized samples  
- Localizing the attention regions involved in each form of memorization  
- <a href="https://github.com/orailix/cnn-4-llm-memo">[Code]</a> 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/classif_sae_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unveiling Decision-Making in LLMs for Text Classification : Extraction of influential and interpretable concepts with Sparse Autoencoders](https://arxiv.org/abs/2506.23951)

*ArXiv Preprint - June 2025*

Mathis Le Bail, **Jérémie Dentan**, Davide Buscaldi, Sonia Vanier
- A new SAE-based method to extract interpretable concepts from LLMs  
- Applicable to any LLM-based classification scenario  
- Demonstrates strong empirical results  
- <a href="https://github.com/orailix/ClassifSAE">[Code]</a> 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2025</div><img src='images/predict_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predicting memorization within Large Language Models fine-tuned for classification](https://arxiv.org/abs/2409.18858)

*European Conference on Artificial Intelligence (ECAI) - October 2025*

**Jérémie Dentan**, Davide Buscaldi, Aymen Shabou, Sonia Vanier
- An auditing tool for practitioners to evaluate their models and predict vulnerable samples before they are memorized
- Theoretical justification and strong empirical results
- Easy to use with a low computational budget
- <a href="https://github.com/orailix/predict_llm_memorization">[Code]</a> 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Usenix Security 24</div><img src='images/cdmi_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reconstructing Training Data From Document Understanding Models](https://www.usenix.org/conference/usenixsecurity24/presentation/dentan)

*Usenix Security Symposium - August 2024*

**Jérémie Dentan**, Arnaud Paran, Aymen Shabou
- Presents the first reconstruction attacks against document understanding models
- Strong empirical results, with up to 4.1% of perfect reconstructions
- Focus on the impact of multimodality on the performance of the attack
- <a href="https://www.usenix.org/system/files/usenixsecurity24_slides-dentan.pdf">[Slides]</a>  <a href="https://youtu.be/Ob9J2qmhvfU">[Presentation Video]</a> 
</div>
</div>

- [Using Error Level Analysis to remove Underspecification](https://www.researchgate.net/publication/369315523_Using_Error_Level_Analysis_to_remove_Underspecification) Jérémie Dentan. 2023.
- [Towards a reliable detection of forgeries based on demosaicing](https://www.researchgate.net/publication/369481216_Towards_a_reliable_detection_of_forgeries_based_on_demosaicing) Jérémie Dentan. 2023.
- [Cellular Component Ontology Prediction](https://www.researchgate.net/publication/368293111_Cellular_Component_Ontology_Prediction) Jérémie Dentan, Abdellah El Mrini, Meryem Jaaidan. 2023.

# 📖 Educations
- *2022-2023*, Master of Science in Mathematics, Vision, Learning (MVA). ENS Paris-Saclay, Gif-sur-Yvette, France.
- *2019-2022*, Master of Engineering in Applied Mathematics and Computer Science. École Polytechnique, Palaiseau, France. 
- *2017-2019*, Classe préparatoire MPSI/MP*. Lycée Privé Ste Geneviève, Versailles, France. 

# 💻 Internships
- *2023.04 - 2023.09*, Research Assistant. Crédit Agricole DataLab Groupe, Montrouge, France.
- *2022.04 - 2022.09*, Research Assistant. Oracle Labs, Zurich, Switzerland.
- *2021.06 - 2021.08*, Business Analyst. BearingPoint, Paris, France.
- *2019.09 - 2020.03*, Deputy Project Manager for Civil Security. French Embassy, Antananarivo, Madagascar.

<br>
<br>
<br>
<br>
<br>
