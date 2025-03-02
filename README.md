# **MLFraminghamHeartStudy**  
Predicting coronary heart disease (CHD) using the Framingham Heart Study dataset. This project involves building predictive models to assess CHD risk factors and improve heart disease prevention strategies.

## **Project Overview**  
This project utilizes data from the **Framingham Heart Study**, a long-term cardiovascular study that began in 1948, tracking the health of thousands of participants. The goal is to **predict the likelihood of developing CHD within 10 years** based on various medical and behavioral factors.

## **Dataset**  
- **Total Observations:** 3,658 participants  
- **Features:** 16 variables including age, BMI, blood pressure, cholesterol levels, smoking status, and diabetes.  
- **Target Variable:** `TenYearCHD` (binary: 1 = CHD within 10 years, 0 = No CHD).  
- **Data Split:**  
  - `framingham_train.csv`: Training set (2,560 observations)  
  - `framingham_test.csv`: Test set (1,098 observations)  

## **Methodology**  
- **Logistic Regression Model** is used to estimate CHD risk.  
- **Feature Importance** analysis is conducted to identify key risk factors.  
- **Threshold Optimization:** Finding an optimal probability threshold `p̄` to decide when preventive medication should be prescribed.  
- **Model Evaluation:** Accuracy, True Positive Rate (TPR), False Positive Rate (FPR), and ROC Curve analysis.  
- **Economic Cost Analysis:** Estimating expected medical costs per patient based on different treatment strategies.  

## **Use Case Example**  
A real-world patient example is evaluated using the model to determine whether **preventive medication should be prescribed** based on their predicted CHD risk.

## **Next Steps**  
- **ROC Curve Analysis:** Assessing the model's effectiveness.  
- **Insurance Co-Payment Strategy:** Determining an optimal cost-sharing policy to encourage self-selection for treatment.  
- **Ethical Considerations:** Addressing potential biases in the analysis and model predictions.  
