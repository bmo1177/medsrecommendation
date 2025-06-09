Here’s the **revised and complete `README.md`** for your project, now including setup instructions from installing Python to testing the model with a `test.txt` file. It remains concise, professional, and easy to follow for users or reviewers at **Tiaret University**.

---

# Personalized Medical Recommendation System with Machine Learning

Welcome to the **Personalized Medical Recommendation System** — an AI-powered health assistant created for educational purposes at **Tiaret University**. This system helps users identify potential diseases based on their symptoms and provides personalized recommendations, including medications, diet, workouts, and precautions.

---

## 🚀 Features

* **Symptom-Based Disease Prediction**
  Input symptoms manually or via speech to get instant predictions.

* **Voice Recognition Support**
  Describe symptoms using voice input (mic-enabled devices).

* **Tailored Recommendations**
  Get suggestions for:

  * Top 5 medicines
  * Precautionary measures
  * Diet plans
  * Workouts

* **Flask Web App**
  Lightweight and easy-to-use interface.

* **Privacy and Safety**
  User data is kept local and handled securely.

---

## 🛠️ Setup Instructions

### 1. 📥 Install Python

Download and install Python 3.10 or newer:
👉 [https://www.python.org/downloads/](https://www.python.org/downloads/)

Make sure to check **"Add Python to PATH"** during installation.

---

### 2. 📁 Clone the Repository

```bash
git clone https://github.com/yourusername/Personalized-Medical-Recommendation-System.git
cd Personalized-Medical-Recommendation-System
```

---

### 3. 📦 Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

---

### 4. 🔧 Install Dependencies

```bash
pip install pandas numpy flask sklearn
```

---

### 5. 📂 Prepare the Model and Files

Make sure the following files are present:

* `model.pkl` – Trained disease prediction model
* `symptom_df.txt` – List of known symptoms
* `medications.csv`, `diets.csv`, etc. – Recommendation databases
* `test.txt` – Contains example symptoms (one per line or comma-separated)

---

### 6. 🌐 Run the Web App

```bash
python main.py
```

Then open your browser and go to:
👉 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## ✅ Example `test.txt`

```txt
fatigue, weight_loss, restlessness, lethargy
```

---

## 🧑‍💻 Developers

This system was developed anonymously as part of educational projects at **Tiaret University** for both **OSSY** and **Meriom** coursework.

---

## 📌 Notes

* This project is for academic and educational use only.
* It is **not intended** to replace professional medical advice.

