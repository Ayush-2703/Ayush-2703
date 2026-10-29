<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:1E3A8A,100:5B21B6&height=250&section=header&text=AYUSH%20KUMAR%20SINGH&fontSize=60&fontColor=F1F5F9&fontAlignY=36&animation=fadeIn&desc=AI%20%2F%20ML%20Engineer%20%C2%B7%20Researcher%20%C2%B7%20Final-Year%20B.Tech%20(AI)&descSize=18&descAlignY=58)

**I build deep learning systems from first principles, then test them like production software.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushsingh2703/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ab49ayush@gmail.com)
[![Publications](https://img.shields.io/badge/Publications-2%20co--authored-5B21B6?style=for-the-badge)](#-research--publications)
[![CGPA](https://img.shields.io/badge/CGPA-8.48-1E3A8A?style=for-the-badge)](#-education)

**🟢 Open to entry-level ML / AI Engineer and Data / Analyst roles · Research collaborations · Open-source contributions**

</div>

---

## 👋 About Me

<img align="right" width="300" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"/>

I'm a final-year **B.Tech Artificial Intelligence** student at **Amity University Lucknow** (CGPA **8.48**) and a fresher actively looking for my first full-time role in ML / AI engineering.

What sets my work apart is the habit behind it, not the stack:

- **I build from scratch to understand.** Tokenizers, attention layers, LSTMs, training loops, and a pure-Python Transformer, written by hand before I reach for a library.
- **I verify my own claims.** My repos ship tests, CI, and honest results, including bugs, failed experiments, and discrepancies I found in my own reports.
- **I publish.** I co-authored two conference papers, and both have open-source reference implementations you can run.

---

## 🎯 Currently

| | |
|---|---|
| 🧪 **Learning in public** | LLM internals and deep learning through three structured, code-first curricula (NLP, Deep Learning, LLMs) (see [Learning Repositories](#-learning-repositories)) |
| 🔬 **Researching** | Robust watermarking for AI-generated images (contrastive CNN encoder-decoder, PyTorch), a paper in progress |
| 🎓 **Final-year project** | Vision-based, task-agnostic Transformer research |
| 🧩 **Practising** | Data Structures & Algorithms for placement drives, with solutions logged in [LeetCode_Problems](https://github.com/Ayush-2703/LeetCode_Problems) |

---

## 💼 Experience

**AI & Machine Learning Intern · Maincrafts Technology** · *May 2026 – Jul 2026*
- Built and tuned regression models on the **California Housing** dataset in scikit-learn, using engineered features, grid-search hyperparameter tuning, and **5-fold cross-validation** against a linear-regression baseline.

**Generative AI & Agentic Systems Intern · Lenovo LEAP** · *Jun 2026 – Jul 2026*
- Completed a 6-week engineering internship on generative AI architectures: **multi-agent systems, tool-calling pipelines, and LLM-driven workflows** for automated problem-solving.

---

## 📊 GitHub Analytics

<div align="center">
  <img src="./metrics.svg" alt="GitHub Metrics" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ayush-2703/Ayush-2703/output/snake-dark.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/Ayush-2703/Ayush-2703/output/snake.svg" />
  </picture>
</div>

---

## 🔬 Featured Projects

### 🛡️ ACIS Framework: Adversarial ML Security for Construction AI `Dec 2025 – Mar 2026`

AI systems in the built environment are increasingly trusted with real decisions, yet their security is rarely examined. ACIS organises that risk into a **7-vector adversarial threat taxonomy** across 4 AI asset categories. It lets you simulate **five attack classes** (FGSM, PGD, data poisoning, model extraction and backdoor) and evaluate **six defense mechanisms** on three synthetic datasets of 3,700+ samples. A **5-page Streamlit dashboard** and a CLI make live threat assessment possible without touching the code. The project is tested with **35+ unit tests and CI across 3 Python versions**, and it is the **reference implementation of my ICCCIS-2026 paper**.

`Python` `Streamlit` `Adversarial ML` `pytest` `GitHub Actions`

[![Repo](https://img.shields.io/badge/View_Repo-acis__framework-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/acis_framework)

---

### 📊 FT-Transformer: Tabular Deep Learning, Engineered Like a Library `2026`

This is a from-scratch PyTorch implementation of the **FT-Transformer** (Gorishniy et al., 2021), which turns every feature of a table into a token and runs self-attention over them. I benchmarked it on California Housing against Linear, Ridge and tuned Decision Tree baselines, and it reached **24.6% lower RMSE** (3-seed average). I backed the result with ablations on attention heads and depth, a 50-trial Optuna search and a cross-seed stability check, so it isn't a single lucky run. The code is packaged as a library with **50 tests, 98% coverage, Docker and CI on Python 3.10 / 3.11 / 3.12**. While cross-checking my own internship report against the code, I found and fixed two errors, a parameter count (184,321 reported vs **57,131** verified) and an overstated permutation-invariance claim, and documented both in the repo.

`PyTorch` `Optuna` `scikit-learn` `Docker` `CI/CD`

[![Repo](https://img.shields.io/badge/View_Repo-FT--Transformer-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/FT-Transformer)

---

### 🌍 Geodata Processing with AI `May – Jul 2025`

This is an end-to-end pipeline for **ISRO ResourceSat-2 LISS-III** satellite imagery. It covers water-body classification, 8-class land-cover mapping, multi-temporal change detection and figure generation. The first version uses Random Forest and an MLP in scikit-learn. The second version, in PyTorch, combines a **U-Net CNN, stacked BiLSTM/GRU and a Spectral Transformer** through ensemble fusion, using spectral indices (NDVI, NDWI, NDBI, NBR) and gradient-based saliency maps for explainability. Reported results are water accuracy 1.00, land-cover accuracy 0.67 and 5.95% change detected, and the repo has 32 unit tests with GitHub Actions on Python 3.8–3.11. It is the implementation behind my **NCESTSD 2025** paper.

`PyTorch` `rasterio` `Remote Sensing` `CNN` `Transformer`

[![Repo](https://img.shields.io/badge/View_Repo-Geodata__Processing-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/Geodata_Processing)

---

### ⚡ Transformer from Scratch

This repo retraces the full path from **RNN to LSTM to Transformer**, explaining why each step was needed. It implements all three Transformer families: an Encoder (BERT-style), a Decoder (GPT-style) and an Encoder-Decoder for sequence-to-sequence tasks. Every module has a theory note, the derived maths, working code and a plain-language explanation. It also includes a **pure-Python decoder with no PyTorch or NumPy**, so every operation is visible, plus training with a warmup learning-rate schedule, comparison tables, a glossary and a limitations section. Built with a collaborator under faculty guidance, it has 72 commits and is meant to be a reference for anyone learning how LLMs actually work.

`PyTorch` `Self-Attention` `NLP` `LLMs` `Pure Python`

[![Repo](https://img.shields.io/badge/View_Repo-transformer--from--scratch-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/transformer-from-scratch)

---

### 📝 Natural Language Processing: From Word Vectors to Recursive Networks

This is a 24-topic NLP curriculum across five phases that follows the path the field itself took. It starts with word vectors, TF-IDF and t-SNE, moves through bigram and neural language models, then Word2Vec (CBOW, Skip-Gram, negative sampling), matrix factorization, PMI and **GloVe**. It continues into sequence tagging with **HMM and RNN POS taggers and NER**, and ends with recursive networks, including a **Recursive Neural Tensor Network for sentiment on the Stanford Sentiment Treebank**. Each topic ships four parts: a `theory.md` with the derivations, a runnable PyTorch/TensorFlow implementation on real datasets (20 Newsgroups, text8, CoNLL-2003, SST), a line-by-line `explanation.md` and supporting diagrams. The curriculum is anchored in the Bengio, Collobert & Weston and GloVe papers, and the repo has **416 commits**.

`PyTorch` `TensorFlow` `Word2Vec` `GloVe` `HMM` `RNN` `NER`

[![Repo](https://img.shields.io/badge/View_Repo-Natural__Language__Processing-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/Natural_Language_Processing)

---

### 🤖 Large Language Models: A 23-Topic Curriculum

This is a five-phase curriculum that takes LLMs apart topic by topic, from internals to applications and current frontiers. Every one of its **23 topics** has the same three files: `theory.md`, `implementation.py` and `explanation.md`. All code is actually run, and I report what happened, including bugs, instabilities and inconclusive results, instead of showing only the runs that worked. I built it to learn LLMs properly and so that a reader can follow the reasoning and rerun every result themselves.

`LLMs` `PyTorch` `NLP` `Generative AI`

[![Repo](https://img.shields.io/badge/View_Repo-Large__Language__Models-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/Large_languaage_Models)

---

### 🧠 Deep Learning Mastery

This is a six-phase PyTorch curriculum that goes from neural-network foundations through CNNs, RNNs and LSTMs to Transformers, generative AI and MLOps. It uses the same three-file structure per topic as my LLM repo: theory, runnable implementation and a written explanation. Every script is executed, and the results are reported honestly, with bugs and failed experiments documented. Together with the LLM curriculum, it covers **11 structured phases** of self-taught deep learning built on first principles.

`PyTorch` `CNN` `RNN/LSTM` `GenAI` `MLOps`

[![Repo](https://img.shields.io/badge/View_Repo-Deep__Learning-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/Deep_Learning)

---

### 🕵️ AI Job Agent

This project automates the repetitive part of job hunting: finding relevant openings and tailoring a resume to each one. It is written in Python and uses **Gemini 2.5 Flash** together with the **Tinyfish API**. I built it after my Generative AI and Agentic Systems internship at Lenovo LEAP, where I worked on multi-agent systems and tool-calling pipelines. It is a small, practical example of an LLM-driven workflow that does real work for the person using it.

`Python` `Gemini 2.5 Flash` `Agentic AI` `Tinyfish API`

[![Repo](https://img.shields.io/badge/View_Repo-ai__job__agent-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/ai_job_agent)

---

### 🧮 LeetCode Problems

This is a running log of my optimized Python solutions to LeetCode problems, kept to build Data Structures and Algorithms fluency for placement drives. My approach is pattern recognition first: I identify the underlying pattern and struggle with a problem before reading any solution. The goal is not a high solved-count but being able to explain why an approach works and what its time and space complexity is. It sits alongside my ML work because strong engineers need both.

`Python` `DSA` `Problem Solving`

[![Repo](https://img.shields.io/badge/View_Repo-LeetCode__Problems-181717?style=for-the-badge&logo=github)](https://github.com/Ayush-2703/LeetCode_Problems)

---

## 📄 Research & Publications

| Paper | Venue | Role | Code |
|---|---|---|---|
| *Cybersecurity Threats in AI-Driven Construction Systems: A Framework for Adversarial Machine Learning Risks in the Built Environment* | 2nd IETE International Conference on Computing, Communication & Intelligent Systems (**ICCCIS-2026**), Amity University Lucknow | Co-author | [acis_framework](https://github.com/Ayush-2703/acis_framework) |
| *Geodata Processing Using Artificial Intelligence* | **NCESTSD 2025** | Co-author | [Geodata_Processing](https://github.com/Ayush-2703/Geodata_Processing) |

---

## 🛠️ Tech Stack

**AI / ML**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-2C6EBF?style=for-the-badge)

**Data, Analytics & Databases**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge)

**Engineering, DevOps & Cloud**<br>
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

**Skills at a glance**

| Area | Skills |
|---|---|
| **AI & ML** | Machine Learning, Deep Learning, CNNs, Transformer architectures, Transfer Learning, LLMs, NLP, Generative AI, Agentic systems (multi-agent, tool-calling) |
| **Data & Analytics** | Statistical modeling, cross-validation, MySQL, DBMS, Hadoop |
| **CS Fundamentals** | Python, Data Structures & Algorithms, Object-Oriented Programming |
| **Security** | Cybersecurity essentials, network security, adversarial ML, digital forensics concepts |
| **Geospatial** | Satellite image analysis, remote sensing, land-cover classification |
| **Practices** | Unit testing, CI/CD, reproducible experiments, ablation studies |

---

## 🏆 Certifications

| Certification | Domain |
|---|---|
| Oracle Cloud Infrastructure 2025 Certified **AI Foundations Associate** | Cloud AI |
| Oracle Cloud Infrastructure 2025 **Migration Architect** Certified Professional | Cloud Architecture |
| **Data Engineering on AWS: Foundations** | Data Engineering |
| **Cisco Cybersecurity Essentials** | Security |
| **Cybersecurity Job Simulation** (Forage) | Security |
| **Digital Forensics Concepts** (Infosec) | Forensics |
| **Geodata Processing using Python and Machine Learning** | Geospatial AI |
| **Application of AI/ML Model for Specific Crop Acreage Mapping** | Geospatial AI |
| **Remote Sensing and Digital Image Analysis** | Geospatial |
| **MATLAB Onramp** | Scientific Computing |

---

## 🎓 Education

| Degree | Institution | Period | Score |
|---|---|---|---|
| **B. Tech, Artificial Intelligence** | Amity University Lucknow | 2023 – Present | CGPA **8.48/10** |
| Intermediate (10+2) | SDS College, Saran | 2023 | 67.8% |
| Secondary (10) | Shakti Shanti Aademy, Saran | 2023 | 81.2% |

**Languages:** English · Hindi (full professional proficiency) · French (elementary)

---

## 📫 Let's Connect

I'm looking for an **entry-level ML / AI engineering or analyst role** where careful engineering and honest evaluation matter. If you're hiring, researching, or building something interesting in Machine Learning, Deep Learning, LLMs, NLP, or geospatial AI, I'd like to hear from you.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayushsingh2703/)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ab49ayush@gmail.com)

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:020617,50:1E3A8A,100:5B21B6&height=60&section=footer)

</div>
