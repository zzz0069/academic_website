---
date: "2019-12-27T00:00:00Z"
external_link: ""
image:
  caption:
  focal_point: Smart
links:
- name: Github
  url: https://github.com/zzz0069/AU-ETRI_CM_V3.0
slides:
summary: 
tags:
- research
- include
title: A Novel Inference Architecture for Drivers' Status Estimation in L3 Driving Mode
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

## Summary
Autonomous driving is no longer a dream, now and then companies announce their research and development contributions for self-driving cars. When an autonomous system can't function correctly, it decides when the human driver needs to take over and whether the driver is ready to take control of the cognitive load of driving or not. In this paper, we focus on the question of drivers' readiness in autonomous mode for Level-3, in which human interaction with an autonomous system is required. Development of the whole architecture for drivers’ readiness is further divided into three interconnected models - Behavior Model, Inference Model, and Cognition Model. The behavior model is responsible for drivers’ behavior classification. The inference model is responsible for verifying and inferring the next state/behavior of the driver based on the driver's current state. The cognitive model is a binary classifier for making the final decision that the driver is ready or not. Our framework, Inference Architecture, ensembles all three models, takes sensor input images, and outputs driver's readiness as either "ready" or "not ready". We develop and test each model independently and will implement them for real car systems afterward.
