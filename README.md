Knee Osteoarthritis Risk Prediction System
Project Overview
This project presents a **Multimodal Machine Learning Framework** for predicting preoperative risk in knee osteoarthritis patients.

It combines:
* CNN for X-ray image analysis (KL grading)
* XGBoost for clinical data analysis
* Explainable AI (SHAP & Grad-CAM)
* 
## Technologies Used
* Python
* TensorFlow (CNN)
* XGBoost
* Pandas, NumPy
* SHAP (Explainable AI)
* Google Colab


## Methodology

### 1.Image Analysis
* Knee X-ray images processed using CNN
* Output: KL Grade (0–4)

### 2.Clinical Data Analysis
* Features: BMI, Age, Medical History
* Model: XGBoost
* Output: Risk Level (Low / Medium / High)

### 3. Multimodal Fusion
* Combines CNN + Clinical predictions
* Final Output: Surgery Risk Level

## Output Example
* KL Grade: 1
* Clinical Risk: High
* Final Risk: Low

## Explainable AI
* SHAP → Explains clinical predictions
* Grad-CAM → Visualizes important X-ray regions


##  Note
Dataset not included due to size. Use publicly available knee X-ray datasets (e.g., Kaggle).

