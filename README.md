### Business Requirement Document (BRD)  

#### **Objective:**  
To analyze customer churn in the banking sector, identify key factors influencing churn, and develop actionable insights using a Power BI dashboard.  

---

### **Data Dictionary**  

- **RowNumber:** Represents the record (row) number; has no direct impact on churn.  
- **CustomerId:** Contains random values; not related to churn.  
- **Surname:** The surname of a customer; has no impact on churn.  
- **CreditScore:** Indicates the customer's creditworthiness. Higher credit scores are associated with lower churn probability.  
  - **Credit Score Range:**  
    - Excellent: 800–850  
    - Very Good: 740–799  
    - Good: 670–739  
    - Fair: 580–669  
    - Poor: 300–579  

- **Geography:** The customer's location may influence their decision to leave the bank.  
- **Gender:** Analysis can determine if gender impacts churn.  
- **Age:** Older customers tend to have lower churn rates than younger ones.  
- **Tenure:** The number of years a customer has been with the bank. Longer tenure often indicates higher loyalty.  
- **Balance:** Customers with higher account balances are less likely to churn.  
- **NumOfProducts:** Number of bank products purchased by a customer.  
- **HasCrCard:** Indicates whether a customer holds a credit card.  
  - **1:** Credit card holder  
  - **0:** Non-credit card holder  

- **IsActiveMember:** Active customers are less likely to leave.  
  - **1:** Active Member  
  - **0:** Inactive Member  

- **Estimated Salary:** Customers with higher salaries tend to have lower churn rates.  
- **Exited:** Indicates if the customer has churned.  
  - **0:** Retained  
  - **1:** Exited  

- **Bank DOJ:** The date when the customer joined the bank.  

---

### **Data Gathering**  

To perform the analysis, utilize the following data assets to extract relevant customer information:  
- **ActiveCustomer**  
- **Bank_Churn**  
- **CreditCard**  
- **CustomerInfo**  
- **ExitCustomer**  
- **Gender**  
- **Geography**  

---

### **Churn Analysis**  

**Objective:**  
Analyze customer data to uncover insights into factors contributing to churn. This helps banks understand reasons behind customer exits, enabling them to create targeted loyalty programs and retention campaigns to minimize churn and improve customer satisfaction.  

**Deliverables:**  
- Identification of key churn drivers (e.g., age, geography, balance).  
- Insights visualized through an interactive Power BI dashboard.  
- Recommendations for churn prevention strategies based on the analysis.  

