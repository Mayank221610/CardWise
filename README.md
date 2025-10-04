# CardWise-Credit Approval Predictor

This project is a machine learning-based web application that predicts the likelihood of credit card approval for a customer based on their personal and financial details. It leverages a Random Forest Classifier trained on historical credit and application records.

---

## 🔍 Project Overview

Many financial institutions face challenges in assessing credit card applications quickly and accurately. This project provides a predictive solution using machine learning to automate and improve this process.

The application offers:
- A user-friendly web interface (built using Flask)
- Real-time predictions
- Visual insights into model performance

---

## 📁 Directory Structure

```

├── Dataset/
│   ├── application\_record.csv
│   └── credit\_record.csv
│ 
├── models/
│   ├── Random\_Forest\_best\_model.pkl
│   ├── best\_threshold.txt
│   └── train\_columns.pkl
│ 
├── notebooks/
│   ├── 1\_Visualizing\_and\_analyzing\_data.ipynb
│   ├── 2\_Data\_preprocessing.ipynb
│   ├── 3\_Model\_building.ipynb
│   └── 4\_Prediction.ipynb
│ 
├── app.py
├── requirements.txt
└── README.md

````

## 🚀 How to Run the Project

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/cardwise.git
   cd cardwise


2. **Create a virtual environment** (optional but recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**

   ```bash
   python app.py
   ```

5. **Visit in browser:**
   Navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) to use the application.

---

## 🧠 Machine Learning Details

* **Model Used:** Random Forest Classifier
* **Evaluation Metrics:** Accuracy, F1 Score, Confusion Matrix
* **Preprocessing:** Handled using SMOTE, encoding, feature scaling
* **Threshold Selection:** Based on optimized F1 score

## 👨‍💻 Author

* **Mayank** – [GitHub](https://github.com/Mayank221610)

## 📧 Connect with Me

**Mayank**

💼 [My LinkedIn](www.linkedin.com/in/mayank-83b657365)

👨‍💻 [My GitHub](https://github.com/Mayank221610)

📧 [Email Id](mayank221605@gmail.com)



If you have any questions or suggestions, feel free to reach out via GitHub or email.
