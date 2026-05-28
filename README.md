<div align="center">

# Rishabh Singh

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=500&lines=AI+Infra+%7C+LLMs+%7C+Low-Level+Systems;Incoming+SWE+%40+AWS+EC2;ACL+2026+%7C+UW+Paul+G.+Allen+School)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](https://rscsportfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rissingh23)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rissingh23)

Seeking Fall 2026 / Summer 2027 internships in SWE, AI Infra, and ML Engineering.

</div>

---

## Research

### Reading Between the Lines: The One-Sided Conversation Problem
*ACL 2026 — 2nd Author*  
[Paper](https://arxiv.org/abs/2511.03056) · [Allen School ML Lab](https://www.cs.washington.edu)

Formalized the one-sided conversation (1SC) problem: inferring missing dialogue when only one speaker is recorded. Built an NLP pipeline for dialogue infilling and summarization from partial transcripts, fine-tuning LLMs with PyTorch and deploying inference via Flask into a real-time in-ear AI device. Evaluated with LLM-as-a-Judge and human A/B testing across MultiWOZ, DailyDialog, and Candor.

---

## Featured Projects

---

### Calendub — UW Club Discovery Platform
[Live](https://calendub-app.vercel.app) · [GitHub](https://github.com/rissingh23/CalenDUB-Web)

Full-stack club discovery and event platform for UW students.
- AI-powered recommendations using Python, MongoDB, Firebase, and OpenAI; improved query performance by 40%
- Presented to 500+ students; supported 30+ UW clubs

---

### ML-Based OS Task Scheduling Simulator
[Live](https://tasksim-lab.onrender.com) · [Github](https://github.com/rissingh23/ml-os-task-scheduling-simulator)
- Built a multithreaded C++ OS scheduler simulator supporting FIFO, MLFQ, and ML-based scheduling with analysis
- Achieved 68\% runtime-prediction accuracy by training XGBoost and DNNs on Google / Alibaba cluster traces.
- Reduced deadline-miss rate by \textbf{13\%} by using ML-guided scheduling to optimize processes over heuristic baselines.

---

### Low-Latency Limit Order Book Simulator and ML Inference Engine
[Live](https://low-latency-order-book-sim.vercel.app) · [GitHub](https://github.com/rissingh23/low-latency-order-book-sim)

High-performance C++ matching engine built for low-latency trading simulation.
- Price-time priority engine handling 1M+ orders/sec throughput
- Lock-free queues and cache-aware data structures reducing latency by 35%
- XGBoost and MLP small models running optimized for future decision/optimal prediction
- Profiled with `perf` and CPU flame graphs, measuring p50/p99 under burst traffic

---

### FocusLoop — Real-Time EEG + Eye-Tracking Neurofeedback
*1st Place (EEG Track), NeuroHackathon*  
[GitHub](https://github.com/rissingh23/FocusLoop)

Closed-loop attention-training platform fusing EEG and eye-tracking to adapt a Unity environment in real time.
- Combined Muse 2 EEG (β / θ+α focus index) and Tobii gaze dispersion into a single attention state at 10 Hz
- Built Python signal pipeline with MNE, BrainFlow, and ZeroMQ; Unity OSC listener adjusts lighting and distractors
- Dual-sensor fusion halved calibration time vs. single-signal neurofeedback systems

---

### AppetizeAI — Social Dining Finder
[GitHub](https://github.com/rissingh23/AppetizeAI)

Full-stack social dining platform using Flask microservices, AWS Bedrock, and Yelp APIs.
- Developed REST APIs integrating AWS Bedrock to generate ranked restaurant recommendations with 92% user satisfaction
- Reduced response latency by 35% through Redis caching and optimized PostgreSQL query execution
- Served 25+ users across Flask microservices backed by Node.js and Redis

---

### LeetCode Learning Extension — SensAI
*2nd Place, OSS4AI Hackathon*  
[Demo](https://youtu.be/YhLaJVf3ZGQ) · [GitHub](https://github.com/rissingh23/SensAI)

Chrome extension balancing AI assistance with real problem-solving growth.
- Automated evaluation workflows using LLMs and synthetic datasets
- Improved problem-solving performance by 15% across 60+ signups

---

<details>
<summary>More Projects</summary>
<br>

**[UW Campus Pathfinder](https://github.com/rissingh23/UW-Campus-Pathfinder-Friend-Locator)**  
Dijkstra-based campus navigation and friend locator — React + TypeScript

**[Stock Analysis Assistant](https://github.com/rissingh23/AI-Financial-Assistant-Visual-Text)**  
LLM + yfinance financial analysis tool — React, Python, OpenAI API

**[Neuro-Care](https://github.com/rissingh23/neuro-care-cognitive-exercise-for-dementia-patients)**  
Adaptive cognitive exercises for dementia patients — React Native, FastAPI, Python, SQL

**[Fish Species Detection](https://github.com/rissingh23/Fish-Species-Detection-CNN)**  
Image-based fish classifier trained on 20K images — TensorFlow, React, Gemini API

**[Weather & Spam Classifier](https://github.com/rissingh23/Spam-Weather-Classifier)**  
Decision tree classifiers for weather prediction and spam detection

**[Keploy Open Source](https://github.com/rissingh23/keploy)**  
Contributions to API testing and mocking infrastructure — Go, Docker, Kubernetes

</details>

---

## Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000?style=flat&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)

---

<div align="center">

[![Streak](https://github-readme-streak-stats.herokuapp.com?user=rissingh23&theme=radical&hide_border=true)](https://github.com/rissingh23)

</div>
  
