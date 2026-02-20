---
layout: default
title: Sarayu Sivakumar Dhaya


---


## About Me

I am a Master’s graduate in Artificial Intelligence at the University at Buffalo with 5+ years of professional software engineering experience across backend systems and distributed architectures.My industry background shaped how I approach systems, with a focus on reliability, scalability and thoughtful design.

During my coursework I led an industry partnered project with Machinery Monitoring Systems LLC involving real motor hardware, including fault simulation, vibration data collection, data pipelinedevelopment and iterative model refinement for robustness under real-world noise and constraints.

Through coursework, I gained hands-on experience in deep learning, computer vision, and machine learning system design — implementing models, designing structured experiments, benchmarking performance, and refining systems based on measurable results.In parallel, I built personal projects, including a Retrieval-Augmented Generation (RAG) conversational assistant and an agentic multimodal retrieval system. These projects involved semantic search, vector embeddings, hybrid retrieval pipelines, and agent-based reasoning to produce grounded and reliable responses.

Overall, I’m focused on developing practical deep learning and LLM-based systems, with an emphasis on RAG and agent architectures for real-world applications.

---

## Technical Skills

**Programming:** Python · Java · SQL  

**Deep Learning & AI:**  
PyTorch · TensorFlow · Scikit-learn · Self-Supervised Learning · Reinforcement Learning (PPO, SAC, A2C) · Computer Vision · NLP · Pydantic

**LLMs & Generative AI:**  
RAG · ReAct Agents · Prompt Engineering · OpenCLIP · ChromaDB · LangChain · OpenAI API  

**Data & Systems:**  
Pandas · NumPy · OpenCV · Gymnasium · PySpark · Hadoop  

**Systems & Deployment:**  
Docker · Kubernetes · CI/CD · GPU-based Training & Inference · CUDA  


---


## Project Experience

## Deep Learning-Based Predictive Maintenance of Rotating Machinery  
*(University - Industry Collaboration)*  

- Engineered a triaxial vibration data acquisition pipeline on a custom rotor test rig, generating **100K+ vibration signals** across multiple fault conditions.  
- Developed a custom **dual-encoder 1D CNN** combining time-domain waveforms with FFT-based frequency features using channel-wise attention mechanisms.  
- Implemented multi-window signal processing to capture fault progression trends and reduce sensitivity to transient noise.  
- Applied **contrastive self-supervised pretraining**, achieving **91% downstream classification accuracy** while reducing labeled data dependence.  

**Tech:** PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention  

---

## Agentic Multimodal RAG with Hybrid Retrieval  
**[🔗 View Source Code](https://github.com/sarayusd/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git)**

- Built an **agentic multimodal Retrieval-Augmented Generation system** using OpenCLIP, LangChain, ChromaDB, and OpenAI API, indexing **8K+ image-text pairs**.  
- Achieved **84.5% Recall@5 and 0.81 MRR** in text-to-image retrieval evaluation.  
- Architected a ReAct-based LLM agent with tool-driven retrieval and grounded reasoning, achieving **9.06/10 faithfulness** and 3.3% refusal rate.  
- Designed a hybrid ranking pipeline combining dense embeddings with lexical re-scoring to reduce semantic drift and improve grounding robustness.  

**Tech:** OpenCLIP · LangChain · ChromaDB · LLM Agents · Hybrid Retrieval  

---

### Sustainable Energy Management in Smart Homes with Reinforcement Learning  
**[🔗 View Source Code](https://github.com/sarayusd/Sustainable-Energy-Management-with-Reinforcement-Learning.git)**

- Explored intelligent battery storage control in CityLearn environment to minimize energy cost and carbon emissions.  
- Implemented and compared **Rule Based Control**, **PPO**, and **SAC** agents.  
- **SAC** achieved best energy efficiency and lowest peak demand.  
- **Tech:** PyTorch · CityLearn · RL · Python  

---

### Scene Recognition with Deep CNNs (MIT Indoor67)  
**[🔗 View Source Code](https://github.com/sarayusd/Scene-Recognition-with-Deep-CNNs)**

**1. Dense like Teacher (Strong Backbone)**  
- Implemented a custom DenseNet-like architecture from scratch.  
- Used **SE (Squeeze and Excitation)** in bottleneck blocks to improve channelwise attention.  

**2. Hybrid CNN + SE (Student) with Knowledge Distillation**  
- Built a lighter Hybrid CNN with SE blocks for faster inference.  
- Distilled soft targets from the Dense-like teacher so that the student learned richer class boundaries than from hard labels alone.  

**3. Ensemble Learning**  
- Final predictions were ensembled across all trained models:  
  - Dense-like teacher  
  - Distilled Hybrid CNN + SE  
  - Other experimental CNN variants (Mini / Efficient-style)  
- Achieved a project-high **76% F1-score** and enhanced robustness by combining multiple models using soft and weighted ensemble voting.  

- **Tech:** PyTorch · CNN · SE blocks · Knowledge distillation · Ensemble voting
  
---

##  Professional Experience

### Tata Consultancy Services | IT Analyst *(Apr 2018 – Dec 2019)*  
- Developed **Java modules** for trade, location movement, and settlement.  
- Designed SQL queries and stored procedures for high-volume data processing.  
- Collaborated in Agile environment to deliver reliable modules under tight deadlines.

### Capgemini | Associate Consultant *(Nov 2013 – Mar 2018)*  
- Built **RESTful Java services** and microservices for turbine outage data.  
- Delivered production support ensuring smooth operations.  
- Adhered to coding standards, improved maintainability.

---

##  Contact & Profiles

- **GitHub:** [https://github.com/sarayusd]( https://github.com/sarayusd)  
- **LinkedIn:** [https://www.linkedin.com/in/sarayusd/](https://www.linkedin.com/in/sarayusd/)  
- **Email:** sarayusd31@gmail.com  

---

