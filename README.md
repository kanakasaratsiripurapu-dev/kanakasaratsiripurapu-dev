<p align="center">
  <img src="profile.png" alt="Kanaka Sarat Siripurapu" width="170" style="border-radius: 50%;" />
</p>

<h1 align="center">KANAKA SARAT SIRIPURAPU</h1>

<p align="center">
  <b>Software Engineer · Applied AI / GenAI Engineer · Big Data Researcher</b><br>
  Building production-grade backends, distributed Big Data pipelines, and agentic AI systems 🚀
</p>

<p align="center">
  <a href="mailto:kanakasarat.siripurapu@sjsu.edu"><img src="https://img.shields.io/badge/Email-kanakasarat.siripurapu%40sjsu.edu-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/kanakasarat/"><img src="https://img.shields.io/badge/LinkedIn-Kanaka%20Sarat-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  &nbsp;
  <a href="https://leetcode.com/u/kanak_sarat/"><img src="https://img.shields.io/badge/LeetCode-204%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"></a>
  &nbsp;
  <a href="https://sites.google.com/sjsu.edu/saratportfolio/resume"><img src="https://img.shields.io/badge/Portfolio-View-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
</p>

---

## 🧭 Summary

Master's student in **Artificial Intelligence at San José State University** with hands-on experience across the full software development lifecycle — from distributed Big Data pipelines to deployed REST APIs to agentic AI products.

- **Co-author of published research** on HPMR-optimized Hadoop MapReduce for cancer survival analysis (95% accuracy, 30% speed-up over default Hadoop).
- Production focus on **Python, Java, FastAPI, Hadoop / MapReduce, PostgreSQL, Docker, and React** — end-to-end backend systems and ML services.
- Strong fundamentals: **204 LeetCode problems solved** (117 medium · 35 hard), Object-Oriented Design, REST API design, JUnit / pytest software testing.
- **3 additional research papers under submission** in NLP, Computer Vision, and Reinforcement Learning.

---

## 🏆 Achievements & Recognition

### **📄 Published Research — Hadoop MapReduce for Cancer Survival Analysis**
*Co-authored with Pragnyaban Mishra, B. Harsha Vardhan, Rohit Paul · Dept. of CSE, GITAM University*
- HPMR-optimized Hadoop MapReduce on Wisconsin Breast Cancer dataset · **95%** classification accuracy
- **30% speed-up** over default Hadoop via memory + shuffle tuning · scaled to **100 GB** datasets

### **📝 Papers Under Submission (3)**
- *Multi-Label Telugu News Classification using Deep Neural Architectures* (CNN / LSTM / Bi-LSTM, +15-20% over baselines)
- *EfficientNet-B0 for Tomato Leaf Disease Detection* (11-class transfer learning + augmentation pipeline)
- *Crop Disease Detection with CNN + GAN + Attention* (15,000+ leaf images, 0.92 F1-score)

### **💻 LeetCode — 204 Problems Solved**
- **117 Medium · 35 Hard** · ~97% acceptance rate · steady consistency on DSA fundamentals

