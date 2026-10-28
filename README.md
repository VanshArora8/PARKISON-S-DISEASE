# PARKISON-S-DISEASE
Parkinson's disease (PD) is a progressive neurological disorder characterized by motor and 
non-motor symptoms, significantly affecting the quality of life. Early and accurate diagnosis is 
crucial for effective treatment and management of the disease. In this study, machine learning 
techniques were utilized to develop a predictive model for Parkinson's disease based on a 
dataset of vocal and biomedical features. The dataset includes features such as RPDE 
(Recurrence Period Density Entropy), DFA (Detrended Fluctuation Analysis), and other 
biomarkers, which have been shown to correlate with the presence of Parkinson's. 
We implemented and compared multiple machine learning algorithms, including Decision 
Tree, Random Forest, K-Nearest Neighbors (KNN), Naive Bayes, Support Vector Machines 
(SVM), and Logistic Regression, to identify the best-performing model. The models were 
evaluated using performance metrics such as accuracy, precision, recall, F1-score, and AUC
ROC. Random Forest and Support Vector Machines emerged as the most effective algorithms, 
achieving the highest predictive accuracy and robustness in classifying Parkinson's disease. 
Feature importance analysis further highlighted the most significant predictors contributing to 
the model's performance. 
This study demonstrates the potential of machine learning in providing reliable and efficient 
diagnostic tools for Parkinson’s disease. By automating the prediction process, these models 
can support medical professionals in making faster and more accurate diagnoses, thereby 
improving patient outcomes. Future work will focus on expanding the dataset and integrating 
additional features to enhance the generalizability of the models. 
 Random Forest achieved the highest accuracy at 92%, followed by SVM at 89%, while 
Logistic Regression and KNN scored 87% and 84%, respectively. Decision Tree reached 100%, 
suggesting potential overfitting, and Naive Bayes showed the lowest accuracy at 69%. The 
findings highlight Random Forest as the most reliable model, demonstrating the utility of 
ensemble approaches for PD classification.
How to run the project
1. Download and extract the ZIP file.
2. Open the extracted folder in VS Code.
3. Open the terminal and run:

pip install -r requirements.txt
streamlit run app.py


5. Open the local URL displayed in the terminal.
6. Upload your Parkinson’s dataset in CSV format and click Train models.
