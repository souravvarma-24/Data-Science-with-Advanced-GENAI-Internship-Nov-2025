## 🚀 Using MLflow for Experiment Tracking and Model Management
---

**Innomatics Research Labs – Data Science Internship**
---

This repository demonstrates the integration of **MLflow** into an existing **Sentiment Analysis project** to enable experiment tracking, model management, and reproducibility. The task focuses on logging parameters, metrics, artifacts, managing multiple runs, and organizing experiments using MLflow’s tracking APIs.

The implementation showcases end-to-end MLflow usage during model training and evaluation, excluding the bonus workflow orchestration component.

---

## 🧩 Objective

The objective of this task is to introduce **MLflow** for:
- Experiment tracking
- Model management
- Reproducibility in machine learning projects

The integration is performed on an existing **Sentiment Analysis** pipeline.

---

## 📁 Project Structure

All project files are organized as shown below:

```
📁 Sourav_419_Data-Science-with-Advanced-GENAI-Internship_Assignment_13
│
└── MLflow_Experiment_Tracking_and_Model_Management.ipynb
```

The notebook contains the complete MLflow integration, training runs, logging, and evaluation.

---

## 🛠 Technologies Used

- Python  
- Scikit-learn  
- MLflow  
- Matplotlib  
- Pandas & NumPy  
- NLP (TF-IDF)  

---

## ▶️ What Is Demonstrated

This project demonstrates the following MLflow capabilities:

- Integration of MLflow into an existing ML project  
- Training models within MLflow runs  
- Logging model parameters and evaluation metrics  
- Logging artifacts such as plots and prediction files  
- Customizing run names for better experiment organization  
- Comparing multiple runs for hyperparameter tuning  
- Model logging and management using MLflow APIs  
- Tagging runs for improved traceability  

*(Bonus workflow orchestration using Prefect is intentionally excluded.)*

---

## ▶️ Experiment Workflow

1. Load and preprocess sentiment analysis data.
2. Train multiple machine learning models using TF-IDF features.
3. Start MLflow runs with meaningful run names.
4. Log model parameters such as algorithm type and hyperparameters.
5. Log evaluation metrics including F1-score.
6. Log artifacts such as confusion matrix plots and prediction samples.
7. Perform hyperparameter tuning across multiple runs.
8. Track and compare experiments using the MLflow UI.

---

## ▶️ How to Run the Notebook

Ensure the required libraries are installed:

pip install mlflow scikit-learn pandas matplotlib

Launch the notebook and start the MLflow UI:

mlflow ui

Run the notebook cells to generate experiments and view results at:

http://127.0.0.1:5000

---

## 📌 Key Outcomes

- Clear experiment tracking across multiple model runs  
- Reproducible training and evaluation workflow  
- Visual comparison of metrics and hyperparameters  
- Organized model artifacts and run metadata  

---

## 🧑‍🎓 Intern Details

| Field | Information |
|------|-------------|
| **Name** | Sourav Varma Gottumukkala |
| **Assignment** | Using MLflow for Experiment Tracking and Model Management |
| **Internship** | Data Science Internship |
| **Organization** | Innomatics Research Labs |

---

## 🏁 Final Summary

This project successfully integrates MLflow into a sentiment analysis pipeline to demonstrate experiment tracking, hyperparameter comparison, and model management. All core requirements specified for MLflow usage have been implemented and validated, ensuring reproducibility and transparency in the machine learning workflow.

---

**This completes Internship Assignment => Using MLflow for Experiment Tracking and Model Management successfully.**

---

## Your support matters! If this repository helped you, please leave a ⭐.
