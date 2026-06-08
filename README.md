<h1 align="center">Mahesh Kumar Tippanu</h1>

<h3 align="center">
M.Tech Researcher &nbsp;·&nbsp; Federated Biometric Security &nbsp;·&nbsp; Unsupervised Anomaly Detection &nbsp;·&nbsp; Trustworthy AI
</h3>

<p align="center">
  GITAM University, Visakhapatnam &nbsp;·&nbsp; maheshkumartippanu@gmail.com
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mahesh-kumar-tippanu-343237a5/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:maheshkumartippanu@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/mahesh-kumar-tippanu-343237a5/">
    <img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=mahesh-tippanu&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="profile views"/>
</p>

---

## 🔬 Research Focus

I work on **unsupervised attack detection for federated biometric systems** — specifically,
detecting multi-face registration attacks in distributed face recognition without labeled
attack data or centralised data access.

My M.Tech thesis proposes a **dual-signal anomaly detection framework** combining:
- **PCA subspace residual scoring** — reconstruction inconsistency relative to an enrolled identity cluster
- **Cosine dispersion scoring** — heterogeneity measure across all enrolled embeddings for an account

Both signals are fused and evaluated on **ArcFace-ResNet50 embeddings** across **20 non-IID
federated clients** without any labeled attack samples at training or inference time.

> *To the best of our knowledge, enrollment-time detection of multi-face registration attacks
> in federated face recognition remains largely unexplored.*

---

## 📊 Thesis Results

**Dataset:** CelebA &nbsp;·&nbsp; 6,540 identities &nbsp;·&nbsp; 20 non-IID clients (Dirichlet partition)
**Embedding model:** ArcFace-ResNet50 via ONNX Runtime

| Detector Configuration | AUC | Notes |
|---|---|---|
| Baseline-V1 — Cosine Dispersion only | 0.497 | Near-random; dispersion alone insufficient |
| Detector-V2 — PCA Subspace Residuals | 0.700 | Significant improvement via subspace modelling |
| **Fusion (α = 0.5)** | **0.740** | **TPR@1%FPR = 46.7% — best configuration** |

**Key finding:** Enrollment-time integrity verification is achievable without labeled attack
samples, raw data sharing, or centralised training.

---

## 📄 Publications

### ✅ WiDS 2026 — Accepted, Peer-Reviewed

**"A Dual-Signal Unsupervised Framework for Multi-Face Registration Attack Detection
in Federated Face Recognition"**

- 9th International Conference for Women in Data Science (WiDS 2026)
- Prince Sultan University, Riyadh, Saudi Arabia · September 2026
- Authors: Sultan Ahmad, **Tippanu Mahesh Kumar**, Eali Stephen Neal Joshua,
  Abu Taha Zamani, Deepa Sonal

---

### 🔄 IJCB 2026 — Under Review

**"A Dual-Signal Unsupervised Framework for Multi-Face Registration Attack Detection
in Federated Face Recognition"**

- IEEE/IAPR International Joint Conference on Biometrics 2026
- Rome, Italy
- Extended experimental evaluation on CelebA (6,540 identities, 20 non-IID clients)
- Grant: PSAU/2025/01/39033

---

## 🧠 Research Interests

- Unsupervised anomaly detection in biometric enrollment systems
- Federated and privacy-preserving machine learning
- One-class learning and representation learning for security
- Explainable AI for high-risk biometric applications
- Trustworthy AI under EU AI Act constraints
- Differential privacy and secure distributed inference

---

## 🔍 Open Research Questions (PhD Agenda)

The current thesis results expose four open problems that define my PhD research direction:

| # | Research Question | Current Gap |
|---|---|---|
| RQ1 | Can client-adaptive α weighting outperform fixed fusion? | α=0.5 ignores per-client distribution |
| RQ2 | Can per-client PCA capture local distribution shifts? | PCA not adapted to client-specific data |
| RQ3 | Does the framework generalise beyond CelebA? | Single-dataset evaluation only |
| RQ4 | Can anomaly signals be made interpretable? | Scores are opaque scalar outputs |

---

## ⚙️ Technical Stack

**Research & ML:**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge)
![Federated Learning](https://img.shields.io/badge/Federated_Learning-1F6FEB?style=for-the-badge)

**Backend & AI Systems:**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121D33?style=for-the-badge)
![Flowise](https://img.shields.io/badge/Flowise-FF6B6B?style=for-the-badge)

**Languages:**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

---

## 🎓 Education

**M.Tech, Computer Science & Engineering**
GITAM University, Visakhapatnam · 2024–2026
CGPA: 8.58/10 · O Grade (10/10 SGPA) in both project semesters
*Supervisor: Dr. Eali Stephen Neal Joshua*

**B.Tech, Civil Engineering**
Andhra University, Visakhapatnam · 2017–2021

---

## 💼 Industry Experience

**AI Agentic Engineer** — Nova3Ark, Bangalore · Sept 2025–Present
Architecting multi-component AI inference pipelines, LLM orchestration systems,
and production agentic workflows.

**Python Developer** — Paccore IT Solutions, Hyderabad · Feb–Oct 2023
Backend API development, async refactoring, production system debugging.

**Apprentice Engineer** — BridgeLabz Solutions, Mumbai · Mar 2022–Jan 2023
Full-stack Java training: Spring Boot, REST APIs, Hibernate, MySQL.

---

## 📈 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=mahesh-tippanu&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahesh-tippanu&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mahesh-tippanu&theme=tokyonight&hide_border=true" />
</p>

---

## 🌐 Connect

<p align="left">
  <a href="https://github.com/mahesh-tippanu">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/mahesh-kumar-tippanu-343237a5/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:maheshkumartippanu@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://hashnode.com/@MTippanu">
    <img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>Open to PhD positions in Computer Vision · Federated Learning · Biometric Security · Trustworthy AI</i>
</p>
