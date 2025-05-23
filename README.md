![GitHub Banner](assets/banner.png)

# About me

Hi, I am Zhou Zihui. I am a Master's student in Computer Science at Chongqing University 🎓. My current research interests include **Multi-modal Representation Learning**, **Vision-Language Models**, **Computer Vision**, and **Remote Sensing AI**.

- **Resume:** [Download Resume](assets/resume.pdf)
- [**Zhihu**](https://www.zhihu.com/people/guai-guai-28-38)

# Educations

- _2023.09.01 - current_, Master's Student, Major in Computer Science, Chongqing University

  - Advisor: Prof. Feng Yong
  - Research Focus: **Multi-modal Representation Learning**, **Vision-Language Models**, **Computer Vision**, and **Remote Sensing AI**.

- _2019.09.01 - 2023.06.30_, Undergraduate Student, Major in Computer Science, Chongqing University

  - Bachelor Thesis: Research and Implementation of Image Text Retrieval Based on Attention Mechanism

# Publications

## Assessment and Mitigation of Hallucinations in Multimodal Large Language Models within the Domain of Remote Sensing (Under Review)

**Zihui Zhou**, Yong Feng, Guofan Duan, Mingliang Zhou, and Weijia Jia

- We characterize MLLM hallucination patterns in the remote sensing field, establishing a taxonomy that categorizes 4 different hallucination types.
- We propose an MLLM hallucinations detection suite: including **the RSHalluEval benchmark, evaluation metrics, and flexible automated hallucination detection strategies (for precision-focused and efficiency-focused scenes, respectively)**, and evaluate MLLM hallucinations in this domain.
- We introduce **RSHalluShield**: a hallucination mitigation dataset of 30,000 QA pairs.
- We fine-tune the model on the RSHalluShield dataset, resulting in a 12.33% increase in the hallucination-free rate. Superior performance is also achieved on downstream tasks.

![img](assets/hallucination_framework.png)

## Fine-Grained Information Supplementation and Value-Guided Learning for Remote Sensing Image-Text Retrieval

**Zihui Zhou**, Yong Feng, Agen Qiu, Guofan Duan, and Mingliang Zhou

**Accepted by the IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing** | [**Paper**](assets/Fine-Grained_Information_Supplementation_and_Value-Guided_Learning_for_Remote_Sensing_Image-Text_Retrieval.pdf) | [**Code**](https://github.com/zhouzihui2001/FISVL/tree/main)

We propose a fine-grained information supplementation and value-guided learning (FISVL) model. Feature enhancement is carried out by integrating the prior knowledge in the field of recommendation systems, and a value-oriented training strategy is adopted to learn feature representations that are fine-grained, highly expressive and robust. Specifically, FISVL contains the following core modules:
1. ​**fine-grained information supplementation (FGIS)​**: By fusing the visual information of global and local features, the perception ability of the model for multi-scale features of remote sensing images is enhanced, and the problem of representation limitations caused by insufficient feature granularity in traditional methods is solved.
2. ​**Double loss optimization mechanism**: Aiming at the problem of excessive similarity within the mode, weighted contrast loss (the weighting strategy refers to the dynamic adjustment method of sample importance) and scene adaptive fine-grained perceptial loss are proposed to improve the model discrimination ability by constraining the spatial distribution of features.
3. ​**Value-Guided Learning Framework**: enables the model to focus on the most valuable information at different training stages, thereby adapting to the specific requirements of each phase.
We verify the validity of the model on the RSICD and RSITMD datasets. The results show that this method reaches the leading level in both fine-grained feature learning and cross-modal alignment tasks.
![# FISVL框架图](assets/fine-grained_framework.png)
![# FISVL在RSITMD和RSICD数据集上的效果](assets/FISVL_result1.png)
![# 可视化效果](assets/FISVL_result2.png)

# Projects
## Bachelor Thesis: Research and Implementation of Image Text Retrieval Based on Attention Mechanism
_September 2018-May 2019_, Chongqing University, Researcher | Supervisor: Prof Feng Yong
- We developed an **intra-modal loss function with three forms (visual, text, and combined modalities)** to constrain global feature disparities between positive instances and hard negatives, thus obtaining superior global feature representation.
- We adopted **two re-ranking algorithms** to optimize the similarity matrix.
- We conducted experiments to demonstrate the superiority of the proposed model and developed **a prototype image-text retrieval system** based on it.
![# SGRAF+框架图](assets/sgraf+.png)

## Intelligent Environmental Monitoring System Based on Multi-source Satellite Remote Sensing Images
_September 2023-June 2024_, Chongqing University, Project member | Supervisor: Prof Feng Yong
- System functions:
  
  - Supports intelligent recognition of more than 13 types of objects in environments such as forests and rivers.
  - Supports dynamic change detection and dynamic recognition of patches, with a dynamic recognition rate of patches exceeding **89%**.
  - Supports the segmentation of long and narrow rivers and can fit the trajectories on both sides of the river to calculate the trajectory fitting accuracy. The dynamic trajectory fitting accuracy is less than **4.78m**.
  - Supports the real-time interpretation of the large vision-language model.
- My contributions:

  - Developed the functional module for high-resolution remote sensing image segmentation.
  - Trained the river segmentation model and achieved an mIoU of **92%**.
  - Deployed the remote sensing MLLM GeoChat to implement intelligent remote sensing question answering.


<p align="center">
  <img src="assets/system_segment.png" width="744" height="272" alt="Example of segment" style="display: block; margin: 0 auto;">
</p>
<p align="center">
  <img src="assets/system_river_segment.png" width="414" height="239" alt="河流分割示例" style="display: block; margin: 0 auto;">
</p>
<p align="center">
  <img src="assets/system_change_detection.png" width="1083" height="344" alt="变化检测示例" style="display: block; margin: 0 auto;">
</p>
<p align="center">
  <img src="assets/system_geochat.png" width="786" height="398" alt="大模型示例" style="display: block; margin: 0 auto;">
</p>

# Internships

**Chongqing Longline Intelligent Technology Co., Ltd.** 

_December 2024-April 2025_, Perception and Localization Department Intern, Algorithm Design Engineer

  - **Automated Labeling for Autonomous Driving Data**: Responsible for business data adaptation and prompt design for model inference. The whole project has been packaged as an operator to enable large scale data production.
  - **Multi-modal Driving Data Generation**: Trained and optimized the 3D occupancy control generation model, including business data adaptation and model training and tuning for 3D scene reconstruction.
 
# Honors and Awards

- _November 2024_, University-level First-Class Scholarship
- _November 2023_, University-level First-Class Scholarship
- _October 2024_, University-level Merit Student
- _June 2022_, National-level Innovation and Entrepreneurship Training Program, Second-Level Completion

# Skills

## Programming Languages

- Python
- Java
- C++

## Machine Learning & AI

- **Frameworks**: PyTorch, OpenCV
- **Techniques**: Deep Learning, Multi-modal Representation Learning, Computer Vision

# Contact

- **Email:** 20191694@cqu.edu.com
