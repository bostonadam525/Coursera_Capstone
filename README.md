# IBM Data Science Professional Certificate Capstone Course - Predicting Cardiovascular Disease
Submissions by Adam Lang

This was the final project I completed for the IBM Data Science Professional Certificate Program on coursera.
The project has 3 parts:
1. Python Jupyter Notebook
2. Written Report in Microsoft Word (pdf document)
3. PowerPoint Presentation (pdf document)

Summary of Dataset:
- Kaggle dataset
- 70,000 patients
- 11 features
- Cardiovascular (CVD) target variable
- 5 categorical variables
- 5 continuous variables

Summary of the Project:
- The project was predicting cardiovascular disease using machine learning algorithms of SVM, KNN, Random Forest, and Naive Bayes.
- Feature Scaling was performed using Robust Scaling.
- Exploratory Data Analysis using data visualization techniques in Matplotlib and Seaborn. 
- Inferential statistics revealed the highest correlation between continuous variables was seen with Weight and BMI (0.760). This was not explored further though other than Pearson correlation and correlation heatmap. 
- Machine Learning algorithm optimization using GridSearchCV library from scikit-learn. The RBF SVM algorithm was the most accurate model. 
- 10 folds cross validation was performed to validate the models. 
- Random Forest variable importance revealed the most important predictors of cardiovascular disease were: Height, Age By Decade, Cholesterol, Weight, Age, Gender.
- Worst predictors of CVD were: Obesity, Systolic BP, Alcohol, Activity level, BMI. 
- **Overall the best model was the Support Vector Machine (SVM) with an accuracy of 74%. Precision was 0.78, Recall was 0.72, F1 score was 0.72, Jaccard Index was 0.74. Ensemble model average (of all models) was 72.2% accuracy.**
- KNN algorithm was closest to the SVM in accuracy and it was found a k of 68 made this possible. 
- Naive Bayes revealed there was a higher probability of having CVD than not based on predictive probability threshold of > 0.5. 

Future directions of the project may include using linear models to evaluate the Weight and BMI correlation and others. 
Weaknesses of the project included: 
- uneven sample sizes of age groups, dominant age group of patients in dataset was 50-59 with oldest patient being 65 which is not representative of the true population of cardiovascular disease when the prevalence of CVD is only 40% in this age group whereas it is 75% and higher age 65 and older.
