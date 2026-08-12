# Data Mining Portfolio

ML assignments: classification, neural networks, ensemble methods, clustering, and ethical considerations.

## 📂 Contents

### Assignment 1: Classification, Regression & Clustering
- **Classification:** J48, Random Forest (99.5% accuracy)
- **Regression:** M5P, SMOreg, Linear Regression
- **Clustering:** K-means, EM (7 segments identified)
- **Association:** Apriori on transaction data

📄 `assignment-1-report.pdf`

### Assignment 2: Neural Networks & Ensemble Methods
- **Part 1 – Neural Networks:** MLP on hypothyroid data (34 attributes, 4 classes)
  - Best architecture: 33–2–4, accuracy ~78%
  - Hyperparameter tuning: LR=0.5, M=0.3
  
- **Part 2 – Ensembles:** Medical mortality prediction (imbalanced, 21% DIE)
  - Bagging: 84.52% accuracy
  - AdaBoost: 0.594 recall (best for minority class)
  - Random Forest: 85.16% accuracy
  - **Vote (best overall): 86.45% accuracy, 0.632 F1**
  - Key lesson: Recall > Accuracy under class imbalance

- **Part 3 – IMDB Data Mining:** 5,043 films
  - Top predictors: critic reviews, user votes
  - 4 market segments identified
  - Random Forest: correlation=0.881

📄 `assignment-2-report.pdf`

### Ethics Presentation: Privacy in Healthcare
- Privacy risks (data breaches, re-identification, misuse)
- Real case: Google DeepMind & NHS (1.6M records without consent)
- Solutions: anonymization, encryption, informed consent

📄 `ethics-presentation.pdf`

---

## 🔑 Key Takeaways

| Topic | Finding |
|-------|---------|
| **Best Classifier** | J48 (99.5%) on structured data; Random Forest on mixed-type |
| **Neural Networks** | MLP optimal at h=2 (small networks avoid overfitting) |
| **Class Imbalance** | Use Recall as primary metric, not Accuracy |
| **Ensembles** | Vote (diverse models) best overall; AdaBoost best for recall |
| **Data Mining Ethics** | Consent + anonymization + encryption non-negotiable |

---

Practical-data-mining-portfolio/
├── README.md
├── ethics-presentation.pdf
├── assignment-1-report.pdf
├── assignment-2-report.pdf
├── A1_Dataset
└── A2_Dataset
    
---

## 🛠 Technologies

Weka, Python, 10-fold cross-validation, preprocessing pipelines

## 📚 Course

COSC 3125: Data Mining | RMIT University (2025)

## 👤 Author

Prathibha Magesh (s3859590)

(Assignments 1–2 also include collaboration with S4068533)