### **🎯 Production Deployment**
- [SalesPilot](https://salespilot-44lq.onrender.com) — deployed FastAPI backend with live ML scoring and TSP route optimization

---

## 💼 Work Experience

### **AI / ML Engineer @ Innovate** · *May 2024 – Sep 2024 · Chennai, India*
- Engineered an **Extractive Text Summarization** system using TF-IDF, tokenization, and sentence scoring with ROUGE-based evaluation, improving summary coherence by **18%**.
- Built modular **NLP preprocessing pipelines** on large text corpora, reducing end-to-end processing time by **30%**.

### **Machine Learning Engineer @ CodeBeat** · *May 2024 – Jun 2024 · Visakhapatnam, India*
- Developed and benchmarked **Logistic Regression, Random Forest, and XGBoost** on **50K+ clinical records**; achieved **0.91 AUC-ROC** and reduced false negatives by **22%**.
- Designed feature engineering and hyperparameter tuning workflows; improved accuracy by **15%** and scaled inference throughput by **2×**.

### **AI Research Trainee @ Academor** · *Jan 2023 – Aug 2023 · Bengaluru, India*
- Engineered **CNN and GAN architectures** with LBP/Gabor filters, transfer learning, and attention mechanisms for crop disease detection on **15,000+ leaf images**; achieved **0.92 F1-score**.
- Benchmarked **6 deep learning models**, demonstrating **20% improvement** over traditional ML baselines.

---

## 🚀 Featured Projects

### 🔹 [Hadoop MapReduce for Breast Cancer Survival Analysis](https://github.com/kanakasaratsiripurapu-dev/hadoop-mapreduce-cancer-survival)
**Distributed Big Data pipeline backing a published research paper.**
- HPMR-optimized **Java MapReduce** (Mapper / Reducer / Driver) with JUnit-tested OOD threshold logic.
- Containerized **5-node Hadoop cluster** (NameNode, DataNode, ResourceManager, NodeManager, HistoryServer) via Docker Compose; scaled linearly to **100 GB** datasets.
- **Tech:** Java · Apache Hadoop · HDFS · MapReduce · Docker Compose · Maven · JUnit

### 🔹 [SubScout — AI-Powered Subscription Management Agent](https://github.com/kanakasaratsiripurapu-dev/CMPE-Fall25-Kanakasarat-Siripurapu-subscription-cancelling-agentic-app) `(Ongoing)`
**Agentic AI backend that scans Gmail and auto-detects subscriptions.**
- FastAPI REST API with **Celery + Redis** async task queues for scheduled Gmail scans.
- **Google OAuth 2.0** + LLM prompt pipeline to extract subscription metadata (cost, renewal date, cancellation link) from raw email text.
- Encrypted-credentials **PostgreSQL** schema; full stack containerized via Docker Compose.
- **Tech:** Python · FastAPI · Celery · Redis · PostgreSQL · Docker Compose · Google OAuth · LLM

### 🔹 [SalesPilot — Sales Route & Deal Prioritization Backend](https://github.com/kanakasaratsiripurapu-dev/salespilot) · [Live Demo](https://salespilot-44lq.onrender.com)
**Deployed production backend** that scores accounts and generates TSP-optimized visit routes.
- **XGBoost** classifier in a Scikit-learn Pipeline (One-Hot Encoding, log1p, stratified 70/15/15 split) scoring deal-closure probability.
- TSP route optimization via **OR-Tools** (GUIDED_LOCAL_SEARCH) with nearest-neighbour fallback and haversine distance.
- Deployed on **Render** with managed PostgreSQL and a **Leaflet.js** frontend.
- **Tech:** Python · FastAPI · PostgreSQL · XGBoost · OR-Tools · Leaflet.js · Docker · Render

### 🔹 [Object Detection — End-to-End ML Service (YOLOv8 + Web UI)](https://github.com/kanakasaratsiripurapu-dev/dl-assignment)
**Production-style ML serving with web frontend.**
- FastAPI inference server exposing REST endpoints for image upload and real-time detection.
- Optimized serving latency by exporting models to **ONNX** and **TensorRT**; benchmarked speed-vs-accuracy across runtime backends.
- **React (Vite)** single-page frontend for interactive image upload and bounding-box visualization.
- **Tech:** Python · FastAPI · React (Vite) · PyTorch · ONNX · TensorRT · Docker

### 🔹 [Top-K Recommender Systems on Myket App Install Dataset](https://github.com/kanakasaratsiripurapu-dev/recommender_systems)
**Temporal Top-K recommender pipeline on 694K interactions.**
- Implemented **collaborative filtering, RP3-beta, EASE, and ItemKNN** algorithms from scratch in NumPy / SciPy.
- Shared evaluation framework with global temporal 80/10/10 split and metadata-aware hybrid variants.
- **Tech:** Python · NumPy · Pandas · SciPy · scikit-learn

### 🔹 [Adaptive Ad Click Optimization — Multi-Armed Bandits](https://github.com/kanakasaratsiripurapu-dev/adaptive-ad-click-optimization-bandits)
**RL algorithms benchmarked on real-world CTR data.**
- Implemented **Epsilon-Greedy, UCB1, and Thompson Sampling** on simulated CTR + the **Avazu CTR** dataset.
- Evaluated under stationary and non-stationary (drift) conditions; Thompson Sampling achieved lowest cumulative regret.
- **Tech:** Python · NumPy · Matplotlib

### 🔹 [Multi-Label Telugu News Classification](https://github.com/kanakasaratsiripurapu-dev/multilabel-telugu-news-classification)
**Low-resource NLP — CNN / LSTM / Bi-LSTM classifiers.**
- Improved **F1-score from 0.78 → 0.89** via 5-fold cross-validation across 6 multi-label categories.
- 20+ domain-specific NLP features; comparative study of 5 ML/DL models (paper under submission).
- **Tech:** Python · TensorFlow · Keras · scikit-learn · NLTK

### 🔹 [EfficientNet-B0 — Tomato Leaf Disease Detection](https://github.com/kanakasaratsiripurapu-dev/efficientnet-tomato-leaf-disease)
**11-class transfer-learning classifier with Augmentor pipeline.**
- EfficientNet-B0 backbone + BatchNorm + Dense(256) + Dropout(0.5) + softmax head.
- End-to-end evaluation suite (weighted P/R/F1, per-class ROC-AUC, Jaccard, confusion matrix); paper under submission.
- **Tech:** Python · TensorFlow · Keras · EfficientNet-B0 · OpenCV · Augmentor

---

## 🛠 Tech Stack

### **Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### **Backend & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### **Big Data & Distributed Systems**
![Hadoop](https://img.shields.io/badge/Apache_Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![HDFS](https://img.shields.io/badge/HDFS-007ACC?style=for-the-badge)
![MapReduce](https://img.shields.io/badge/MapReduce-F89820?style=for-the-badge)

### **ML / AI / GenAI**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white)

### **DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### **Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

### **Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

### **Engineering Practices**
**Object-Oriented Design** · **Data Structures & Algorithms** · **REST API Design** · **Software Testing (JUnit, pytest)** · **Agile** · **Code Review** · **Technical Documentation**

---

## 🎓 Education

🎓 **Master of Science (M.S.) in Artificial Intelligence**
San José State University · San Jose, CA · *Aug 2025 – May 2027 (Expected)* · **GPA: 3.5 / 4.0**
*Coursework: Data Structures & Algorithms · Machine Learning · Deep Learning (CNNs, RNNs, LSTMs, GANs) · Reinforcement Learning · Natural Language Processing*

🎓 **Bachelor of Technology (B.Tech) in Computer Science (AI & ML)**
Gandhi Institute of Technology and Management (GITAM) · Visakhapatnam, India · *Oct 2021 – Jul 2025*
*Coursework: Data Structures & Algorithms · Object-Oriented Programming · Software Engineering · Operating Systems · Database Management Systems*

---

## 📜 Certifications

- **Programming Fundamentals** — Duke University (Coursera)
- **Python Data Structures** — University of Michigan (Coursera)
- **Regression Models** — Johns Hopkins University (Coursera)

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kanakasaratsiripurapu-dev&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kanakasaratsiripurapu-dev&layout=compact&theme=default&hide_border=true&hide=html,css&langs_count=8" alt="Top Languages" height="160">
</p>

---

<p align="center">
  <em>Open to <b>Software Engineering · Applied AI · ML Engineering · Backend</b> internships and full-time roles.</em><br>
  <em>Let's build something great. ✨</em>
</p>

<p align="center">⭐ From kanakasaratsiripurapu-dev</p>
