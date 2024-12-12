---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

## [Recent Projects]
- **Human-Robot Co-Transportation with Human Uncertainty-Aware MPC and Pose Optimization**
  * Abstract: This paper proposes a new control algorithm for
human-robot co-transportation based on a robot manipulator
equipped with a mobile base and a robotic arm. The primary
focus is to adapt to human uncertainties through the robot’s
whole-body kinematics and pose optimization. We introduce
an augmented Model Predictive Control (MPC) formulation
that explicitly models human uncertainties and contains extra
variables than regular MPC to optimize the pose of the robotic
arm. The core of our methodology involves a two-step iterative
design: At each planning horizon, we select the best pose of
the robotic arm (joint angle combination) from a candidate
set, aiming to achieve the lowest estimated control cost. This
selection is based on solving an uncertainty-aware Discrete
Algebraic Ricatti Equation (DARE), which also informs the
optimal control inputs for both the mobile base and the robotic
arm. To validate the effectiveness of the proposed approach, we
provide theoretical derivation for the uncertainty-aware DARE
and perform simulated and hardware experiments using a Fetch
robot under varying conditions, including different trajectories
and noise levels. The results reveal that our proposed approach
outperforms baseline algorithms.
 [[Preprint]](https://arxiv.org/pdf/2404.00514) [[Video]](https://youtu.be/PwDM0ed08ms?si=PVsEdDzGWro5cpkl)
  
- **Social-LLaVA: Enhancing Robot Navigation through Human-Language Reasoning in Social Spaces**
  * Abstract: Most existing social robot navigation techniques
either leverage hand-crafted rules or human demonstrations to
connect robot perception to socially compliant actions. However, there remains a significant gap in effectively translating
perception into socially compliant actions, much like how
human reasoning naturally occurs in dynamic environments.
Considering the recent success of Vision-Language Models
(VLMs), we propose using language to bridge the gap in
human-like reasoning between perception and socially aware
robot actions. We create a vision-language dataset, Social
robot Navigation via Explainable Interactions (SNEI), featuring 40K human-annotated Visual Question Answers (VQAs)
based on 2K human-robot social interactions in unstructured,
crowded public spaces, spanning perception, prediction, chain of-thought reasoning, action, and explanation. We fine-tune a
VLM, Social-LLaVA, using SNEI to demonstrate the practical
application of our dataset. Social-LLaVA outperforms state-of-the-art models like GPT-4V and Gemini, based on the average of
fifteen different human-judge scores across 50 VQAs. Deployed
onboard a mobile robot, Social-LLaVA enables human-like
reasoning, marking a promising step toward socially compliant
robot navigation in dynamic public spaces through language
reasoning. [[Preprint]](https://cs.gmu.edu/~xiao/papers/social_llava.pdf) [[Video]](https://youtu.be/dcHOuPguz_s?si=cB0YmIVhWB7u3itR)


## [Previous Projects]
- **ML & AI**
  * Image Forgery Detection.
  * Automatic Radiology Report Generation from X-Rays.
  * Machine Reading Comprehension in Medical Field.
  * Data analysis of clinical trials using Unsupervised Learning. 

- **Development**
  * Design and develop APIs for data enrichment and search in Clinical Data Portal. <ins>Tools:</ins> Node.js, React, PostgreSQL, Sequelize
  * Design and build backend of an online Course-Selling website. <ins>Tools:</ins> AWS Serverless, DynamoDb, Node.js, GraphQL