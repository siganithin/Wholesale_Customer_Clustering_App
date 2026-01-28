# Wholesale_Customer_Clustering_App

This project is an interactive Streamlit dashboard that uses K-Means clustering to segment wholesale customers based on their purchasing behavior. It helps identify hidden customer groups to support better business decision-making.

---

## Business Problem

A wholesale distributor serves different types of clients such as retail stores, cafés, hotels, and restaurants. Treating all customers in the same way leads to inefficient inventory planning, poor marketing strategies, and missed upselling opportunities.

This project groups customers based on similarities in their annual spending patterns to improve decision-making.

---

## Objective

- Discover customer segments without predefined labels  
- Understand purchasing behavior using clustering techniques  
- Provide business-friendly insights through interactive visualizations  

---

## Approach

- Selected numerical spending features representing customer purchase behavior  
- Applied feature scaling using StandardScaler for fair distance calculation  
- Used K-Means clustering with user-controlled parameters  
- Visualized clusters and generated non-technical business interpretations  

---

## Dashboard Features

- Selection of any two numerical features for clustering  
- Adjustable number of clusters (K = 2 to 10)  
- Button-based clustering execution for better understanding  
- 2D scatter plot with clearly marked cluster centers  
- Cluster summary table and simple business interpretation  

---

## Project Structure

```text
Wholesale_Customer_Clustering_App/
│
├── app.py
├── wholesale_customers.csv
├── requirements.txt
└── README.md
```
-Technologies Used
Python
Streamlit
Pandas
NumPy
Scikit-learn
Matplotlib

-How to Run the Project
1.Install the required dependencies:
pip install -r requirements.txt

2.Run the Streamlit application:
streamlit run app.py
