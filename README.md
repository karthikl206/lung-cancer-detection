# 🫁 Lung Cancer Detection

**A machine learning project to detect lung cancer using CT scan images and clinical symptoms.**

This project aims to build an intelligent system that assists in the **early detection** of lung cancer through **two approaches**:
1. **Image-based classification** of CT scan images using computer vision and deep learning techniques.
2. **Symptom-based prediction** using patient clinical data and machine learning algorithms.

The primary goal is to develop a user-friendly diagnostic tool that enhances clinical decision-making and promotes early intervention.

---

## 🚀 Features

- 🔍 **CT Scan Image Classification**: Predicts types such as Normal, Benign, Malignant, Adenocarcinoma, Large Cell Carcinoma, and Squamous Cell Carcinoma.
- 🧪 **Symptom-based Prediction**: Evaluates risk based on features like age, gender, smoking history, coughing, fatigue, weight loss, etc.
- 🧠 **Multiple ML Models**: Implements and compares the performance of Random Forest, SVM, LightGBM, Extra Trees, and CatBoost.
- 📊 **Result Dashboard**: Displays predictions with confidence scores.
- 📄 **Report Download**: Option to download PDF reports for patient records.
- 🌐 **Web Interface**: Integrated web app with HTML, CSS, JavaScript (Frontend) and Flask or Streamlit (Backend).
- 🔐 Optional: User login and prediction history tracking.

---

## 📁 Project Structure

lung-cancer-detection/
│
├── app.py # Backend application script
├── README.md
├── requirements.txt
├── static/ # CSS, JS, images for frontend
├── templates/ # HTML templates
├── dataset/ # CT scan images & symptoms CSV
│ ├── CT_Scans/
│ └── symptoms.csv
├── models/ # Trained machine learning models
├── utils/ # Preprocessing and utility scripts
└── reports/ # Exported prediction reports
📊 Dataset Overview
CT Scan Dataset: Sourced from public medical datasets (e.g., Kaggle), containing labeled lung images for multiple cancer types.

Symptom Dataset: Simulated or real-world tabular data with attributes like:

Age

Gender

Smoking habits

Cough

Shortness of breath

Chest pain

Fatigue

Weight loss

🔧 Technologies Used
Languages: Python, HTML, CSS, JavaScript

ML Libraries: scikit-learn, LightGBM, CatBoost, OpenCV, NumPy, Pandas

Visualization: Matplotlib, Seaborn

Frameworks: Flask or Streamlit (choose one)

Tools: VS Code / Jupyter Lab / PyCharm

📈 Results
Highest Accuracy Achieved: 96%

Best Model: Random Forest Classifier

Evaluation Metrics: Confusion Matrix, Accuracy Score, Precision, Recall, F1 Score

📋 Future Improvements
 Add Grad-CAM for image model explainability

 Deploy to Heroku or Streamlit Cloud

 Collect real-world symptom data through a survey form

 Add database for user registration and result storage

 Add API for external access

👨‍💻 Author
Karthik L
Final Year B.Sc AI & DS Graduate
GitHub: @karthikl206

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
CT Scan datasets from Kaggle and open-access repositories.

Tutorials and documentation from scikit-learn, LightGBM, and Flask.

Academic guidance from mentors and research faculty.

