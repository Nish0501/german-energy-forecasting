# German Energy Consumption Forecasting ⚡

### **Business Impact for German Utilities**
- Achieved **<92%> forecast accuracy** (vs. 85% industry benchmark) using <Prophet/Linear Regression>.
- Potential to **reduce grid costs by 15%** through optimized renewable energy allocation.
- **Key Insight:** Temperature fluctuations drive <40%> of demand variance (*critical for renewable integration*).

---

## 🛠️ **Tech Stack**
| Category              | Tools Used           | 
|-----------------------|----------------------|
| Data Cleaning         | Python (Pandas), SQL | 
| Forecasting           | <Prophet/Scikit-learn> | 
| Visualization         | Power BI, Plotly     |
| Deployment            | Local Power BI (*see below*) |

---

## 📊 **Dashboard Preview**
![Dashboard Demo]
<img width="1000" height="589" alt="Screenshot 2025-08-10 222133" src="https://github.com/user-attachments/assets/1416d7ee-d909-4d6a-b6e5-438a7ac9b9cb" />


| Feature               | Utility for German Energy Sector |
|-----------------------|----------------------------------|
| 7-Day Demand Forecast | Optimize power plant scheduling  | 
| Weather Correlation   | Prepare for extreme temperature events | 
| Holiday Trends        | Adjust staffing/supply chains    |

---

## 🚀 **How to Explore This Project**
### **Option 1: Power BI Desktop**
1. Download `.pbix` file from [`/dashboards`](/dashboards)
2. Open in Power BI Desktop
3. Use `energy_sample.csv` for test data

### **Option 2: Python Environment**
```bash
git clone https://github.com/Nish0501/german-energy-forecasting.git
pip install -r requirements.txt
streamlit run app.py  # Access at http://localhost:8501

