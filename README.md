# LGAImers 4th

## 📘 Phase 1: Foundational AI Curriculum

This phase covered a wide range of essential AI concepts, from mathematical foundations to advanced deep learning techniques.

### ✅ Course Modules

- **Module 1. AI Ethics**  
  Ethical considerations in the development and use of artificial intelligence.

- **Module 2. Linear Algebra**  
  Topics included eigenvalue decomposition and singular value decomposition.

- **Module 3. Introduction to Machine Learning**  
  Basic concepts and representative algorithms in machine learning.

- **Module 4. Supervised Learning**  
  Regression and classification methods.

- **Module 5. Causal Inference**  
  Understanding causality using Markov models and related techniques.

- **Module 6. Deep Learning Fundamentals**  
  - CNNs for image classification: AlexNet, VGG, ResNet  
  - RNNs and NLP: seq2seq, attention mechanisms, transfer learning, pre-trained models

---

## 📊 Phase 2: Supervised Learning – Classification Task

This phase focused on applying supervised learning methods to solve a practical classification problem using B2B customer data.

### ✅ Practical Modules

- **Module 7. Introduction to B2B Marketing**  
  Understanding B2B markets, customer value, pricing, and value capture.

- **Module 8. Predictive Scoring Model Based on B2B Customer Data**  
  - Techniques for predicting B2B customer behavior  
  - Recommendation algorithms  
  - Logistic regression and artificial neural networks (ANNs)

- **Module 9. LG Electronics Case & Hackathon Overview**  
  - Introduction to LG Electronics' B2B marketing and analytics challenges  
  - Overview of the hackathon task and problem definition

---

## 💻 Code: Multi-Model Defect Classification

This repository contains a machine learning pipeline for a binary classification task using customer data. It utilizes various ensemble and individual classifiers such as Decision Trees, Random Forest, XGBoost, LightGBM, and more.

### 📁 Dataset

- `train.csv`: Training dataset including customer features and a target label (e.g., success/failure of a campaign).
- `submission.csv`: Test dataset with the same features but without labels, used for final prediction.

### 🧹 Preprocessing

1. **Missing Values Handling**
   - Missing values are filled with 0.
   - An alternative method (backfill) is also included but commented out.

2. **Categorical Data Encoding**
   - Categorical (object) columns are encoded using a custom label encoding function.
   - Optionally, object-type columns can be dropped (code commented out).

