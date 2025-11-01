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

I am currently a postdoctoral research fellow with Speech Lab, College of Computing and Data Science, at Nanyang Technological University, supervised by Prof. [Eng Siong Chng](https://scholar.google.com/citations?hl=en&user=FJodrCcAAAAJ).  
Prior to joining NTU Speech Lab, I received my Ph.D. from School of Electronic and Electrical Engineering at Nanyang Technological University, under the supervision of Prof. [Andy W. H. Khong](https://scholar.google.com/citations?user=qnOioyYAAAAJ&hl=en) (EEE, Nanyang Technological University) and Dr. [Leibny Paola Garcia](https://scholar.google.com/citations?hl=en&user=fAXgPckAAAAJ&view_op=list_works&sortby=pubdate) (CLSP, The Johns Hopkins Univerisity). Apart from my supervisors, I also work closely with Prof. [Suzy J. Styles](https://scholar.google.com.sg/citations?user=k96cKgsAAAAJ&hl=en) (NTU), Prof. [Sanjeev Khudanpur](https://scholar.google.com/citations?hl=en&user=K-BdgNwAAAAJ&view_op=list_works&sortby=pubdate) (JHU), and Prof. [Shinji Watanabe](https://scholar.google.com/citations?user=U5xRA6QAAAAJ&hl=en) (CMU).

My research topics are:

- **Spoken Language Recognition:** Language identification and diarization

- **Speech Recognition:** Code-switching and multilingual speech recognition

- **Large-scale Pre-trained Model:** Speech/Audio-LLM and other LLM-based applications

# 📖 Educations
- *2018.08 - 2023.05*, Ph.D., Nanyang Technological University.  
Thesis: [Enhancing Spoken Language Identification and Diarization for Multilingual Speech](https://dr.ntu.edu.sg/handle/10356/168498)  
Supervisors: Prof. [Andy W. H. Khong](https://www3.ntu.edu.sg/home/andykhong/index.htm) (NTU) & Dr. [Leibny Paola Garcia](https://www.clsp.jhu.edu/faculty/paola-garcia/) (JHU)  
- *2017.08 - 2018.05*, Ms.C., Nanyang Technological University.  
- *2012.09 - 2016.07*, B.Eng, Harbin Institute of Technology.    
Supervisor: Prof. [Chenguang He](https://homepage.hit.edu.cn/hechenguang)  


# 📝 Publications
- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ACL 2025 Findings</span> [SpeechT-RAG: Reliable Depression Detection in LLMs with Retrieval-Augmented Generation Using Speech Timing Information](https://arxiv.org/abs/2502.10950), Xiangyu Zhang, **<u>Hexin Liu</u><sup>†</sup>**, Qiquan Zhang, Beena Ahmed, Julien Epps.  

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP 2025</span> [A Two-Stage LoRA Strategy for Expanding Language Capabilities in Multilingual ASR Models](https://arxiv.org/abs/2405.12609), Chin Yuen Kwok, **<u>Hexin Liu</u><sup>†</sup>**, Jia Qi Yip, Sheng Li, Eng Siong Chng.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP 2025</span> [Mamba in Speech: Towards an Alternative to Self-Attention](https://arxiv.org/abs/2405.12609), Xiangyu Zhang\*, Qiquan Zhang\*, **<u>Hexin Liu</u><sup>†</sup>***, Tianyi Xiao, Xinyuan Qian, Beena Ahmed, Eliathamby Ambikairajah, Haizhou Li, Julien Epps.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE TASLP 2025</span> [Aligning Speech to Languages to Enhance Code-switching Speech Recognition](https://arxiv.org/abs/2403.05887), **<u>Hexin Liu</u>**, Xiangyu Zhang, Haoyang Zhang, Leibny Paola Garcia, Andy W.H. Khong, Eng Siong Chng, Shinji Watanabe.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2024</span> [Enhancing Code-switching Speech Recognition with Interactive Language Biases](https://arxiv.org/pdf/2309.16953), **<u>Hexin Liu</u>**, Leibny Paola Garcia, Xiangyu Zhang, Andy W.H. Khong, Sanjeev Khudanpur.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span> [Reducing Language Confusion for Code-switching Speech Recognition with Token-level Language Diarization](https://ieeexplore.ieee.org/abstract/document/10095878/), **<u>Hexin Liu</u>**, Haihua Xu, Leibny Paola Garcia, Andy W.H. Khong, Yi He, Sanjeev Khudanpur.  

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Interspeech 2023</span> [MERLIon CCS Challenge: A English-Mandarin code-switching child-directed speech corpus for language identification and diarization](https://arxiv.org/abs/2305.18881), Victoria YH Chua\*, **<u>Hexin Liu</u>\***, Leibny Paola Garcia, Fei Ting Woon, Jinyi Wong, Xiangyu Zhang, Sanjeev Khudanpur, Andy W.H. Khong, Justin Dauwels, Suzy J Styles.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE JSTSP 2022</span> [Efficient self-supervised learning representations for spoken language identification](https://ieeexplore.ieee.org/abstract/document/9866521/), **<u>Hexin Liu</u>**, Leibny Paola Garcia, Andy W.H. Khong, Eng Siong Chng, Suzy J. Styles, Sanjeev Khudanpur.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Odyssey 2022</span> [Enhancing Language Identification using Dual-mode Model with Knowledge Distillation](https://www.researchgate.net/profile/Hexin_Liu6/publication/361591322_Enhancing_Language_Identification_Using_Dual-Mode_Model_with_Knowledge_Distillation/links/639f1bdfe42faa7e75d362df/Enhancing-Language-Identification-Using-Dual-Mode-Model-with-Knowledge-Distillation.pdf), **<u>Hexin Liu</u>**, Leibny Paola Garcia, Andy W.H. Khong, Justin Dauwels, Suzy J. Styles, Sanjeev Khudanpur.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Interspeech 2022</span><span style="color:red">(Oral)</span> [PHO-LID: A Unified Model Incorporating Acoustic-Phonetic and Phonotactic Information for Language Identification](https://arxiv.org/abs/2405.12609), **<u>Hexin Liu</u>**, Leibny Paola Garcia, Andy W.H. Khong, Suzy J. Styles, Sanjeev Khudanpur.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Interspeech 2021</span> [End-to-end language diarization for bilingual code-switching speech](https://www.researchgate.net/profile/Hexin_Liu6/publication/354221085_End-to-End_Language_Diarization_for_Bilingual_Code-Switching_Speech/links/613f238001846e45ef451003/End-to-End-Language-Diarization-for-Bilingual-Code-Switching-Speech.pdf), **<u>Hexin Liu</u>**, Leibny Paola Garcia, Xinyi Zhang, Justin Dauwels, Andy W.H. Khong, Sanjeev Khudanpur, Suzy J. Styles.

# 🧑‍🔬 Services
- **Reviewer:**&nbsp; ICASSP(23-24), Interspeech(2022-24), ASRU(2022-24), SLT(2022-24), COLING(2024-25), IEEE TASLP, SPL, ESWA
- **Session Chair:**&nbsp; Interspeech (2023), APSIPA-TPC (2025-27), IALP (2024)
- **Organizer:**&nbsp; Interspeech23@MERLIon, Interspeech25@MLC-SLM, ICASSP25@SPADE, ICASSP26@ASAE
- **Others:**&nbsp; Mentor in IEEE SLT 2022 Hackthon   

# 💻 Work Experiences
- *2016.09 - 2017.02*, Research Assistant, Harbin Institute of Technology, supervisor: Prof. Chenguang He.
- *2022.08 - 2023.01*, Research Scientist Intern, Bytedance AI Lab, Singapore.
- *2023.04 - 2023.08*, Research Associate, Delta-NTU Corp Lab, Nanyang Technological University, supervisor: Prof. Andy W.H. Khong.
- *2023.09 - now*, Research Fellow, Speech Lab, Nanyang Technological University, supervisor: Prof. Eng Siong Chng.

# 💬 Invited talks and awards
- *2024.06*，IEEE & APSIPA SG chapters joint Seminar: Emerging Trends and Innovations in Machine Learning and AI  
Automatic speech recognition with large language models [[slides]](https://entuedu-my.sharepoint.com/:p:/g/personal/hexin_liu_staff_main_ntu_edu_sg/EfQ_BZ7VYQhNtJxnBLa_tEcB-U58SWRY_TKxKf8c8SkgKw?e=4B8Jlw)
- *APSIPA 2025*, Best student paper award: "Explainable Disentanglement on Discrete Speech Representations for Noise-Robust ASR"
