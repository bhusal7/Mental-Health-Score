# 🧠 Mental Health Score Prediction

A machine learning project that predicts a **mental health score** using student social media usage, academic, demographic, and lifestyle-related features.

The project includes data analysis, preprocessing, model training, evaluation, a saved machine learning model, and a simple web interface/API for making predictions.

> **Note:** This project is for educational and demonstration purposes only. The predicted score should not be treated as a medical diagnosis or professional mental-health assessment.

---

## 📌 Project Overview

Social media usage can be associated with different aspects of students' well-being. This project explores a dataset containing student social media usage and mental-health-related information and builds a machine learning model to predict a mental health score.

### Main workflow

**Dataset → Data Cleaning → Exploratory Data Analysis → Preprocessing → Model Training → Evaluation → Saved Model → Prediction Interface**

---

## ✨ Features

- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data preprocessing and feature handling
- 🤖 Machine learning model training
- 📈 Model evaluation
- 💾 Trained model saved as a `.pkl` file
- 🌐 Simple HTML/CSS/JavaScript frontend
- ⚡ Python backend using FastAPI
- 📓 Jupyter Notebook implementation
- 🔮 Mental health score prediction from user-provided inputs

---

## 🗂️ Project Structure

```text
Mental-Health-Score/
│
├── ML Project.html
├── ML_Project.ipynb
├── mental_health_score.ipynb
│
├── Mental_Health_Model.pkl
├── Student Social Media And Mental Health Impact (1).csv
│
├── main.py
├── index.html
├── script.js
├── style.css
│
├── requirements.txt
│
├── .ipynb_checkpoints/
├── .virtual_documents/
└── anaconda_projects/
```

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning & Data Science
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib / Pickle

### Backend
- FastAPI
- Uvicorn

### Frontend
- HTML
- CSS
- JavaScript

### Development Environment
- Jupyter Notebook
- Anaconda
- Git & GitHub

---

## 📊 Dataset

The project uses:

**Student Social Media And Mental Health Impact (1).csv**

The dataset contains information related to students, including social media usage and other factors associated with mental health.

The notebook performs the necessary data exploration and preprocessing before training the model.

---

## 🤖 Machine Learning Model

The trained model is stored as:

```text
Mental_Health_Model.pkl
```

The model can be loaded and used for predictions through the Python backend.

The exact preprocessing and modeling steps can be explored in:

```text
mental_health_score.ipynb
ML_Project.ipynb
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/bhusal7/Mental-Health-Score.git
cd Mental-Health-Score
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

**Windows CMD:**

```cmd
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Start the FastAPI Server

```bash
uvicorn main:app --reload
```

The API will normally be available at:

```text
http://127.0.0.1:8000
```

FastAPI interactive documentation:

```text
http://127.0.0.1:8000/docs
```

---

## 🌐 Frontend

The project also contains:

```text
index.html
style.css
script.js
```

These files provide the user interface for entering information and interacting with the prediction system.

Make sure the frontend sends requests to the correct FastAPI endpoint configured in `main.py`.

---

## 📓 Jupyter Notebook

To explore the complete machine learning workflow, open:

```text
mental_health_score.ipynb
```

or:

```text
ML_Project.ipynb
```

The notebooks contain the analysis, preprocessing, model development, and evaluation steps.

---

## 📈 Machine Learning Workflow

1. Load the dataset
2. Inspect the data
3. Handle missing/invalid values
4. Explore relationships between variables
5. Prepare features and target
6. Preprocess numerical and categorical features
7. Split data into training and testing sets
8. Train machine learning models
9. Evaluate model performance
10. Select the trained model
11. Save the model
12. Use the model for predictions through FastAPI

---

## 📁 Important Files

| File | Purpose |
|---|---|
| `mental_health_score.ipynb` | Main ML notebook |
| `ML_Project.ipynb` | Machine learning project notebook |
| `ML Project.html` | Exported notebook/report |
| `Mental_Health_Model.pkl` | Trained ML model |
| `Student Social Media And Mental Health Impact (1).csv` | Dataset |
| `main.py` | FastAPI backend |
| `index.html` | Frontend page |
| `script.js` | Frontend JavaScript |
| `style.css` | Frontend styling |
| `requirements.txt` | Python dependencies |

---

## ⚠️ Disclaimer

This project is an **educational machine learning project**.

It does **not** provide medical advice, diagnosis, treatment, or clinical assessment. A machine learning prediction should not be used as a substitute for guidance from a qualified mental-health professional.

---

## 🎯 Future Improvements

- Improve model accuracy through feature engineering
- Compare additional machine learning algorithms
- Add better validation and hyperparameter tuning
- Improve frontend design and user experience
- Deploy the FastAPI application online
- Add prediction history
- Add model performance visualizations
- Improve API validation and error handling

---

## 👨‍💻 Author

**Vashudev Bhusal**

GitHub: https://github.com/bhusal7

---

## ⭐ Acknowledgment

This project was created as part of a practical learning journey in **Machine Learning, Data Science, FastAPI, and Web Development**.

If you find this project useful, consider giving the repository a ⭐.
