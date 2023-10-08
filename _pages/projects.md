---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

## [Recent Projects]
- **Targeted Learning: A Hybrid Approach to Social Robot Navigation**
  * Abstract: Empowering robots to navigate in a socially compliant manner is essential for the acceptance of robots moving in human-inhabited environments. Previously, roboticists have developed classical navigation systems with decades of empirical validation to achieve safety and efficiency. However, the many complex factors of social compliance make classical navigation systems hard to adapt to social situations, where no amount of tuning enables them to be both safe (people are too unpredictable) and efficient (the frozen robot problem). With recent advances in deep learning approaches, the common reaction has been to entirely discard classical navigation systems and start from scratch, building a completely new learning-based social navigation planner. In this work, we find that this reaction is unnecessarily extreme: using a large-scale real-world social navigation dataset, SCAND, we find that classical systems can be used safely and efficiently in a large number of social situations (up to 80%). We therefore ask if we can rethink this problem by leveraging the advantages of both classical and learning-based approaches. We propose a hybrid strategy in which we learn to switch between a classical geometric planner and a data-driven method. Our experiments on both SCAND and two physical robots show that the hybrid planner can achieve better social compliance in terms of a variety of metrics, compared to using either the classical or learning-based approach alone. [[Preprint]](https://browse.arxiv.org/pdf/2309.13466.pdf) [[Video]](https://youtu.be/QT0JTuPhnqE?si=5KXGpkhJGD_5NO8D)
  
- **A Study on Learning Social Robot Navigation with Multimodal Perception**
  * Abstract: Autonomous mobile robots need to perceive the environments with their onboard sensors (e.g., LiDARs and RGB cameras) and then make appropriate navigation decisions. In order to navigate human-inhabited public spaces, such a navigation task becomes more than only obstacle avoidance, but also requires considering surrounding humans and their intentions to somewhat change the navigation behavior in response to the underlying social norms, i.e., being socially compliant. Machine learning methods are shown to be effective in capturing those complex and subtle social interactions in a data-driven manner, without explicitly hand-crafting simplified models or cost functions. Considering multiple available sensor modalities and the efficiency of learning methods, this paper presents a comprehensive study on learning social robot navigation with multimodal perception using a large-scale realworld dataset. The study investigates social robot navigation decision making on both the global and local planning levels and contrasts unimodal and multimodal learning against a set of classical navigation approaches in different social scenarios, while also analyzing the training and generalizability performance from the learning perspective. We also conduct a human study on how learning with multimodal perception affects the perceived social compliance. The results show that multimodal learning has a clear advantage over unimodal learning in both dataset and human studies. We open-source our code for the community’s future use to study multimodal perception for learning social robot navigation. [[Preprint]](https://browse.arxiv.org/pdf/2309.12568.pdf) [[Video]](https://youtu.be/5j8mAK9ecjs?si=dSjcXME6bupwPp-x)


## [Previous Projects]
- **ML & AI**
  * Image Forgery Detection.
  * Automatic Radiology Report Generation from X-Rays.
  * Machine Reading Comprehension in Medical Field.
  * Data analysis of clinical trials using Unsupervised Learning. 

- **Development**
  * Design and develop APIs for data enrichment and search in Clinical Data Portal. <ins>Tools:</ins> Node.js, React, PostgreSQL, Sequelize
  * Design and build backend of an online Course-Selling website. <ins>Tools:</ins> AWS Serverless, DynamoDb, Node.js, GraphQL