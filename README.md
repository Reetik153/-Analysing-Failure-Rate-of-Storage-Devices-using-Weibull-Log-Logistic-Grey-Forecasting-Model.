# Analysing Failure Rate of Storage Devices using Weibull Log Logistic Grey Forecasting Model.
This project analyzes HDD failure rates using the Weibull Log-Logistic Grey Forecasting Model (WLLGM). By combining Weibull and Log-Logistic distributions with grey modeling and optimization, it delivers more accurate predictions than MLR, helping data centers reduce downtime and replacement costs.

**🎯 Objectives**

Predict HDD failures with greater accuracy to enhance storage reliability.

Implement a Grey forecasting model with nonlinear features.

Compare performance against MLR using real-world HDD data.

Identify the most influential SMART attributes for failure prediction.

**📊 Dataset**

Source: Backblaze HDD Dataset

Attributes Used: SMART parameters such as Reallocated Sector Count, Power-On Hours, etc.

HDD Models: ST14000NM001G, ST4000DM000, ST14000NM0138

**⚙️ Methodology**

Data Preprocessing – Cleaning and selecting SMART attributes.

Model Formulation – Weibull + Log-Logistic mixture distribution.

Parameter Estimation – Using Whale Optimization Algorithm (WOA).

Interaction Effects – Capturing nonlinear relationships.

Evaluation – Metrics: MAPE, RMSE, MAE, and Standard Deviation.

**📈 Results**

WLLGM outperformed MLR across all evaluation metrics.

SMART 5 (Reallocated Sector Count) was the most critical predictor of HDD failure.

Reduced false positives led to fewer unnecessary HDD replacements and cost savings.

**🚀 Future Scope**

Extend to SSDs and cloud storage systems.

Integrate with machine learning models for hybrid forecasting.

Apply to other mechanical systems (e.g., turbines, vehicles).

**🛠️ Tech Stack**

Languages: Python, R (optional)

Libraries: NumPy, Pandas, SciPy, Matplotlib, Scikit-learn

Optimization: Whale Optimization Algorithm (WOA)

**👥 Team Members**

Ritesh Patil

Darshana Parle

Sejal Mahadik

Reetik Prajapati

Nishad Sangale

📜 License

This project is for academic and research purposes. Feel free to fork, modify, and use it with proper attribution.
