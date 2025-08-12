# German Energy Consumption Forecasting

### Project Overview

This project presents a comprehensive, end-to-end analysis of German energy consumption data, with the primary goal of building a predictive model for future demand. The project demonstrates a full data analytics workflow, from raw data cleaning and feature engineering to machine learning modeling and the creation of an interactive business intelligence dashboard.

### Tools and Technologies

* **Data Analysis & Cleaning:** Python (Pandas)
* **Time-Series Modeling:** Python (Prophet or Scikit-learn for Linear Regression)
* **Data Visualization:** Python (Matplotlib, Seaborn)
* **Business Intelligence:** Power BI
* **Version Control:** Git, Git LFS, GitHub
* **Dataset:** German Energy and Weather Data (Kaggle/ENTSO-E)

### Key Business Insights & Recommendations

The predictive model and dashboard provide direct, actionable insights for a German utility company:

* **Accurate Demand Forecasting:** The model provides a reliable forecast of future energy demand with a Mean Absolute Error (MAE) of **<Your MAE Value>** and a Root Mean Squared Error (RMSE) of **<Your RMSE Value>**.
    * **Recommendation:** This forecast can be used to optimize energy supply, reduce costs, and enhance grid stability, especially when integrating renewable energy sources.

* **Impact of External Factors:** The analysis revealed that external factors like **temperature** and **public holidays** are significant drivers of energy consumption.
    * **Recommendation:** These insights can be used to refine short-term supply chain management and make more informed strategic decisions during extreme weather events or holiday seasons.

* **Data-Driven Decision Making:** The interactive dashboard allows stakeholders to visualize historical consumption trends and instantly see the model's predictions, empowering them to make proactive, data-driven decisions.

### Project Methodology

The project followed a structured, professional data science pipeline:

1.  **Data Cleaning & Preprocessing:** The raw data was cleaned to handle multi-level headers and improper datetime formatting. Data was aggregated from an hourly to a daily frequency to simplify the analysis.
2.  **Feature Engineering:** Time-based features and external factors (like weather data) were prepared to train the predictive model.
3.  **Predictive Modeling:** A machine learning model was trained to forecast future energy consumption. The model was rigorously evaluated using standard metrics like MAE and RMSE.
4.  **Dashboarding:** The final output is an interactive Power BI dashboard that visualizes the model's predictions against the actual data, making the results clear and accessible.

### Dashboard Preview

Here is a screenshot of the interactive Power BI dashboard, which showcases the model's performance and key insights.

![German Energy Consumption Forecast Dashboard Screenshot](<img width="1000" height="589" alt="Screenshot 2025-08-10 222133" src="https://github.com/user-attachments/assets/3dca2c9e-993f-4e9e-a708-ea7d60d68876" />
)

*Note: The Power BI file (.pbix) is available in the `dashboards/` directory for full interactivity.*

### How to Replicate This Project

To explore this project on your local machine, you can clone the repository and open the Jupyter Notebooks in the `notebooks/` folder. The final dashboard can be opened using Power BI Desktop.
