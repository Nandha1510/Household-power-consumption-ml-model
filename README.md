# Household-power-consumption-ml-model

### **Comprehensive Report for PowerPulse: Household Energy Usage Forecast**  

---

#### **1. Approach**  
The PowerPulse project follows a structured approach to address the challenge of household energy management:  
1. **Data Understanding**: Explored historical energy consumption data to grasp its structure, variables, and patterns.  
2. **Data Preprocessing**: Cleaned the data by handling missing values, converting datatypes, and removing outliers using Isolation Forest.  
3. **Feature Engineering**: Generated impactful features such as rolling averages, daily averages, peak hour indicators, and time-based variables like `hour`, `day_of_week`, and `month` to enhance prediction accuracy.  
4. **Model Development**: Trained and evaluated multiple machine learning models, including Random Forest, XGBoost, and Neural Networks, with hyperparameter tuning for optimization.  

---

#### **2. Data Analysis**  
Detailed exploratory data analysis (EDA) uncovered critical insights:  
- **Energy Trends**: Correlation heatmaps revealed strong relationships between energy consumption and features like global intensity and voltage.  
- **Usage Patterns**: Time-series analysis highlighted peak consumption hours (6 PM–10 PM) and variations across days of the week.  
- **Outlier Detection**: Identified and removed anomalous data points that could skew model performance.  
- **Feature Importance**: Analyzed the contribution of engineered features to ensure relevance and boost predictive power.  

---

 **3. Model Selection and Evaluation**  
Three models were trained and rigorously evaluated using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R². Key findings:  
- **Random Forest**: Achieved robust performance with quick training and high interpretability.  
- **XGBoost**: Delivered the best accuracy by leveraging GPU acceleration and hyperparameter tuning.  
- **Neural Networks**: Modeled non-linear relationships effectively but required more computational resources.  
The models were validated using cross-validation to ensure stability across datasets.  

---

 **4. Insights and Recommendations**  
- **Key Insights**:  
   - Energy usage peaks during evenings, suggesting the need for demand-side management.  
   - Rolling averages and peak hour indicators significantly improved model accuracy.  
   - Voltage and global intensity were the most critical predictors of energy consumption.  
- **Recommendations**:  
   - Consumers: Leverage insights to optimize energy usage during off-peak hours to reduce costs.  
   - Providers: Integrate this predictive model into demand forecasting systems to enhance grid reliability and efficiency.  
   - Future Enhancements: Incorporate external data like weather conditions for even better accuracy and scalability.  

---

