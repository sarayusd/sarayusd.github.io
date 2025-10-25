---
layout: default
title: Featured AI/ML Projects
---

#  Welcome to My AI/ML Portfolio

I’m a **Master’s student in Artificial Intelligence at the University at Buffalo** with 5+ years of software engineering experience.  
I specialize in **Deep Learning, Reinforcement Learning, and Computer Vision**, and I enjoy building **end-to-end AI solutions** with real-world impact.

---

## Technical Skills

- **Programming Languages:** Python, Java, SQL  
- **ML & Data Frameworks:** PyTorch, Scikit-learn, Pandas, NumPy, OpenCV, Gymnasium, PySpark, Hadoop  
- **Visualization:** Matplotlib, Seaborn  
- **Databases:** MySQL, Oracle  
- **Tools:** Git, Bitbucket, Maven, MATLAB, Jupyter Notebook

---

# Sustainable Energy Management in Smart Homes with Reinforcement Learning  
**[🔗 View Source Code]( https://github.com/sarayusd/Sustainable-Energy-Management-with-Reinforcement-Learning.git)**

This project explores intelligent **battery storage control** in a **single building** energy system using the [CityLearn](https://www.citylearn.net/) simulation environment.  
The goal is to minimize energy cost, reduce carbon emissions, and flatten peak loads through learning-based control strategies, comparing traditional **Rule Based Control** with advanced RL algorithms **PPO** and **SAC**.

We compare:
- **Rule Based Control (RBC)** baseline strategy  
- **Proximal Policy Optimization (PPO)** (on-policy)  
- **Soft Actor-Critic (SAC)** (off-policy with entropy regularization)

---

##  Problem Overview
- Urban buildings create peak loads during expensive and carbon intensive periods.
- A battery can charge during off-peak/solar hours and discharge during peak hours to flatten the load curve.
- We train RL agents to learn this control policy automatically.

---

## 🧪 Simulation Setup
- **Environment:** CityLearn 2022 dataset  
- **Scenario:** Single building, centralized control  
- **Simulation Window:** 7 days  
- **Key Observations:** hour, net consumption, price, carbon intensity, solar generation, SoC  
- **Action:** continuous in [-1, 1]  
  - `-1` = discharge  
  - `0` = idle  
  - `1` = charge

---

##  Reward Design
The reward combines:
- Energy penalty  
- Electricity cost  
- Carbon penalty  
- Peak demand penalty  

It incentivizes:
- Charging during solar/off-peak periods   
- Discharging during high-price and high-carbon hours 
- Avoiding demand spikes.

---

##  Results

###  Rule-Based Controller (Baseline)

| Metric              | Result        |
|----------------------|---------------|
| Avg Reward           | 38.02         |
| Net Energy (kWh)     | -15.84        |
| Peak Load (kW)       | 2.76          |

---

###  PPO Agent

| Metric              | Result (Approx) |
|----------------------|-----------------|
| Avg Reward           | 35–36           |
| Net Energy (kWh)     | -14.5           |
| Peak Load (kW)       | 3.4–5.0         |
| Cost ($)             | -4.15          |

- Adaptive control, slower convergence than SAC.

---

###  SAC Agent

| Metric              | Result          |
|----------------------|-----------------|
| Avg Reward           | 38.80          |
| Net Energy (kWh)     | -16.31         |
| Peak Load (kW)       | 2.76           |
| Cost ($)             | -4.64          |

- Best performing agent with lowest cost and peak load.  
- Maintains low peak demand and high reward across episodes.

---

##  Tech Stack
- Python 3  
- PyTorch  
- CityLearn  
- NumPy / Pandas / Matplotlib

---

## Future Work
- Extend to multi-building control and demand response programs.  

---

#  Scene Recognition with Deep CNNs (MIT Indoor67)  
**[🔗 View Source Code]( https://github.com/sarayusd/Scene-Recognition-with-Deep-CNNs.git)**

This project focuses on **indoor scene classification** using the MIT Indoor67 dataset.  
Indoor scene recognition is challenging due to high intra-class variability, clutter, and reliance on object-level cues rather than global layouts.  
We implement and compare multiple deep learning architectures and combine them using **ensemble learning** to improve accuracy and robustness.

---

## 🧾 Dataset Description

- **Dataset:** [MIT Indoor67](http://web.mit.edu/torralba/www/indoor.html)  
- **Classes:** 67 indoor categories (e.g., bookstore, kitchen, auditorium)  
- **Images:** 15,620 total  
- **Split:** standard train/val/test  
- **Input:** 224×224 RGB images  
- **Metrics:** Top-1 accuracy, macro/weighted F1, confusion matrix

### Preprocessing
- Train: random crops, flips, rotations, color jitter, normalization  
- Val/Test: resize + normalization

### Class Imbalance Handling
- Used class weights, label smoothing, weighted sampling, and targeted fine-tuning.

---

## Model Architectures

### 1. DenseNet-Like Scene Classifier (Teacher)
- 58-layer DenseNet-style CNN  
- 9.9M parameters  
- **Train Acc:** 79.6% | **Test Acc:** 62.1%  
- Macro F1: 0.60 | Weighted F1: 0.62

---

### 2. MiniEfficientNet (Student, KD)
- Lightweight MBConv + SE modules (~1.2M params)  
- With **knowledge distillation** from teacher  
- **Test Acc:** 61.5% | Macro F1: 0.59 | Weighted F1: 0.63  
- Significant F1 boost for low-performing classes

---

### 3. Ensemble (Soft & Weighted Voting)

| Model                 | Acc | Macro F1 | Weighted F1 |
|-----------------------|-----|----------|-------------|
| DenseNet (Teacher)    | 62% | 0.60     | 0.62        |
| MiniEfficientNet      | 61.5% | 0.59   | 0.63        |
| **Weighted Voting**   | **77%** | **0.80** | **0.76**  |

- Soft & weighted ensemble improved accuracy and robustness across rare classes.

---

## Performance Highlights
- DenseNet: robust feature extractor  
- MiniEfficientNet + KD: lightweight and accurate  
- Ensemble: boosted performance to 77% accuracy and 0.80 macro recall

---

## Tech Stack
- Python 3  
- PyTorch · Torchvision  
- NumPy · Pandas · scikit-learn  
- Matplotlib · tqdm

---

##  Future Work
- Incorporate ViT backbones for richer features  
- Deploy lightweight student models on edge devices.

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

