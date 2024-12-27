# Lung Cancer Prediction Using Machine Learning

## **Description**
This project focuses on developing and evaluating machine learning models to predict lung cancer based on clinical and behavioral features. Using advanced algorithms such as Logistic Regression, Random Forest, and Support Vector Machines (SVM), the goal is to create an accurate and reliable system for early detection of lung cancer. By identifying individuals at higher risk, the project aims to enable timely medical intervention and improve treatment outcomes.

The dataset includes key features such as:
- **Demographics**: Gender and age
- **Behavioral Factors**: Smoking, alcohol consumption, peer pressure
- **Clinical Symptoms**: Chronic diseases, fatigue, wheezing, coughing, chest pain

The project also addresses challenges like class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)** and selects key features with **RFE (Recursive Feature Elimination)** to enhance the performance of the models.

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**: 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `imblearn`
  - Algorithms: Logistic Regression, Random Forest, SVM

## **Benefits**
- **Early Detection**: Identifies individuals at risk of lung cancer, enabling timely intervention.
- **Improved Outcomes**: Enhances the chances of successful treatment through early diagnosis.
- **Feature Insights**: Highlights the influence of behavioral and clinical factors in lung cancer prediction.

## **Applications**
1. **Healthcare**: Assists medical professionals in diagnosing and monitoring lung cancer risk.
2. **Public Health**: Helps in creating awareness about the impact of smoking and other risk factors.
3. **Research**: Provides a basis for further studies on lung cancer and predictive analytics.

## **Project Highlights**
### Aim of the Project
The primary aim of this project is to develop and evaluate machine learning models that can predict lung cancer based on a range of clinical and behavioral features. By using various machine learning techniques, such as Logistic Regression, Random Forest, and Support Vector Machines (SVM), the project seeks to identify which algorithm performs best in predicting lung cancer. The project’s goal is to build a robust, accurate model capable of identifying individuals who are at a higher risk of developing lung cancer, thereby enabling early intervention and improving the chances of successful treatment. Additionally, the project aims to explore the influence of different factors, such as smoking and chronic diseases, in predicting lung cancer and to assess the model's performance through metrics such as accuracy, precision, recall, and ROC-AUC scores.

### Key Findings
- **Performance Metrics**:
  - Random Forest achieved the highest accuracy of **95%**.
  - SVM followed with an accuracy of **93%**.
  - Logistic Regression achieved an accuracy of **82%**.
- **Feature Selection**: Recursive Feature Elimination (RFE) was used to identify the most important features, improving model efficiency and interpretability.
- **Class Imbalance Handling**: SMOTE was employed to address the imbalance in the dataset, ensuring fair training for the models.

### Conclusion
This project underscores the transformative potential of machine learning in the early detection of lung cancer, a critical step toward improving patient outcomes and saving lives. By leveraging algorithms such as Logistic Regression, Random Forest, and Support Vector Machines, we successfully developed predictive models capable of identifying individuals at high risk of developing lung cancer with notable accuracy and reliability.

Among the models evaluated, **Random Forest** emerged as the most effective, offering the best balance between precision, recall, and accuracy. Factors such as smoking and chronic diseases were found to be significant predictors of lung cancer, reinforcing their importance in early detection efforts. By employing advanced techniques like SMOTE and RFE, the project successfully addressed challenges and delivered actionable insights.

This project serves as a testament to the power of machine learning in healthcare, providing a foundation for further advancements in predictive analytics and early disease detection.
