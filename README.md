# 🎓 ScholarIQ — Student Performance Prediction System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" />
</p>

<h3 align="center">
  AI-powered academic intelligence for predicting student outcomes before results day.
</h3>

<p align="center">
  <a href="https://aistudentperformanceanalytics-rxj9rhuavw6ykenw8aszqh.streamlit.app/">
    <img src="https://img.shields.io/badge/🚀%20LIVE%20DEMO-Try%20ScholarIQ-00C853?style=for-the-badge" />
  </a>
  <a href="YOUR_GITHUB_URL">
    <img src="https://img.shields.io/badge/⭐%20STAR%20PROJECT-GitHub-181717?style=for-the-badge&logo=github" />
  </a>
</p>

---

## 🚀 Live Demo

### 👉 [Launch ScholarIQ](https://aistudentperformanceanalytics-rxj9rhuavw6ykenw8aszqh.streamlit.app/)

Experience the complete prediction workflow directly in the browser.

**No installation required.**

---

# 🧠 What is ScholarIQ?

**ScholarIQ** is a machine-learning-based student performance prediction system designed to estimate a student's final academic score using important academic and behavioral indicators.

Instead of waiting for final examination results, ScholarIQ provides an **early performance forecast** and highlights factors that may influence the student's outcome.

### The core idea

```text
Student Data
     ↓
Machine Learning Model
     ↓
Predicted Score
     ↓
Performance Analysis
     ↓
Personalized Recommendations
```

---

# ✨ Features

| Feature                  | Description                                         |
| ------------------------ | ---------------------------------------------------- |
| 👤 Student Profile       | Enter student information and academic details      |
| 📚 Academic Analysis     | Analyze assignments, internal marks and study hours  |
| 📅 Attendance Analysis   | Calculate and visualize attendance percentage        |
| 🤖 ML Prediction         | Predict final academic score                         |
| 🎯 Grade Prediction      | Convert predicted score into academic grade          |
| 📊 Performance Breakdown | Visualize the contribution of important factors      |
| 💡 Recommendations       | Generate improvement suggestions                     |
| 📥 Report Generation     | Download the student's prediction report              |
| ⚡ Live Preview           | Dashboard updates instantly as values change          |
| 🎨 Modern UI             | Dark, responsive academic intelligence dashboard      |

---

# 🖥️ Application Screens

## 1️⃣ Student Prediction Dashboard

The first screen allows users to enter the student's profile and academic information.

### Student Profile

* Student name
* Gender
* Age

### Academic Details

* Assignments submitted
* Internal marks
* Self-study hours
* Previous failures
* Extra classes

### Attendance

* Total classes conducted
* Classes attended
* Automatically calculated attendance percentage

### Prediction

Once the required information is entered, the user can select:

**`Predict Final Score →`**

to generate the prediction.

<p align="center">
  <img src="docs/screenshots/student-input-dashboard.png" width="95%">
</p>

<p align="center">
  <i>ScholarIQ — Student input and prediction dashboard</i>
</p>

---

# 📊 2️⃣ Prediction Results Dashboard

After prediction, ScholarIQ presents the results through an interactive analytics dashboard.

### Prediction Result

Displays:

* Predicted score
* Grade
* Performance category
* Projected final score

### Performance Breakdown

The system visualizes individual factors including:

* Assignments
* Internal marks
* Attendance
* Study hours
* Discipline

### Recommendations

The application automatically generates actionable recommendations based on the student's profile.

For example:

```text
Submit all assignments on time.

Focus more on internal assessments.
```

<p align="center">
  <img src="docs/screenshots/prediction-results-dashboard.png" width="95%">
</p>

<p align="center">
  <i>ScholarIQ — Prediction, performance analysis and recommendations</i>
</p>

---

# 🎯 Complete User Journey

