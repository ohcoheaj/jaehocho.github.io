---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/CV_jaehocho.pdf" class="btn btn--primary"><i class="fas fa-file-pdf"></i> Download CV (PDF)</a>

Education
======
* **M.S. in Artificial Intelligence**, Ulsan National Institute of Science and Technology (UNIST), Jan. 2025 – Feb. 2027 (expected)
  * Artificial Intelligence Graduate School · GPA 3.85 / 4.3
* **B.S. in Media Technology & Applied Mathematics (double major)**, Hanyang University ERICA, Mar. 2019 – Aug. 2024
  * GPA 4.17 / 4.5 (Major 4.25 / 4.5) · Early Graduation, *Summa Cum Laude*

Research Interests
======
* Transfer Learning, Semi/Self-Supervised Learning
* Object Detection, Anomaly Detection
* Industrial AI (AI+X)

Experience
======
* **Intern**, POSCO DX (Intelligence Operation Group), Jul. 2026
  * Real-time detection model (YOLOv11) for key steel tapping events and validation of PLC integration with a mock PLC server
* **Research Intern**, MVL Lab, UNIST, Jul. 2024 – Aug. 2024 (Advisor: Taehwan Kim)
  * Semi-supervised learning, multi-modal representation learning
* **Research Intern**, Visual Intelligence Lab, ETRI, Jan. 2024 – Feb. 2024 (Advisor: Kimin Yun)
  * Domain adaptation of Grounding DINO for banner detection via semi-supervised learning
* **Research Intern**, Field Robotics Lab, ETRI (UST), Jul. 2023 – Aug. 2023 (Advisor: Seung Ik Lee)
  * Out-of-distribution object detection with Detection Transformer

Research Projects
======
* **IITP Hyperscale Industrial AI** @ IMML Lab, May 2026 – Dec. 2026 (Co-first Author)
  * Benchmark for large-scale engineering drawings with a VLM fine-tuned via supervised fine-tuning
* **Multi-Modal Industrial Anomaly Detection** @ IMML Lab, Jun. 2025 – Mar. 2026 (First Author)
  * Extracting and fusing defect information from RGB and 3D point clouds

Publications
======
**International Conferences**
  <ul>{% for post in site.publications reversed %}{% if post.category == "conferences" %}
    {% include archive-single-cv.html %}{% endif %}
  {% endfor %}</ul>

**Domestic Conferences**
1. **J. H. Cho**, Y. S. Bae, Y. S. Cheon, and K. M. Yun, "Fine-tuning Open-set Detectors through Self Training and Data Selection Strategies: A Case Study in Banner Detection", *KCC 2024*, Jeju, Korea (poster)
2. J. H. Song, **J. H. Cho**, and S. I. Lee, "Integrating Regional Proposal Network and Segment Model for Enhanced Out-of-Distribution Object Detection", *KSC 2023*, Busan, Korea (poster)
3. **J. H. Cho**, H. J. Lee, G. H. Jeon, M. T. Oh, and S. B. Yoon, "A study on the improvement of Object Detection Model via Data Augmentation", *ACK 2023*, Korea

Awards and Honors
======
* 3rd Prize, WCRC Data Contest (deep learning session), 2023
* Participation Award, KSC 2023 Undergraduate/Junior Paper Competition, 2023
* Haesung Cultural Foundation Scholarship, 2024
* Software Brain Scholarship (Academic Excellence), Hanyang University ERICA, 2022–2023
* ERICA Excellent Talent Scholarship, Hanyang University ERICA, 2019
* Dacon: Low-resolution bird image classification (20 / 385, top 5%); LG Aimers 3rd Hackathon (71 / 747, top 10%)

Skills
======
* **Programming**: Python (Advanced), PyTorch, R (Intermediate), Java (Beginner)
* **Language**: English — OPIc Intermediate High (IH)

Military Service
======
* Republic of Korea Navy (Cheonghae Unit 33rd), Jan. 2020 – Sep. 2021
