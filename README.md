# 📌 Intensity Analysis NLP Model - README

## 🚀 **Project Overview**
The **Intensity Analysis NLP Model** is designed to analyze text reviews and classify their emotional intensity into three categories: **Happiness, Anger, or Sadness**. Using **Natural Language Processing (NLP)** techniques, this model enables real-time sentiment analysis to enhance customer insights.

---

## 🔧 **Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/intensity-analysis-nlp.git
cd intensity-analysis-nlp
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run Preprocessing & Model Training**
```bash
python train_model.py
```

### **4️⃣ Run the API (Flask Deployment)**
```bash
python flask_app.py
```

### **5️⃣ Run the Web App (Streamlit Deployment)**
```bash
streamlit run app.py
```

---

## 📊 **Project Workflow**
1. **Data Collection** - Collected & labeled text data for emotional intensity.
2. **Preprocessing** - Removed stopwords, tokenized, vectorized (TF-IDF).
3. **Feature Engineering** - Applied **n-grams, TF-IDF weighting**.
4. **Model Training** - Trained models (Logistic Regression, SVM, Random Forest, LSTM).
5. **Model Evaluation** - Assessed using **accuracy, precision, recall, and F1-score**.
6. **Hyperparameter Tuning** - Optimized parameters for best performance.
7. **Deployment** - Deployed via Flask API & Streamlit Web App.

---

## 🔍 **Usage**
### **1️⃣ API Endpoint (Flask Deployment)**
#### **POST Request:**
```json
{
    "text": "I am extremely happy today!"
}
```
#### **Response:**
```json
{
    "prediction": "Happiness"
}
```

---

## 🚀 **Model Performance**
| Model               | Accuracy  | Precision | Recall  | F1-Score |
|---------------------|----------|-----------|---------|----------|
| Logistic Regression| 81.2%    | 79.8%     | 80.1%   | 80.3%    |
| SVM               | 85.5%    | 84.3%     | 85.1%   | 84.7%    |
| Random Forest     | 86.1%    | 85.2%     | 86.0%   | 85.5%    |
| LSTM (Deep Learning) | 89.3% | 88.7% | 89.0% | 88.8% |

---

## 🛠 **Future Improvements**
- **Fine-tune with Transformer models (BERT, GPT-3).**
- **Expand dataset to include more diverse expressions.**
- **Optimize real-time inference for production.**

---

## 📜 **License**
This project is licensed under the **MIT License**.

### 🔥 **Author:** Krishnapriya Adepu  
For queries, feel free to reach out!

