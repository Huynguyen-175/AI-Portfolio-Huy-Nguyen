# 👋 Hey, I'm Huy Nguyen
> NLP & LLM builder · AI student at HCC · Aspiring BAT transfer

I'm an NLP/LLM enthusiast who loves turning language models into useful things. I build projects around prompt engineering, fine-tuning, RAG pipelines, and AI-powered tools — and share everything here. If it involves text and intelligence, I'm probably tinkering with it.

---

## 🎓 Education

Currently pursuing an **A.S. in Computer Science** at Houston Community College (HCC), with a focus on AI and machine learning. Completing coursework to transfer into the **Bachelor of Applied Technology (BAT)** program — working toward turning this passion into a full four-year degree.

**Courses completed:**

- **Artificial Intelligence History & Foundations** *(ITAI-1370)* — Core concepts, milestones, and the evolution of AI from early symbolic systems to modern deep learning.
- **Intro to Machine Learning** *(ITAI-1371)* — Supervised/unsupervised learning, model evaluation, feature engineering, and practical ML workflows.
- **A.I. in Cybersecurity** *(ITAI-1372)* — Applying ML to threat detection, anomaly detection, and security automation.
- **Natural Language Processing** *(ITAI-2373)* — Text preprocessing, embeddings, language models, and building NLP pipelines — the heart of my focus area.

---

## 🚀 Featured Projects

### 🦺 PPE Compliance Agent *(ITAI-1378 — Computer Vision)*
[🔗 View on GitHub](https://github.com/Huynguyen-175/ITAI1378_Final_PPEComplianceAgent)

A full perceive → reason → act CV agent, not just a detector — built to automatically verify PPE (mask) compliance for home health caregivers from a photo. A fine-tuned YOLOv8n model (90% mAP@0.5 on a 4,547-image dataset) feeds structured detections into an explicit rule-based reasoning layer, which logs every decision as a full inspectable JSON trace and outputs an annotated image + compliance report. Wrapped in an interactive Gradio demo. Real evaluation on 20 labeled test images hit a 95% task success rate — and surfaced a genuine reasoning-layer bug (a low-confidence false positive silently overriding correct detections) that I root-caused, fixed, and regression-tested, plus a second perception-layer limitation documented for future work.

`Python` `YOLOv8` `Ultralytics` `OpenCV` `Gradio` `Computer Vision` `Agent Design`

---

### 🚗 Used Car Price Prediction *(ITAI-1371 — Intro to Machine Learning)*
[🔗 View on GitHub](https://github.com/Huynguyen-175/ITAI1371-Midterm-Group5-HUY-NGUYEN---ABRAHAM-BARRETO---SANDHYA-CHAMAKURI)

A supervised regression project built to predict used car asking prices from real-world listings data. Working with a Kaggle dataset of 9,582 records scraped from an Indian auto marketplace, our team handled the full ML pipeline — parsing messy raw strings, imputing missing values, removing duplicates, engineering features, and encoding categoricals. We then trained and compared three models (Linear Regression, Random Forest, and XGBoost) evaluated on MAE, RMSE, and R².

`Python` `Scikit-learn` `XGBoost` `Pandas` `Feature Engineering` `Regression`

---

### 🤖 NewsBot Intelligence System *(ITAI-2373 — Natural Language Processing)*
[🔗 View on GitHub](https://github.com/Huynguyen-175/ITAI2373-NewsBot-Midterm)

An end-to-end NLP pipeline that automatically processes, categorizes, and extracts insights from news articles. Built on the BBC News dataset (~1,490 articles across 5 categories), NewsBot integrates all core NLP techniques — text preprocessing, TF-IDF feature extraction, POS tagging, dependency parsing, sentiment analysis, multi-class classification, and named entity recognition — into a single cohesive system. Best model (Linear SVM) achieved ~97% accuracy.

`Python` `spaCy` `NLTK` `Scikit-learn` `VADER` `TF-IDF` `NER` `Google Colab`

---

## 📬 Let's Connect

Always happy to chat, collaborate, or just geek out over prompts and LLMs.

**Email: huynguyen0517@gmail.com**
