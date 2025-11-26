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

Ruyue Xin is a Lecturer at the School of Artificial Intelligence, China University of Geosciences (Beijing). She received her Ph.D. in 2023 from the University of Amsterdam, the Netherlands, under the supervision of Prof. Cees de Laat, Prof. Paola Grosso, and Dr. Zhiming Zhao, at the MultiScale Networked Systems (MNS) Lab. Her research focuses on machine learning–based performance diagnosis for distributed applications, developing novel anomaly detection and causal inference methods to detect performance anomalies and identify root causes. She has published more than 20 papers in international journals and conferences, including ACM Computing Surveys (CSUR), Future Generation Computer Systems (FGCS), Journal of Systems and Software (JSS), etc. She serves as an executive committee member of the CCF Service Computing Committee.

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by the ACM Computing Surveys (CSUR) (IF:28). 
<!--- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. .-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CUSR 2025</div><img src='images/trustAI2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trustworthy AI-based performance diagnosis systems for cloud applications: A review](https://dl.acm.org/doi/full/10.1145/3701740)

**Ruyue Xin**, Jingye Wang, Peng Chen, Zhiming Zhao

<!---[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> .-->
- Performance diagnosis systems using AI can be summarized into a general framework from data to models. However, the AI-based framework has hazards such as limited data privacy and low robustness that may degrade user experience and trust. Therefore, it is essential to review trustworthiness requirements for AI-based performance diagnosis systems. In this paper, we introduce trustworthiness requirements and extract six key ones: data privacy, fairness, robustness, explainability, efficiency, and human intervention. We then unify these requirements into a general performance diagnosis framework, from data collection to model development. Next, we provide related works for each component and concrete actions to improve trustworthiness. Finally, we identify research directions and challenges for developing trustworthy AI-based performance diagnosis systems.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FGCS 2024</div><img src='images/fgcc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A fine-grained robust performance diagnosis framework for run-time cloud applications](https://www.sciencedirect.com/science/article/pii/S0167739X24000591)

**Ruyue Xin**, Peng Chen, Paola Grosso, Zhiming Zhao

- To maintain required service quality for time-critical cloud applications, operators must continuously detect performance anomalies and diagnose their root causes. However, existing methods face challenges such as the need for high-quality labeled data, low reusability and robustness of detection models, and the lack of real-time fine-grained root cause localization. These issues hinder quick fixes and effective adaptation decisions. We provide a Fine-grained Robust Performance Diagnosis (FIRED) framework to address these challenges. The framework includes a metrics selection component to filter noise and improve detection efficiency, an anomaly detection component that assembles several well-chosen base models with a deep neural network and uses weakly supervised learning, and a real-time fine-grained root cause localization component to identify dependent resource metrics of performance anomalies.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JSS 2023</div><img src='images/causalRCA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Causalrca: Causal inference based precise fine-grained root cause localization for microservice applications](https://www.sciencedirect.com/science/article/pii/S016412122300119X)

**Ruyue Xin**, Peng Chen, Zhiming Zhao

- Effectively localizing root causes of performance anomalies is crucial for rapid recovery and loss mitigation in cloud microservice applications. Depending on the granularity of localized causes, operators may take different actions, e.g., restarting or migrating services for coarse-grained faulty service localization, or scaling resources when specific indicative metrics are identified (fine-grained). Prior research mainly targets coarse-grained localization, while interest in fine-grained root cause localization is increasing. Causal inference (CI) methods have recently gained popularity but face limitations such as linear causal assumptions and strict data distribution requirements. To address these challenges, we propose CausalRCA, a framework for fine-grained, automated, real-time root cause localization. CausalRCA employs a gradient-based causal structure learning method to generate weighted causal graphs and a root cause inference method to localize root cause metrics.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCC 2023</div><img src='images/AD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust and accurate performance anomaly detection and prediction for cloud applications: a novel ensemble learning-based framework](https://link.springer.com/article/10.1186/s13677-022-00383-6)

**Ruyue Xin**, Hongyun Liu, Peng Chen, Zhiming Zhao

- Effectively detecting run-time performance anomalies is crucial for clouds to identify abnormal behavior and prevent future incidents. For real-world use, an anomaly detection framework must satisfy three key requirements: high detection accuracy, good robustness to changing application patterns, and the ability to predict upcoming anomalies. However, existing research mainly focuses on improving accuracy, and few approaches address all three challenges simultaneously. Our experiments on multiple application monitoring datasets show that existing methods emphasize different data features, leading to diverse performance across patterns. Thus, they struggle to improve accuracy and robustness and to predict anomalies. To meet the three requirements, we propose an Ensemble Learning-Based Detection (ELBD) framework that integrates well-selected detection methods. ELBD includes three classic linear ensemble methods (maximum, average, weighted average) and a novel deep ensemble method.
</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** .-->

<!--# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. .-->

# 📖 Educations
- *2019.09 - 2023.11*, Doctor, Computer Science, University of Amsterdam, Amsterdam, Netherlands. 
- *2016.09 - 2019.06*, Master, System Analysis and Integration, Beijing Normal University, Beijing, China. 
- *2012.09 - 2016.06*, Bachelor, Information Management and Information Systems, Communication University of China, Beijing, China. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. .-->