```text
┌─────────────────────────┐
│   Enter Student Profile │
└────────────┬────────────┘
             ↓
┌─────────────────────────┐
│   Enter Academic Data   │
│                         │
│ • Assignments           │
│ • Internal Marks        │
│ • Study Hours           │
│ • Previous Failures     │
└────────────┬────────────┘
             ↓
┌─────────────────────────┐
│   Enter Attendance      │
│                         │
│ Total Classes           │
│ Classes Attended        │
└────────────┬────────────┘
             ↓
┌─────────────────────────┐
│   Predict Final Score   │
└────────────┬────────────┘
             ↓
┌─────────────────────────┐
│    ML Prediction        │
└────────────┬────────────┘
             ↓
       ┌─────┴─────┐
       ↓           ↓
┌────────────┐ ┌────────────────┐
│ Score &    │ │ Performance    │
│ Grade      │ │ Breakdown      │
└─────┬──────┘ └───────┬────────┘
      │                │
      └────────┬───────┘
               ↓
┌─────────────────────────┐
│ Personalized            │
│ Recommendations         │
└────────────┬────────────┘
             ↓
┌─────────────────────────┐
│ Download Student Report │
└─────────────────────────┘
```

---

# 🤖 Machine Learning Pipeline

The project follows a complete machine learning workflow:

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Feature Selection
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Serialization
     ↓
Streamlit Deployment
```

The trained model is stored as:

```text
Model/student_model.pkl
```

---

# 📥 Input Features

ScholarIQ uses the following student-related attributes:

| Feature            | Description                               |
| ------------------ | ------------------------------------------ |
| Gender              | Student gender                            |
| Age                 | Student age                               |
| Assignments         | Number of assignments submitted           |
| Internal Marks      | Internal assessment performance           |
| Attendance          | Calculated attendance percentage          |
| Self Study Hours    | Daily study duration                      |
| Previous Failures   | Number of previous academic failures      |
| Extra Classes       | Whether the student attends extra classes |

---

# 📤 Prediction Output

The application generates:

### 🎯 Predicted Score

A final academic score on a **0–100 scale**.

### 🏆 Grade

The predicted score is converted into an academic grade.

### 📊 Performance Level

The application classifies the student's predicted performance.

### 💡 Recommendations

The system identifies areas where the student can improve.

---

# 📈 Performance Classification

|  Score | Grade | Performance       |
| -----: | :---: | ------------------ |
| 90–100 |   A+  | Outstanding        |
|  80–89 |   A   | Excellent          |
|  70–79 |   B   | Very Good          |
|  60–69 |   C   | Good               |
|  50–59 |   D   | Average            |
|   < 50 |   F   | Needs Improvement  |

---

# 📊 Example

A student enters:

```text
Student Name       : Pardi
Age                : 20
Assignments        : 5 / 10
Internal Marks     : 5 / 10
Attendance         : 90%
Study Hours        : 3 hrs/day
Previous Failures  : 0
Extra Classes      : Yes
```

ScholarIQ generates:

```text
┌─────────────────────────────┐
│       PREDICTION RESULT     │
│                             │
│          50 / 100           │
│                             │
│       GRADE D · AVERAGE     │
└─────────────────────────────┘
```

followed by:

```text
Performance Breakdown
────────────────────────────
Assignments       █████ 50
Internal Marks    █████ 50
Attendance        █████████ 90
Study Hours       ███ 30
Discipline        ██████████ 100
```

and personalized recommendations.

---

# 🏗️ System Architecture

```text
                         ┌───────────────────┐
                         │   Student Input   │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │ Feature Processing│
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │ Trained ML Model  │
                         │ student_model.pkl │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │ Score Prediction  │
                         └─────────┬─────────┘
                                   │
               ┌───────────────────┼───────────────────┐
               │                   │                   │
               ▼                   ▼                   ▼
        ┌─────────────┐    ┌──────────────┐    ┌──────────────┐
        │ Score/Grade │    │ Performance  │    │ Personalized │
        │             │    │ Breakdown    │    │Recommendations│
        └─────────────┘    └──────────────┘    └──────────────┘
                                   │
                                   ▼
                           ┌──────────────┐
                           │ Student      │
                           │ Report       │
                           └──────────────┘
