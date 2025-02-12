---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

# 郭博文

**联系方式**  
- 电话: (+86) 180-7905-3176  
- 地址: 上海市杨浦区邯郸路220号  
- 邮箱: [gbone0790@gmail.com](mailto:gbone0790@gmail.com)  
- 个人主页: [gbone3176.github.io](https://gbone3176.github.io/)  

---

## 教育经历

### 复旦大学  
**电子信息科学与技术，信息科学与工程学院 | 本科**   2021.09—2025.06  


- **GPA: 3.66/4.0 (专业前 3%)**  主修课程：计算机体系结构(A)、信号与系统(A)、医学超声技术(A)、数字信号处理(A)、数字图像处理(A)、数字逻辑基础(A)、线性代数(A-)等。  

- **曾获荣誉**  
-- **2023年、2024年本科生国家奖学金**  
-- 2023年信息科学与工程学院“逐月”奖学金  
-- 2022-2023学年 复旦大学优秀团干部优秀学生  
-- **2024年全国大学生统计建模大赛省级二等奖**  
-- **2023年全国大学生光电设计大赛省级二等奖**  
-- 2023年上海市大学生工程与创新能力大赛二等奖  

---

## 科研经历

### CPDM：Prototype-Driven Class-Conditional Synthesis for High-Quality Chest X-ray Image Generation  |  **IEEE·EMBC 一作在投**  

- 提出类别原型驱动的扩散模型（CPDM），通过构造类别原型库和类别与类别的隐空间特征之间的交叉注意力机制，解决医学影像生成中的类别不平衡问题，同时提升图像质量和多样性。在胸部X光片生成任务上超过styleGAN3、U-Vit等SOTA模型。

### VAP-Diffusion: Harnessing the power of MLLM for complex medical data generation  |  **MICCAI 二作在投**
  

- 提出基础视觉提示策略，基于Chain-of-Thought 逐步提示MLLM 准确描述医学图像。提出多模态原型注入机制，构造基于类别的多模态原型库，辅助扩散模型类别解码。在ISIC2019，ISIC2018，结直肠（私有），ChestX-ray14等六个数据集上实现SOTA。

---

## 项目经历

### 基于simCLR-V2的隐空间CXR图像特征提取网络  |  **2024.03-2024.05**  

- 本项目为复旦大学医学影像与人工智能实验室文生图相关课题，本人在项目中负责对比学习的文献综述调研以及基于Simclr-V2网络架构和U-vit网络架构搭建并训练隐空间的CXR图像特征提取网络模型，用于其他下游任务中进行CXR图像特征的针对性高效提取。

### 基于多种机器学习模型的ICU卒中患者预后情况预测模型  **全国大学生统计建模竞赛 | 2024.02-2024.05** 
 
- 本项目以MIMIC-III中ICU内脑卒中患者的临床诊断数据为主要研究对象，构建基于卒中患者ICU内多临床指标的机器学习集成预测模型，其中模型的构建参考并使用了Logistics、SVM、Lasso、Random Forest、XGBoost等广泛使用的机器学习模型并进行了综合比较研究，模型能够针对临床指标进行自动筛选并进行预后情况预测。

### 基于机器视觉的运动目标控制与自动追踪系统  **全国大学生光电设计竞赛 | 2023.08**  

- 本项目基于传统机器视觉，控制云台实现红色激光点沿黑色循迹线移动，绿色激光点随红色激光点移动的效果。本人负责机器视觉与双机通讯部分，包括OpenMV图像处理、激光点与循迹线识别以及主从机通信的Python代码，以及ESP32与openMV之间的串口通信、舵机云台PID 控制的 C 代码。

---

## 实习经历

### 上海人工智能实验室  **智慧体育团队 Python实习生 | 2024.09—2024.12**  


- **参与智慧体育数据管理系统后端的架构设计、开发、测试和优化。** 基于Flask框架设计并优化智慧体育数据管理系统，实现了数据的CRUD操作、身份验证、缓存优化等功能。系统通过Flask-SQLAlchemy进行数据库操作，并基于Flasgger设计相关API文档并进行实际测试和部署。  
- **负责体育数据爬取及预处理系统的设计与开发，实现了高效的数据获取与处理流程。**

---

## 个人总结

- **个人品质**：本人乐观开朗、在校成绩优异、自驱能力强，具有良好的沟通能力和团队合作精神。  
- **语言证书**：大学英语四六级证书，具备良好的英语听说读写能力。普通话测试二级乙等。  
- **编程语言与工作流**：常用Python、Matlab，熟悉C，了解HTML、CSS。四年 Linux 使用经验，流利使用Shell、Vim、Git以及Github。

---

<!-- Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
