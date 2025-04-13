# Prediction of Calories Burnt with Machine Learning

The project is intended to forecast the calories burnt while exercising through supervised machine learning. It makes use of exercise-related information (gender, age, height, weight, duration, heart rate, etc.) in order to make precise predictions of calories burnt.

# Project Structure

- Synopsis.pdf** – Detailed synopsis of the project.
- miniproject.html – Project overview page with a link to the Jupyter Notebook.
- miniproject.ipynb – Jupyter Notebook with the complete implementation.
- projectcode final.txt – Plain text of the Jupyter Notebook code for easy reference.

#Dataset

The project utilizes two datasets:

1. exercise.csv – Has details such as gender, age, height, weight, heart rate, duration, etc.
2. calories.csv – Has the corresponding calories burnt values.

These datasets were combined on the common `ID` column.

#⚙️ Features Used

- Gender (encoded)
- Age
- Height (cm)
- Weight (kg)
- Duration (min)
- Heart Rate (bpm)
- Body Temperature (°C)

# Model Used

- Random Forest Regressor – Obtained high accuracy owing to its ensemble nature and the capacity to learn non-linear interactions.

Other models such as Linear Regression and Decision Tree were also tried for comparison.

# Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The Random Forest model provided the best outcome among all.

# Highlights

- Data preprocessing, visualization, and correlation analysis.
- Feature importance analysis to know what has the maximum impact on calorie burn.
- Model comparison for performance evaluation.
- Clean and interactive Jupyter Notebook with comments and explanation.
- Exported notebook in HTML format for easy viewing.

# How to Run

1. Clone the repository:
```bash
git clone https://github.com/shreyas39raina/calories-burnt-prediction.git
cd calories-burnt-prediction
```
2. Open the Jupyter Notebook:
```bash
Copy
Edit
jupyter notebook miniproject.ipynb
Alternatively, see the HTML version through miniproject.html in your browser.
```
✅ Results
```bash
The Random Forest model could predict the calories burnt with great accuracy, which can be useful for fitness monitoring and health use cases.
```
Contact
For any questions or collaboration opportunities, do reach out:

Shreyas D
www.linkedin.com/in/shreyas-d-9668a422a | shreyasappu952003@gmail.com
