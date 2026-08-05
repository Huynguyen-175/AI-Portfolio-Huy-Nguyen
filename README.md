# 👋 Hey, I'm Huy Nguyen
> Supply chain graduate · M.S. Finance student · AI, NLP & data enthusiast

I'm a supply chain graduate and current Master of Science in Finance student with additional coursework in artificial intelligence and programming. I enjoy building practical projects in machine learning, natural language processing, and computer vision while combining business knowledge with data-driven problem-solving.

---

## 🎓 Education

- **Master of Science in Finance — In Progress**  
  University of Houston–Clear Lake (UHCL)

- **Bachelor's Degree in Supply Chain and Logistics Technology**  
  University of Houston, Main Campus

- **Selected Computer Science and Artificial Intelligence Coursework**  
  Houston Community College (HCC) — **All courses completed with A grades**

### Completed Coursework

#### Artificial Intelligence

- **Artificial Intelligence History & Foundations** *(ITAI-1370)* — Core concepts, major milestones, and the evolution of AI from early symbolic systems to modern deep learning.
- **Introduction to Machine Learning** *(ITAI-1371)* — Supervised and unsupervised learning, model evaluation, feature engineering, and practical machine-learning workflows.
- **A.I. in Cybersecurity** *(ITAI-1372)* — Applications of machine learning in threat detection, anomaly detection, and security automation.
- **Natural Language Processing** *(ITAI-2373)* — Text preprocessing, embeddings, language models, and end-to-end NLP pipelines.
- **Computer Vision and Artificial Intelligence** *(ITAI-1378)* — Image processing, feature extraction, object detection, and practical computer-vision applications.

#### Programming

- **Programming Fundamentals III** *(COSC 2436)* — Advanced programming concepts and problem-solving in Python.
- **Programming Fundamentals II** *(COSC 1437)* — Intermediate programming concepts and application development in Python.
- **Programming Fundamentals I** *(COSC 1436)* — Programming fundamentals and problem-solving in Java.

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

Always happy to connect about artificial intelligence, finance, supply chain, data analytics, and collaborative projects.

**Email: huynguyen0517@gmail.com**
