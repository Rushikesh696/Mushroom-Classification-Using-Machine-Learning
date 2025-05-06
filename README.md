# 🍄 Mushroom Classification using Machine Learning

This project uses machine learning algorithms to classify mushrooms as **edible** or **poisonous** based on their physical characteristics. The dataset used is the [UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom), which contains 8124 instances and 22 categorical features.

## 📁 Dataset Description

Each record in the dataset represents a mushroom sample with features such as:

- Cap shape, surface, and color
- Odor
- Gill attachment, spacing, and size
- Stalk shape and color
- Habitat and population

The target variable (`class`) indicates whether the mushroom is:
- `e`: Edible
- `p`: Poisonous

All features are categorical and require encoding.

---

## ⚙️ Technologies Used

- Python 3.x
- Pandas
- Scikit-learn
- NumPy
- Matplotlib / Seaborn

---

## 📊 Algorithms Applied

The following supervised learning models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Decision Tree Classifier

---

## ✅ Results

| Algorithm             | Accuracy |
|----------------------|----------|
| Logistic Regression  | 95%      |
| KNN                  | 99%+     |
| SVC                  | 99%+     |
| Decision Tree        | 100%     |

**Note**: While the Decision Tree achieved perfect accuracy, this may indicate overfitting.

---

## 🔍 Key Features

- Complete data preprocessing pipeline (label encoding, train-test split)
- Accuracy comparison of multiple models
- Plans for cross-validation, confusion matrix analysis, and feature importance
- Safe and reliable classification for real-world mushroom identification

## Conclusion
In this project, I explored the use of various machine learning algorithms to classify mushrooms as edible or poisonous based on their physical attributes. The results demonstrated that the dataset is highly separable, allowing models like Decision Tree, K-Nearest Neighbors, and Support Vector Classifier to achieve remarkably high accuracy, with Decision Tree even reaching 100% accuracy on the test set.

While this level of performance is promising, it also raises the possibility of overfitting, especially for the Decision Tree model. This highlights the importance of performing additional evaluations such as cross-validation, confusion matrix analysis, and testing on unseen data to ensure generalization.

Overall, the project confirms that machine learning can be a valuable tool for reliable and efficient mushroom classification, with real-world implications for health and safety.

