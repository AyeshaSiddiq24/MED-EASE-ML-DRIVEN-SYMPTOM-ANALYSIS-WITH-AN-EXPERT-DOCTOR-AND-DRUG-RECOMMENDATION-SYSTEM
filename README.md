# MED-EASE-ML-DRIVEN-SYMPTOM-ANALYSIS-WITH-AN-EXPERT-DOCTOR-AND-DRUG-RECOMMENDATION-SYSTEM 
UNDERGRAD: MAJOR - PROJECT

This project is based on our research work presented in **IJIRT, Volume 11, Issue 2 (2024)**.  
It focuses on predicting diseases from user-entered symptoms using machine learning, recommending appropriate medications, and enabling doctor appointment scheduling through an integrated digital system.

The objective is to provide **fast, reliable, and automated healthcare assistance**, addressing the modern need for accurate diagnosis, expert guidance, and seamless patient–doctor interaction.

## 📘 Overview  
MedEase is an intelligent healthcare system designed to analyze symptoms, identify potential diseases, recommend medicines, and connect patients with qualified doctors.

The system aims to enhance accessibility and accuracy in healthcare delivery by combining:

- Machine Learning  
- Basic Deep Learning concepts  
- Web technologies  
- Medical decision support  

### A Real-World Scenario Example  
A patient experiencing symptoms (like abdominal pain) can input them into the system.  
The model predicts possible diseases, suggests medications, and advises booking an appointment.  
A doctor reviews the patient’s details, confirms the diagnosis, and provides treatment recommendations.

This workflow demonstrates MedEase’s role as a **digital companion** for early diagnosis and care.


## 🧠 Existing System  
The traditional ML-based disease prediction systems:

- Only handle structured symptom data  
- Predict diseases but **do NOT** recommend medicines  
- Lack doctor appointment workflows  
- Provide limited diagnostic scope  

MedEase overcomes these limitations by integrating:

- Disease prediction  
- Drug recommendations  
- Doctor selection  
- Appointment booking  
- Complete patient–doctor workflow  



## 📚 Literature Survey (Summary)

A number of previous works inspired MedEase, including:

| Title | Method | Advantage | Drawback |
|------|--------|-----------|----------|
| Symptoms-Based Disease Prediction (2021) | ML Techniques | Improved accuracy | Requires large datasets |
| ML Approach for Symptom Diagnosis (2022) | Naive Bayes + Rule-Based Reasoning | High accuracy | Limited scope |
| Effective Diagnosis of Heart Disease (2015) | Bayes, SVM, Forecasting | Real-time diagnosis | Errors in user-generated data |
| Doctor Recommendation via Collaborative Filtering (2018) | Similarity-based | Personalized recommendation | User review bias |
| Medication Recommendation via EHR (2022) | ML + rule-based | Tailored medicine mapping | Data privacy concerns |
| Medicine Recommendation System (2020) | Interpretable ML | Transparent decision making | Lower accuracy vs DL |
| Dermatology ML Techniques (2015) | Unsupervised | Early intervention | Information overload |
| CNN-based Doctor Recommendation (2020) | CNN | Diagnosis assistance | Misdiagnosis risk |
| Alternative Medicine System (2023) | Cosine Similarity | Workload reduction | Technical complexity |
| Online Doctor Appointment System (2018) | Android App | Easy appointments | Lacks ML features |

These studies highlight challenges and gaps that MedEase resolves by integrating both **disease prediction** and **medical recommendations** into a single solution.



## 🔬 Proposed System  
MedEase delivers:

- ✔️ Accurate disease recognition from symptoms  
- ✔️ Medication recommendations (primary + alternative)  
- ✔️ Doctor selection based on the diagnosed condition  
- ✔️ Appointment booking with real-time schedule updates  
- ✔️ Comprehensive healthcare guidance  

The system leverages **Machine Learning + Web Technologies** to bridge the gap between patients and healthcare professionals.



## 🏗️ System Architecture  

### **Hardware Requirements**
- Updated Processor  
- Minimum 4 GB RAM  
- Minimum 100 GB Hard Disk  

### **Software Requirements**
- OS: Windows  
- Backend: Python 3.6  
- Frontend: HTML, CSS, JavaScript  
- Web Framework: Flask  
- Database: MySQL  
- IDE: PyCharm / Sublime  

### **Design Components**
- E-R Diagram  
- Data Flow Diagram (DFD)  
- UML:  
  - Use Case Diagram (Admin / Patient / Doctor)  
  - Sequence Diagrams  
  - State Diagrams  



## ⚙️ Methodology  

### **Machine Learning Models Used**

#### 1️⃣ Random Forest Classifier  
- Handles both classification and regression  
- Achieved **88% accuracy**  
- Uses majority voting across decision trees  

#### 2️⃣ Naive Bayes Classifier  
- Based on probabilistic Bayes theorem  
- Achieved **86.17% accuracy**  
- Performs well with high-dimensional symptom data  

#### 3️⃣ Decision Tree Classifier  
- Based on IF-ELSE rule-based tree  
- Achieved **82.18% accuracy**

#### 4️⃣ Voting Classifier (Best Performer)  
- Combines: Decision Tree + Naive Bayes + Random Forest  
- Uses Hard/Soft voting  
- Achieved **95% overall accuracy**  

### **Evaluation Metrics**
- Accuracy  
- Recall  
- Precision  
- F1 Score  

(Visual ML evaluation graphs included in the PDF)



## 📊 Dataset Description  
- **Source**: Disease Prediction Dataset (Kaggle)  
- **Link**: https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning  
- **Total Records**: 4921  
- **Total Features (Symptoms)**: 133  

Dataset was updated and modified to enhance accuracy and coverage.



## 🧩 Module Implementation  

### 👤 Patient Module  
- Register using phone number, name, unique username, and password  
- Login to system  
- Enter symptoms  
- View predicted disease  
- Select doctor & book appointment  
- Receive schedule notification  

### 👨‍⚕️ Doctor Module  
- Login to doctor dashboard  
- View appointment requests  
- Approve and schedule appointments  
- Send notifications  

### 🛠 Admin Module  
- Login  
- Manage hospital data  
- Oversee system workflows  

### 🖥 Screens / Pages Implemented  
- Admin Login  
- Patient Registration & Login  
- Doctor Login  
- Symptom Input Page  
- Disease Detection Result Page  
- Appointment Booking Page  
- Updated Output Screens  



## 📈 Results  

The system showed:

- High accuracy disease prediction  
- Effective medicine recommendation mapping  
- Smooth appointment booking workflow  
- Clean UI/UX for patients & doctors  

Voting Classifier ► **95% accuracy**  
Random Forest ► **88% accuracy**  
Naive Bayes ► **86% accuracy**



## 🏁 Conclusion  

MedEase is a powerful healthcare decision-support tool that automates:

- Symptom analysis  
- Disease prediction  
- Doctor recommendations  
- Appointment scheduling  
- Medication suggestions  

The system enhances efficiency, accessibility, and accuracy in healthcare services.

### **Future Enhancements**
- Improved ML models  
- Expanded disease coverage  
- NLP-based chatbot for symptom input  
- Telemedicine integration  
- Secure EHR integration  
- Real-time doctor availability  
- Stronger database & security compliance  


# **Published Paper 


# 🎓 Authors  
**Umar Javeed Altaf**  
**Ayesha Siddiq**  
**Shamamah Firdous**  
Dept. of CS & AI, MJCET, Osmania University  



