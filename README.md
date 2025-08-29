# Divorce Econometrics Project

This project applies econometric methods to analyze the determinants of divorce using IPUMS survey data. We estimate a **linear probability model (LPM)** to evaluate how demographic, socioeconomic, and family-related variables influence the likelihood of divorce.

---

## 📊 Research Question
What factors are most strongly associated with divorce, and how do age, income, education, employment, and number of children contribute to predicting divorce probability?

---

## ⚙️ Methodology
- **Dataset:** IPUMS survey data  
- **Dependent Variable:** Divorce (binary indicator)  
- **Independent Variables:**  
  - Age at marriage  
  - Education level  
  - Income  
  - Employment status  
  - Number of children  

### Steps
1. **Data Cleaning**  
   - Imported IPUMS data into R  
   - Recoded categorical variables  
   - Handled missing values  

2. **Model Estimation**  
   - Fitted **linear probability model (LPM)** using `lm()`  
   - Conducted hypothesis testing and p-tests  
   - Ran heterogeneity checks across subgroups  

3. **Validation & Analysis**  
   - Examined significance of coefficients  
   - Interpreted marginal effects of predictors  
   - Compared robustness across specifications  

---

## 🛠️ Tools
- **R** (data analysis and modeling)  
- **R Markdown** (documentation and reproducibility)  
- **IPUMS** (data source)  

