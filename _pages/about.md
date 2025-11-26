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

Ruyue Xin is a Lecturer at the School of Artificial Intelligence, China University of Geosciences (Beijing). She received her Ph.D. in 2023 from the University of Amsterdam, the Netherlands, under the supervision of Prof. Cees de Laat, Prof. Paola Grosso, and Dr. Zhiming Zhao, at the MultiScale Networked Systems (MNS) Lab. Her research focuses on machine learning–based performance diagnosis for distributed applications, developing novel anomaly detection and causal inference methods to detect performance anomalies and identify root causes. She has published papers in international journals and conferences, including ACM Computing Surveys (CSUR), Future Generation Computer Systems (FGCS), Journal of Systems and Software (JSS), etc. She serves as an executive committee member of the CCF Service Computing Committee.

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by the ACM Computing Surveys (CSUR) (IF:28). 
<!--- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. .-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CUSR 2025</div><img src='images/trustAI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trustworthy AI-based performance diagnosis systems for cloud applications: A review](https://dl.acm.org/doi/full/10.1145/3701740)

**Ruyue Xin**, Jingye Wang, Peng Chen, Zhiming Zhao

<!---[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> .-->
- Performance diagnosis systems for cloud applications are usually developed based on AI approaches, which can be summarized into a general framework from data to models. However, the AI-based framework has potential hazards that could degrade the user experience and trust. For example, a lack of data privacy may compromise the security of AI models, and low robustness can be hard to apply in complex cloud environments. Therefore, it is essential to systematically reviews trustworthiness requirements for AI-based performance diagnosis systems. In this paper, we first introduce trustworthiness requirements and extract six key requirements from a technical perspective, including data privacy, fairness, robustness, explainability, efficiency, and human intervention. We then unify these requirements into a general performance diagnosis framework, ranging from data collection to model development. Next, we comprehensively provide related works for each component and concrete actions to improve trustworthiness in the framework. Finally, we identify possible research directions and challenges for the future development of trustworthy AI-based performance diagnosis systems. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FGCS 2024</div><img src='images/fgcs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A fine-grained robust performance diagnosis framework for run-time cloud applications](https://www.sciencedirect.com/science/article/pii/S0167739X24000591)

**Ruyue Xin**, Peng Chen, Paola Grosso, Zhiming Zhao

- To maintain the required service quality of time-critical cloud applications, operators must continuously monitor their runtime status, detect potential performance anomalies, and diagnose the root causes of these anomalies effectively. However, existing performance diagnosis methods face challenges such as the need for high-quality labeled data, the low reusability and robustness of performance anomaly detection models, and the absence of real-time fine-grained root cause localization. These challenges make fixing performance issues quickly and developing effective adaptation decisions difficult. We provide a Fine-grained Robust Performance Diagnosis (FIRED) framework to tackle those challenges. The framework offers a metrics selection component to filter noise and improve detection efficiency, an anomaly detection component that assembles several well-selected base models with a deep neural network, and adopts weakly supervised learning considering fewer labels exist in reality. The framework also employs a real-time, fine-grained root cause localization component to locate dependent resource metrics of performance anomalies. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JSS 2023</div><img src='images/causalRCA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Causalrca: Causal inference based precise fine-grained root cause localization for microservice applications](https://www.sciencedirect.com/science/article/pii/S016412122300119X)

**Ruyue Xin**, Peng Chen, Zhiming Zhao

- Effectively localizing root causes of performance anomalies is crucial to enabling the rapid recovery and loss mitigation of microservice applications in the cloud. Depending on the granularity of the causes that can be localized, a service operator may take different actions, e.g., restarting or migrating services if only faulty services can be localized (namely, coarse-grained) or scaling resources if specific indicative metrics on the faulty service can be localized (namely, fine-grained). Prior research mainly focuses on coarse-grained faulty service localization, and there is now a growing interest in fine-grained root cause localization to identify faulty services and metrics. Causal inference (CI) based methods have gained popularity recently for root cause localization, but currently used CI methods have limitations, such as the linear causal relations assumption and strict data distribution requirements. To tackle these challenges, we propose a framework named CausalRCA to implement fine-grained, automated, and real-time root cause localization. The CausalRCA uses a gradient-based causal structure learning method to generate weighted causal graphs and a root cause inference method to localize root cause metrics. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCC 2023</div><img src='images/AD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust and accurate performance anomaly detection and prediction for cloud applications: a novel ensemble learning-based framework](https://link.springer.com/article/10.1186/s13677-022-00383-6)

**Ruyue Xin**, Hongyun Liu, Peng Chen, Zhiming Zhao

- Effectively detecting run-time performance anomalies is crucial for clouds to identify abnormal performance behavior and forestall future incidents. To be used for real-world applications, an effective anomaly detection framework should meet three main challenging requirements: high accuracy for identifying anomalies, good robustness when application patterns change, and prediction ability for upcoming anomalies. Unfortunately, existing research about performance anomaly detection usually focuses on improving detection accuracy, while little research tackles the three challenges simultaneously. We conduct experiments for existing detection methods on multiple application monitoring data, and results show that existing detection methods usually focus on different features in data, which will lead to their diverse performance on different data patterns. Therefore, existing anomaly detection methods have difficulty improving detection accuracy and robustness and predicting anomalies. To address the three requirements, we propose an Ensemble Learning-Based Detection (ELBD) framework which integrates existing well-selected detection methods. The framework includes three classic linear ensemble methods (maximum, average, and weighted average) and a novel deep ensemble method. 
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
