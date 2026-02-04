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

I am a first-year Ph.D. student in Computer Science and Informatics at *Emory University*, advised by [Prof. Kai Shu](https://www.cs.emory.edu/~kshu5/). I hold an Sc.M. in Computer Science from Brown University and a B.Eng. in Computer Science from Huazhong University of Science and Technology. My research interests lie in Trustworthy Artificial Intelligence, with a particular emphasis on adversarial machine learning across computer vision and natural language processing. In addition to research, I have contributed to broadening access to computer science education by teaching fundamental CS and AI concepts to high school students through the IgniteCS outreach program. Outside of academia, I pursue personal interests in basketball, strength training, and reading. 

I always welcome opportunities to connect and chat about research, collaborations, or shared interests.


<!-- My research interest is Trustworthy AI. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# News
- *2025.09*: &nbsp;🎉🎉 One paper was accepted by [NeurIPS 2025](https://neurips.cc/Conferences/2025).
- *2025.03*: &nbsp;🎉🎉 Admitted to the PhD program at Emory University! Looking forward to this new chapter.
- *2023.03*: &nbsp;🎉🎉 Admitted to the ScM CS program at Brown University! Excited for the journey ahead.

# Publications 
<ul>
  <li>
    <a href="https://arxiv.org/abs/2507.16052"><strong>Disrupting Semantic and Abstract Features for Better Adversarial Transferability</strong></a><br/>
    <em><strong>Yuyang Luo</strong>, Xiaosen Wang, Zhijin Ge, Yingzhe He</em><br/>
    <span>arXiv preprint, 2025</span>
  </li>

  <li>
    <a href="https://arxiv.org/abs/2505.19911"><strong>Attention! Your Vision-Language Model Could Be Maliciously Manipulated</strong></a><br/>
    <em>Xiaosen Wang, Shaokang Wang, Zhijin Ge, <strong>Yuyang Luo</strong>, Shudong Zhang</em><br/>
    <span>Advances in Neural Information Processing Systems (NeurIPS), 2025</span>
  </li>

  <li>
    <a href="https://github.com/Trustworthy-AI-Group/TransferAttack"><strong>TransferAttack</strong></a>
    <span id="stars-transferattack"></span><br/>
    <em>Xiaosen wang, Zhijin Ge, Shaokang Wang, <strong>Yuyang Luo</strong>, et al.</em><br/>
    <span>Open-source adversarial attack library (GitHub)</span>
  </li>

  <script>
  fetch("https://api.github.com/repos/Trustworthy-AI-Group/TransferAttack")
    .then(res => res.json())
    .then(data => {
      document.getElementById("stars-transferattack").textContent = `⭐ ${data.stargazers_count}`;
    });
  </script>
</ul>
<!-- - [Disrupting Semantic and Abstract Features for Better Adversarial Transferability](https://arxiv.org/abs/2507.16052), Yuyang Luo, Xiaosen Wang, Zhijin Ge, Yingzhe He, **arXiv preprint**, 2025
- [Attention! You Vision Language Model Could Be Maliciously Manipulated](https://arxiv.org/abs/2505.19911), Xiaosen Wang, Shaokang Wang, Zhijin Ge, Yuyang Luo, Shudong Zhang, **arXiv preprint**, 2025
- [TransferAttack](https://github.com/Trustworthy-AI-Group/TransferAttack), Xiaosen Wang, Zhijin Ge, Shaokang Wang, Yuyang Luo -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# Honors and Awards
<!-- - *June 2022* MindSpore AI Innovation Training Camp: First Prize in AI Innovation Training Camp and awarded MindSpore open-source community internship.   -->
- *Feb 2022* Meritorious Winner, Meritorious Winner, Mathematical Contest in Modeling (COMAP): Ranked in the top 7% among all participants.
- *Oct 2021 & Oct 2020* Individual Scholarship on Arts and Sports: Awarded for outstanding performance in arts and sports activities (Top 2%).
- *Apr 2020* Freshman Scholarship: Granted for academic excellence during the freshman year (Top 2%).


# Educations
- *2025.09 – Present* — **Ph.D.**, Computer Science and Informatics, Emory University  
- *2023.09 – 2025.05* — **M.S.**, Computer Science, Brown University  
- *2019.09 – 2023.06* — **B.Eng.**, Computer Science, Huazhong University of Science and Technology 

# Academic Services
- **Conference Reviewer**: WWW 2026, PAKDD 2026

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2024.05 - 2024.08*, [Lorem](https://github.com/), China. -->