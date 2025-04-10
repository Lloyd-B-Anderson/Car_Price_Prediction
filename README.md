### **Car Price Prediction for Rusty Bargain**  

#### **Project Goal**  
Build a fast and accurate model to predict used car prices for Rusty Bargain’s app, comparing:  
- **Linear Regression** (baseline)  
- **Decision Tree**  
- **Random Forest**  
- **Gradient Boosting (LightGBM, XGBoost, CatBoost)**  

#### **Key Steps**  
1. **Data Prep**  
   - Cleaned missing values and outliers  
   - Engineered features (e.g., filtered registration years, standardized power)  
   - Encoded categorical variables  

2. **Model Comparison**  
   - Trained & tuned hyperparameters (GridSearchCV)  
   - Evaluated using **RMSE**  
   - Measured speed (training & prediction)  

3. **Results**  
   - **Best Model:** **LightGBM** (RMSE: **1704**, Train Time: **23.5s**)  
   - **Fastest Training:** **XGBoost** (**12.8s**)  
   - **Highest Accuracy:** **Random Forest (Ajustado)** (RMSE: **1676**, but slowest)  

#### **Conclusion**  
**LightGBM** provided the best balance of accuracy and speed for Rusty Bargain’s needs.  

---  
**Tools:** Python, Pandas, Scikit-learn, LightGBM, XGBoost, CatBoost  
**Skills:** Regression, Hyperparameter Tuning, Feature Engineering  

---

### Key Takeaways:  
- **LightGBM** recommended for production (best speed/accuracy trade-off).  
- **XGBoost** is ideal for rapid prototyping (fastest training).  
- **Random Forest** (tuned) is most accurate but slow (best for offline use).  
