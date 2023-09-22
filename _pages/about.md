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

# About Me
Zhongwei Qiu is currently pursuing his Ph.D. degree at the University of Science and Technology Beijing (USTB), supervised by Prof. Dongmei Fu, co-supervised by Dr. [Jianlong Fu](https://jianlong-fu.github.io/) from Microsoft Research Asia (MSRA). Before that, he received his B.S. degree in Automation from USTB in 2018. He had been a visiting researcher at the University of Sydney (USYD) since July 2022, supervised by Dr. [Chang Xu](http://changxu.xyz/).

His research interest includes 2D/3D human pose estimation and 3D human reconstruction, video super-resolution, NeRF, and diffusion model.

🔥**我在寻找计算机视觉或者多模态相关的工作机会，工作地点在北京、上海、深圳均可。如果有人推荐，欢迎Email，我将不胜感激。
I‘m seeking a position in computer vision and multimodal-related research based in Beijing, Shanghai, and Shenzhen. I would be grateful if anyone could recommend a job. Email:18813059739@163.com.** [简历/CV](https://github.com/qiuzhongwei-USTB/qiuzhongwei-USTB.github.io/blob/main/docs/resume_qiuzhongwei.pdf)

# 🎓︎ Educations
- *2022.07 - 2023.08*, Visiting Research Student, The University of Sydney, Sydney, Australia.
- *2018.06 - 2024.01*, Ph.D. student in Control Science and Engineering, University of Science and Technology Beijing, Beijing China. 
- *2014.09 - 2018.06*, Bachelor of Engineering in Automation, University of Science and Technology Beijing, Beijing China. 

# 🔥 News
- *2023.09*: &nbsp;🎉🎉 2 papers are accepted by NeurIPS.
- *2023.08*: &nbsp;🎉🎉 1 paper is accepted by TPAMI.
- *2023.08*: I will be the reviewer of AAAI 2024 and ICLR 2024.
- *2023.03*: The technology of [FTVSR](https://github.com/researchmm/FTVSR) has been shipped to [Microsoft Edge Browser](https://blogs.windows.com/msedgedev/2023/03/08/video-super-resolution-in-microsoft-edge/).
- *2023.03*: I will serve as the reviewer of NeurIPS 2023.
- *2023.03*: &nbsp;🎉🎉 1 paper is accepted by CVPR2023. 
- *2023.03*: &nbsp;🎉🎉 1 paper is accepted by Pattern Recognition. 
- *2022.12*: I will be the reviewer of ICML 2023.
- *2022.11*: &nbsp;🎉🎉 1 paper is accepted by AAAI2023. 
- *2022.10*: I will be the reviewer of CVPR 2023.

# 📝 Publications 
- **HAP: Structure-Aware Masked Image Modeling for Human-Centric Perception**

  Junkun Yuan, Xinyu Zhang, Hao Zhou, Jian Wang, **Zhongwei Qiu**, Zhiyin Shao, Shaofeng Zhang, Sifan Long, Kun Kuang, Kun Yao, Junyu Han, Errui Ding, Lanfen Lin, Fei Wu, Jingdong Wang.

  *NeurIPS 2023*
  
- **Stable Diffusion is Unstable**
  
  Chengbin Du, Yanxi Li, **Zhongwei Qiu**, Chang Xu.
  
  *NeurIPS 2023* [[paper]](https://arxiv.org/abs/2306.02583)
- **PSVT: End-to-End Multi-person 3D Pose and Shape Estimation with Progressive Video Transformers**
  
  **Zhongwei Qiu**, Yang Qiansheng, Jian Wang, Haocheng Feng, Junyu Han, Errui Ding, Chang Xu, Dongmei Fu, Jingdong Wang
  
  *CVPR 2023* [[paper]](https://arxiv.org/abs/2303.09187)
  
- **Weakly-supervised Pre-training for 3D Human Pose Estimation via Perspective Knowledge**
  
  **Zhongwei Qiu**, Kai Qiu, Jianlong Fu, Dongmei Fu
  
  *Pattern Recognition* [[paper]](https://www.sciencedirect.com/science/article/pii/S0031320323001978)
  
- **Learning Degradation-robust Spatiotemporal Frequency-Transformer for Video Super-Resolution**
  
  **Zhongwei Qiu**, Huan Yang, Jianlong Fu, Daochang Liu, Chang Xu, Dongmei Fu
  
  *TPAMI* [[paper]](https://ieeexplore.ieee.org/document/10239462) [[code]](https://github.com/researchmm/FTVSR)

- **DMIS: Dynamic Mesh-based Importance Sampling for Training Physics-Informed Neural Networks**
  
  Zijiang Yang, **Zhongwei Qiu**, Dongmei Fu
  
  *AAAI 2023* [[paper]](https://arxiv.org/abs/2211.13944) [[code]](https://github.com/MatrixBrain/DMIS)
  
- **Learning spatiotemporal frequency-transformer for compressed video super-resolution**
  
  **Zhongwei Qiu**, Huan Yang, Jianlong Fu, Dongmei Fu
  
  *ECCV 2022* [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136780252.pdf) [[code]](https://github.com/researchmm/FTVSR)
  
- **IVT: An End-to-End Instance-guided Video Transformer for 3D Pose Estimation**
  
  **Zhongwei Qiu**, Qiansheng Yang, Jian Wang, Dongmei Fu
  
  *ACM MM 2022* oral [[paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3547871)

- **Dynamic Graph Reasoning for Multi-person 3D Pose Estimation**
  
  **Zhongwei Qiu**, Qiansheng Yang, Jian Wang, Dongmei Fu
  
  *ACM MM 2022* [[paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3547846)
  
- **DGCN: Dynamic graph convolutional network for efficient multi-person pose estimation**
  
  **Zhongwei Qiu**, Kai Qiu, Jianlong Fu, Dongmei Fu
  
  *AAAI 2020* [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/6867)
  
- **Learning recurrent structure-guided attention network for multi-person pose estimation**
  
  **Zhongwei Qiu**, Kai Qiu, Jianlong Fu, Dongmei Fu
  
  *ICME 2019* oral [[paper]](https://ieeexplore.ieee.org/abstract/document/8785048)
  
# 👨‍💼 Work Experience
- *2021 - 2023*, Research Intern, Baidu VIS, Beijing, China.
- *2018.07 - 2021.02*, Research Intern, Microsoft Research Asia, Beijing, China.

# 🛠 Projects
- **AI Coach for freestyle skiing**, work with XiaoIce at MSRA
- **Video Super-Resolution**, work at MSRA

# 🎖 Honors and Awards
- *2023.05* CVPR 2023 Student Scholarship, CVPR
- *2022.12* Scholarship from Zenith Steel Group
- *2022.12* Star of Academic, University of Science and Technology Beijing
- *2022.12* Excellent Graduate Student, University of Science and Technology Beijing
- *2022.10* ECCV 2022 Student Scholarship, ECCV
- *2022.10* ACM Multimedia 2022 Student Scholarship, ACM Multimedia
- *2021.12* Star of Tomorrow, Microsoft Research Asia
- *2021.02* Star of Tomorrow, Microsoft Research Asia
- *2019.12* Silver Medal (10/1300+) in RSNA Intracranial Hemorrhage Detection, RSNA-Kaggle
- *2018.09* The 2nd place of ChinaMM 2018 JD AI Fashion-Challenge, JD.com
- *2018.06* Excellent Graduation Thesis, University of Science and Technology Beijing
- *2018.06* Outstanding Graduate, University of Science and Technology Beijing

# 💬 Invited Talks
- *2022.10*, "IVT: An End-to-End Instance-guided Video Transformer for 3D Pose Estimation" at ACM Multimedia 2022 (online), Lisbon, Portugal. 
- *2019.07*, "Learning recurrent structure-guided attention network for multi-person pose estimation" at ICME 2019, Shanghai, China.

# 📖 Academic Service
## Conference Reviewer
- **ICLR**: 2024
- **CVPR**: 2023
- **ICML**: 2023
- **NeurIPS**: 2023,2022
- **ACM MM**: 2023,2022,2021
- **AAAI**: 2024,2023
- **ICASSP**: 2023
- **ICME**: 2023,2022,2021,2020,2019

## Journal Reviewer
- TMM, TCSVT
