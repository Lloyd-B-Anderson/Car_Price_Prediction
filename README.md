# **Car Price Prediction for Rusty Bargain**  

### **Project Goal**  
Build a fast and accurate model to predict used car prices for Rusty Bargain’s app, comparing:  
- **Linear Regression** (baseline)  
- **Decision Tree**  
- **Random Forest**  
- **Gradient Boosting (LightGBM, CatBoost, XGBoost)**  

### **Key Steps**  
1. **Data Prep**  
   - Cleaned missing values  
   - Engineered features (e.g., date extraction)  
   - Encoded categorical variables  

2. **Model Comparison**  
   - Trained & tuned hyperparameters  
   - Evaluated using **RMSE**  
   - Measured speed (training & prediction)  

3. **Results**  
   - **Best Model:** LightGBM (RMSE: 1704.12)  
   - **Training Time:** XGBoost was most efficient  

### **Conclusion**  
LightGBM provided the best balance of accuracy and speed for Rusty Bargain’s needs.  

---  
**Tools:** Python, Pandas, Scikit-learn, LightGBM  
**Skills:** Regression, Hyperparameter Tuning, Feature Engineering
