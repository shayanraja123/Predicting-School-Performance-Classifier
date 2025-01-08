# Predicting School Performance

Building a classifier to predict school performance levels (high or low) based on test scores and socioeconomic, demographic, and academic features. The project leverages machine learning models, including KNN, Decision Trees, SVM, and Naive Bayes, to optimize educational resource allocation and enhance data-driven decision-making.

This repository contains the **Hadoop Heroes Project**, a data-driven initiative aimed at classifying schools in the Phoenix metropolitan area as high- or low-performing based on test scores and other demographic, socioeconomic, and academic features. By identifying key factors influencing school performance, this project seeks to optimize resource allocation, guide policy-making, and enhance student outcomes.

---

## 📜 **Project Overview**

The project tackles the problem of school categorization based on performance levels, with the primary objective of improving educational equity. It uses a dataset of 344 schools, containing 24 features such as student-teacher ratio, funding per student, AP participation rates, and standardized test scores.

### **Objectives**
1. Classify schools as high-performing or low-performing based on the Arizona School Score.
2. Identify key factors that influence school performance.
3. Enable optimized resource allocation and policy-making through actionable insights.

---

## 🚀 **Key Highlights**

### **Technical Approach**
1. **Data Preprocessing**:
   - Cleaned and transformed the dataset.
   - Created a binary target variable by splitting the Arizona School Score into high-performing (6–10) and low-performing (0–5).
   - Scaled features using StandardScaler for consistency across models.

2. **Machine Learning Models**:
   - **K-Nearest Neighbors (KNN)**:
     - Achieved the best performance with an accuracy of 67% and F1 score of 0.78.
   - **Decision Trees**:
     - High precision (76%) but slightly lower overall accuracy (67%).
   - **Support Vector Machines (SVM)**:
     - Moderate accuracy (54%) and ROC AUC (0.53).
   - **Naive Bayes**:
     - Struggled with imbalanced data, achieving 44% accuracy.

3. **Hyperparameter Tuning**:
   - Used GridSearchCV to optimize model parameters for KNN, resulting in the best configuration of neighbors, weights, and distance metrics.

4. **Evaluation Metrics**:
   - Accuracy, Precision, Recall, F1 Score, and ROC AUC.

---

## 📊 **Key Findings**

1. **Top Predictors of Performance**:
   - AP Participation rates.
   - Funding per student.
   - Teacher qualification and student-teacher ratio.
   - Demographic attributes (e.g., ethnic composition and gender ratios).

2. **Best Model**:
   - **KNN**:
     - Accuracy: 67%.
     - F1 Score: 0.78.
     - ROC AUC: 0.56.

3. **Insights**:
   - Schools with better funding, higher teacher qualifications, and higher AP participation tend to perform better.
   - Imbalances in demographic and socioeconomic factors influence school outcomes.

---

## 🌟 **Impact and Implications**

This project enables:
- **Targeted Resource Allocation**: Identify low-performing schools for tailored interventions and resource distribution.
- **Policy Development**: Inform educational policies to address systemic disparities.
- **Proactive Measures**: Support schools at risk of declining performance with preemptive action.

---

## 🛠️ **Technologies Used**

- **Programming Language**: Python
- **Libraries**: 
  - Pandas, NumPy for data processing.
  - Scikit-learn for modeling and evaluation.
  - Seaborn and Matplotlib for visualization.
- **Machine Learning Algorithms**: 
  - K-Nearest Neighbors, Decision Trees, Support Vector Machines, Naive Bayes.

---

## 💡 Future Directions
1.	**Addressing Data Imbalance**:
•	Use advanced sampling techniques (e.g., SMOTE) to balance the dataset.
2.	**Feature Engineering**:
•	Include additional features such as attendance rates and detailed funding metrics.
3.	**Advanced Modeling**:
•	Explore ensemble methods like Random Forests and Gradient Boosted Trees for improved accuracy.
4.	**Geographic Adaptability**:
•	Tailor the model for other regions with different educational standards.
5.	**Ethical AI Practices**:
•	Mitigate biases to ensure equitable outcomes.

---

## 🔗 **Portfolio & Contact**

This project is part of my Data Science Portfolio, showcasing my expertise in tackling real-world problems using data science. For any inquiries or collaborations, feel free to reach out via:
-	Email: shayan.raja123@gmail.com
- LinkedIn: https://www.linkedin.com/in/shayanraja
