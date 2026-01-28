# Wholesale_Customer_Clustering_App
An interactive Streamlit dashboard that uses K-Means clustering to segment wholesale customers based on their purchasing behavior, helping identify distinct customer groups for better business decision-making.




# Customer Segmentation Dashboard (K-Means Clustering)

This project is an interactive **Streamlit dashboard** that uses **K-Means clustering** to segment wholesale customers based on their purchasing behavior.  
It helps identify hidden customer groups to support better business decision-making.

---

## 📌 Business Problem
A wholesale distributor serves different types of clients such as retail stores, cafés, hotels, and restaurants.  
Treating all customers the same leads to:
- Inefficient inventory planning  
- Poor marketing strategies  
- Missed upselling opportunities  

This project groups customers based on similarities in spending patterns.

---

## 🎯 Objective
- Discover customer segments without predefined labels  
- Understand purchasing behavior using clustering  
- Provide business-friendly insights through visualization  

---

## 🧠 Approach
- Feature selection based on annual spending categories  
- Data scaling using StandardScaler  
- K-Means clustering with user-controlled parameters  
- Interactive visualization and cluster interpretation  

---

## 🖥️ Dashboard Features
- Select any two numerical features for clustering  
- Choose number of clusters (K = 2 to 10)  
- Run clustering interactively using a button  
- Visualize clusters and centroids in a 2D scatter plot  
- View cluster summary and business interpretation  

---

## 📂 Project Structure
Wholesale_Customer_Clustering_App/
│
├── app.py
├── wholesale_customers.csv
├── requirements.txt
└── README.md


---

## ⚙️ Technologies Used
- Python  
- Streamlit  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## ▶️ How to Run the Project

1. Install dependencies:
```bash
pip install -r requirements.txt

2.Run the Streamlit app:
streamlit run app.py
