# 🎬 Movie Genre Classification from Plot Summaries

## 📌 Project Overview
This project focuses on automatically classifying movie genres based on textual plot summaries using machine learning techniques.  
The task is formulated as a **multi-class supervised text classification problem**, where each movie is assigned a single genre label.

The goal is to build and evaluate models that can learn patterns from movie descriptions and accurately predict their genres.

---

## 🎯 Objectives
- Apply machine learning techniques to a real-world NLP problem  
- Convert unstructured text into meaningful numerical features  
- Train and compare multiple classification models  
- Evaluate performance using appropriate metrics  
- Analyze model strengths and limitations  

---

## 📥 Input & Output
- **Input (X):** Movie plot summary (text)  
- **Output (y):** Predicted movie genre (single label)  

---

## 📊 Dataset
We used the **IMDb Genre Classification Dataset** from Kaggle.

### Dataset Structure:
- `train_data.txt` → Labeled training data  
- `test_data.txt` → Unlabeled test data  
- `test_data_solution.txt` → True test labels  

### Key Statistics:
- ~54,000 training samples  
- ~54,000 test samples  
- 27 different genres  

### Example Genres:
Drama, Comedy, Thriller, Documentary, Horror, Action, Romance, etc.

### Important Observation:
The dataset is **imbalanced**, where some genres (e.g., drama) appear more frequently than others.

---

## ⚙️ Project Pipeline

### 1. Text Preprocessing
- Lowercasing  
- Removing punctuation and noise  
- Text normalization  

### 2. Feature Extraction
- TF-IDF vectorization  
- Converts text into numerical feature vectors  

### 3. Model Training
- Naive Bayes  
- Support Vector Machine (SVM)  
- Logistic Regression  
- Voting Ensemble  

### 4. Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-score (weighted and macro)  

---

## 🤖 Models Used

| Model | Description |
|------|------------|
| Naive Bayes | Baseline probabilistic model for text classification |
| Linear SVM | Effective for high-dimensional sparse data |
| Logistic Regression | Strong linear classifier for multi-class problems |
| Voting Ensemble | Combines predictions from multiple models |

---

## 👥 Team Members
- Joud Alzahrani  
- Norah Alshamsan  
- Walah Alsaeed  
- Norah Alkathiri  
