# Hi, I'm Mihir 👋
Machine Learning Engineer | ML Systems • Time-Series • Reliability

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
</p>

I build **production-oriented ML systems** where labels are missing, noise is high, and failures are expensive.  
My focus is on **how ML behaves under real-world constraints**, not just model accuracy.

---

## What I Work On
- Label-free & weakly supervised ML problems  
- Time-series modeling and drift detection  
- Full ML Lifecycle: Preprocessing, Training, Hyperparameter Tuning, Cross-Validation & Testing
- Offline learning + deterministic online systems  
- Failure modes, alert fatigue, and explainability  

I prefer **statistical ML and explicit objectives** over opaque black-box models when reliability matters.

---

## Featured Project — BLACKICE ❄️  
**Hybrid ML System for Streaming Regime Shift Detection**

<p align="left">
  <img src="https://img.shields.io/badge/ML%20Architecture-Offline%20+%20Online-blue"/>
  <img src="https://img.shields.io/badge/Runtime-O(1)%20Deterministic-success"/>
  <img src="https://img.shields.io/badge/False%20Positives-%3C1%25-critical"/>
  <img src="https://img.shields.io/badge/Noise%20Filtered-80--90%25-brightgreen"/>
</p>

BLACKICE detects **persistent behavioral drift** in infrastructure metrics using a **hybrid ML architecture**:

> **Offline Learning for configuration**  
> **Online Deterministic execution for safety**

### ML Problem
- No labeled data  
- Highly noisy, bursty signals  
- False positives are more costly than delayed detection  
- Black-box anomaly models are hard to debug in production  

### ML Approach
- Streaming statistical baselines (Welford)
- Offline optimization of decision boundaries
- Custom **SRE-weighted loss function**
- Persistence-aware detection instead of point anomalies

### Objective Function
Loss = (False Positives × 5.0) + (Detection Delay × 1.0)

### Impact
- ~80–90% transient noise filtered
- <1% false positives
- O(1) memory per metric stream
- Tested on 8GB+ production-scale time-series data

🔗 Repo: https://github.com/Mihirmaru22/blackice

---

## Other Projects
### Local Fire Weather AI 🌲
**Real-time forest fire risk assessment API**

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white&style=flat-square"/>
</p>

*   **Precision Modeling**: Ridge Regression pipeline with automated feature scaling.
*   **Production Ready**: Serialized Joblib model served via RESTful Flask interface.
*   **Deployment**: Container-friendly structure for AWS/Render.

🔗 [View Code](https://github.com/Mihirmaru22/fwi-prediction-app)

---

## Tech Stack
<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/flask/white"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="38"/>
  </picture>
</p>

---

## Open Source
<p align="left">
  <!-- PyTorch -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="38"/>
</p>

- Contributor to **PyTorch TorchData**
- Fixed a core batching deadlock in the data pipeline ([Merged PR #1522](https://github.com/meta-pytorch/data/pull/1522))
- Documented non-reproducibility when `in_order=False` in `ParallelMapper` ([Merged PR #1523](https://github.com/meta-pytorch/data/pull/1523))
- Added defensive validation + regression tests
- Reviewed under Meta’s OSS process

---

## Currently Learning
<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prometheus/prometheus-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" width="38"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg"/>
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="38"/>
  </picture>
</p>

Distributed systems • ML monitoring • Production ML reliability

---

## Connect
<p align="left">
  <a href="https://github.com/Mihirmaru22">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.simpleicons.org/github/white"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="38"/>
    </picture>
  </a>
  <a href="https://linkedin.com/in/mihir-maru">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="38"/>
    </picture>
  </a>
  <a href="mailto:mihirmaru090@gmail.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="38"/>
    </picture>
  </a>
</p>


