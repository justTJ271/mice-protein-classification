# 🧪 Classification of Mice Based on Protein Expression Levels

This project focuses on classifying mice into different categories based on **protein expression levels** in the cerebral cortex. The dataset contains information related to genotype, behavior, and treatment of mice, which are crucial for understanding learning and memory, especially in Down syndrome research.

---

## 📊 Dataset
- **File used:** `Data_Cortex_Nuclear.csv`
- Contains **protein expression levels** of 77 proteins measured across 1,080 instances of mice.
- Includes metadata such as:
  - **Genotype**: Control or Down syndrome
  - **Treatment**: Drug-treated or untreated
  - **Behavior**: Context-shock vs shock-context
  - **Class labels**: Used for classification tasks

---

## 🧠 Project Objectives
1. Preprocess and clean the dataset (handle missing values, normalize features).
2. Perform **exploratory data analysis (EDA)** to understand patterns in protein expression.
3. Build and evaluate multiple **machine learning (ML)** and **deep learning (DL)** models.
4. Identify the best-performing model for classification of mice.

---

## 🛠️ Technologies & Libraries
- **Python**
- **Pandas, NumPy** – data preprocessing
- **Matplotlib, Seaborn** – data visualization
- **Scikit-learn** – ML models (Logistic Regression, SVM, Random Forest, etc.)
- **TensorFlow / Keras** – Deep learning (MLP, CNN)
- **Stratified K-Fold** – model evaluation
- **Confusion Matrix & Accuracy Metrics**

---

## 🧑‍💻 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/justTJ271/mice-protein-classification.git
   cd mice-protein-classification
