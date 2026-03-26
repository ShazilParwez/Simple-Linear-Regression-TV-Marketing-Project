# Simple Linear Regression on TV Marketing (ML Project)

This repository contains a **Machine Learning Project** that demonstrates a complete ML pipeline using **Simple Linear Regression** on a TV marketing dataset.  
The project predicts **Sales** based on **TV Marketing Cost**.  

---

## 🔹 Project Workflow
1. **Data Ingestion**  
   - Imported dataset (`tvmarketing.csv`)  
   - Inspected with `.head()`, `.tail()`, `.sample()`, `.describe()`, `.isna()`  

2. **Exploratory Data Analysis (EDA)**  
   - Scatter plot between TV and Sales to visualize correlation  

3. **Data Preparation**  
   - Divided dataset into `X` (TV) and `y` (Sales)  

4. **Train-Test Split**  
   - 75% training data, 25% testing data  

5. **Scaling (Standardization)**  
   - Applied `StandardScaler` to improve convergence during gradient descent  

6. **Model Building**  
   - Trained `LinearRegression` model  

7. **Model Evaluation**  
   - Evaluated using:  
     - **R² Score**  
     - **Mean Absolute Error (MAE)**  
     - **Mean Squared Error (MSE)**  
   - Visualized regression line on both training and testing sets  

---

## Results
- Model successfully fit the data and showed a strong positive correlation between TV Marketing and Sales.  
- **Scaling improved convergence** but did not change predictions significantly (since it’s simple linear regression).  

---

## Conclusion
- **This project demonstrates how TV Marketing Cost directly influences Sales.**  
- It provides a hands-on example of a complete ML pipeline: from data ingestion → preprocessing → model building → evaluation.  
- A higher TV marketing budget generally results in increased sales.  

---

## Requirements
Install the required libraries using:

```bash
pip install -r requirements.txt