```

---

# 🛠️ Tech Stack

### Programming

* 🐍 Python

### Machine Learning

* Scikit-Learn
* Joblib
* NumPy
* Pandas

### Visualization

* Plotly

### Application

* Streamlit
* Custom CSS

### Development

* Jupyter Notebook
* VS Code
* Git & GitHub

---

# 📂 Project Structure

```text
Student-Performance-Prediction-System/
│
├── Dataset/
│   ├── student_data.csv
│   ├── student_data_cleaned.csv
│   ├── student_data_feature_engineered.csv
│   └── student_performance_final.csv
│
├── Model/
│   └── student_model.pkl
│
├── Notebook/
│   ├── Student_Performance.ipynb
│   └── Student_Performance_executed.ipynb
│
├── Streamlit_App/
│   ├── app.py
│   └── style.css
│
├── docs/
│   └── screenshots/
│       ├── student-input-dashboard.png
│       └── prediction-results-dashboard.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ⚙️ Run Locally

## 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Student-Performance-Prediction-System.git
```

## 2. Enter the project

```bash
cd Student-Performance-Prediction-System
```

## 3. Create a virtual environment

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## 4. Install dependencies

```bash
pip install -r requirements.txt
```

## 5. Start ScholarIQ

```bash
streamlit run Streamlit_App/app.py
```

---

# ☁️ Deploy Your Own Live Demo

The easiest option is **Streamlit Community Cloud**.

### Deployment

```text
GitHub Repository
       ↓
Streamlit Community Cloud
       ↓
Select app.py
       ↓
Deploy
       ↓
Live URL
```

Set the application entry point to:

```text
Streamlit_App/app.py
```

Then add the generated URL to the top of this README:

```markdown
[🚀 Launch ScholarIQ](YOUR_STREAMLIT_URL)
```

---

# 🎓 Real-World Applications

ScholarIQ can be extended for:

* 🏫 Schools
* 🎓 Universities
* 👨‍🏫 Teachers
* 📚 Academic advisors
* 👨‍🎓 Students
* 🏢 Educational institutions

The system can act as an **early-warning mechanism** for identifying students who may require additional academic support.

---

# 🔮 Future Enhancements

* [ ] 👨‍🏫 Teacher dashboard
* [ ] 👨‍🎓 Student login system
* [ ] 🗄️ Database integration
* [ ] 📊 Historical performance tracking
* [ ] 📈 Student progress analytics
* [ ] 🧠 Explainable AI with SHAP
* [ ] 🤖 AI-generated study plans
* [ ] 📄 Advanced PDF reports
* [ ] 📧 Email report delivery
* [ ] 🚨 Academic risk-level prediction
* [ ] ☁️ Production cloud deployment
* [ ] 📱 Mobile-friendly interface

---

# 💡 Project Vision

ScholarIQ is designed around a simple principle:

> **Don't wait for failure to identify a problem. Predict it early and act on it.**

The long-term goal is to transform the application from a simple score prediction system into an **AI-powered academic early-warning and intervention platform**.

```text
Predict
   ↓
Understand
   ↓
Identify Weaknesses
   ↓
Recommend
   ↓
Improve
```

---

# ⚠️ Disclaimer

This application is developed for **educational and demonstration purposes**.

Predictions are estimates generated by a machine-learning model and should not be considered official academic results. Model performance depends on the quality and representativeness of the training dataset.

---

# 👨‍💻 Author

**Your Name**

Computer Science / Artificial Intelligence & Machine Learning

<p>
  <a href="YOUR_GITHUB_URL">GitHub</a> •
  <a href="YOUR_LINKEDIN_URL">LinkedIn</a> •
  <a href="YOUR_PORTFOLIO_URL">Portfolio</a>
</p>

---

## ⭐ If you like ScholarIQ

If this project helped you or you found it interesting, consider giving the repository a ⭐ on GitHub.

<p align="center">
  <b>🎓 ScholarIQ</b><br>
  Predict smarter • Intervene earlier • Perform better
</p>
