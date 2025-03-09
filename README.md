# Medical-Diagnosis

# 🏥 Disease Prediction App

A **Streamlit-based** web application that predicts the likelihood of various diseases, including **Diabetes, Heart Disease, Parkinson’s, Lung Cancer, and Hypothyroidism**, using trained **Machine Learning models**.

## 🚀 Features
- Predicts **Diabetes, Heart Disease, Parkinson’s, Lung Cancer, and Hypothyroidism**.
- Uses **Machine Learning models** trained on medical datasets.
- **User-friendly** interface with an intuitive form-based input system.
- **Real-time predictions** using `pickle`-saved models.

## 📌 Technologies Used
- **Python**
- **Streamlit** (Web Interface)
- **Scikit-learn** (Machine Learning)
- **Pandas, NumPy** (Data Processing)
- **Pickle** (Model Saving/Loading)

## 📂 Project Structure
```
├── Datasets/                     # Dataset files used for training
│   ├── diabetes.csv
│   ├── heart_disease.csv
│   ├── parkinsons.csv
│   ├── lung_cancer.csv
│   ├── thyroid.csv
```
```
├── Models/                      # Trained ML models (.sav files)
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── lungs_disease_model.sav
│   ├── thyroid_model.sav
│
├── app.py                        # Streamlit Web App
├── requirements.txt               # Dependencies
├── README.md                      # Documentation
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/kassasanathkumar/Medical-Diagnosis.git
   cd Medical-Diagnosis
   ```

2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**
   ```sh
   streamlit run app.py
   ```

## 📊 Disease Prediction Models
Each prediction is powered by **trained machine learning models**:
- **Diabetes:** Uses patient metrics (Glucose, BMI, etc.) to detect diabetes risk.
- **Heart Disease:** Evaluates heart rate, blood pressure, and cholesterol levels.
- **Parkinson’s:** Uses vocal characteristics to detect early signs of Parkinson’s.
- **Lung Cancer:** Checks lifestyle factors like smoking, anxiety, and coughing.
- **Hypothyroidism:** Evaluates thyroid hormone levels to detect thyroid disorders.

## 🤝 Contributing
If you'd like to contribute, feel free to **fork the repository** and submit a **pull request**!

---
### 🔗 Connect with Me  
💼 [LinkedIn](www.linkedin.com/in/kassa-sanath-kumar) | 📧 Email: kassasanathkumar@gmail.com

