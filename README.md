# 💼 Developer Salary Prediction (Udacity ML Project)

This project applies the **CRISP-DM methodology** to analyze and predict developer salaries using the **Stack Overflow Developer Survey**.

---

## 📌 Project Overview

This machine learning project was created as part of the **Udacity Machine Learning Nanodegree**.  
We aim to predict a developer’s annual salary based on professional experience, education, remote work status, country, and technologies used.

---

## 🔍 Dataset

- **Source**: [Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/)
- **Data Used**: Filtered down from over 65,000 responses to a subset of relevant features
- **Note**: Due to dataset size limitations, the raw CSV is not included in this repository.  
  👉 You can download it directly [here](https://survey.stackoverflow.co/datasets/stack-overflow-developer-survey-2024.zip)

---

## 💡 Business Questions Explored

1. How does years of professional coding experience impact salary?
2. Does education level significantly influence salary?
3. Are remote developers paid more?
4. Can we predict a developer’s salary based on these factors?

---

## 🧪 Modeling Summary

- **Model Used**: Random Forest Regressor  
- **Sample Size**: Full dataset (no downsampling used in final version)  
- **Evaluation Metrics**:
  - ✅ **R² Score**: `0.1461`
  - ✅ **Mean Absolute Error (MAE)**: `$33,886.95`
  - ✅ **Root Mean Squared Error (RMSE)**: `$89,472.55`

---

## 🖼️ Visual Insights

- Average salary by years of professional coding experience
- Model performance metrics
- Prediction for a hypothetical developer profile

Example Plot:  
![Salary by Experience](images/salary_by_education.png)

---

## 🧾 Files in this Repository

| File | Description |
|------|-------------|
| `developer_salary_model.ipynb` | Complete notebook with CRISP-DM analysis |
| `images/` | Saved visualizations from the notebook |
| `README.md` | This file |

---

## 💬 Sample Scenario

Ever wondered what salary a developer with 5 years of experience, working remotely in the U.S. using Python and JavaScript, might earn?  
Our model predicts approximately **$X**, demonstrating how this tool can support job seekers and recruiters.

---

## 🚀 Future Improvements

To improve prediction accuracy:
- Add more technical features (e.g., frameworks, cloud platforms)
- Apply NLP to handle free-text responses
- Experiment with advanced models like **XGBoost** or **LightGBM**
- Build a lightweight web app for interactive predictions

---

## 🙏 Acknowledgments

- **Stack Overflow** for providing the dataset: [survey.stackoverflow.co](https://survey.stackoverflow.co/)
- **Udacity** for project structure, reviewer feedback, and guidance throughout
- **CRISP-DM** methodology for a structured and reproducible analysis workflow
- Public tutorials and inspiration:
  - https://medium.com/@pratitisoumya/predicting-developer-salaries-with-machine-learning-f2d81579af86  
  - https://github.com/tien02/salary-prediction

---

_Thank you for visiting this repository!_
