# Customer Segmentation Project

##  Overview
This project demonstrates how customer data can be segmented based on purchasing behavior and engagement metrics.  
The goal is to identify meaningful customer groups to optimize retention, marketing campaigns, and communication strategies.

---

##  Objectives
- Analyze customer purchase history and behavioral metrics  
- Apply clustering methods to segment users  
- Visualize and interpret segment characteristics  
- Provide business recommendations for each cluster  

---

##  Dataset
The dataset includes:
- **Customer ID**
- **Total Purchases**
- **Average Order Value**
- **Recency (days since last purchase)**
- **Frequency (orders per customer)**
- **Monetary Value (RFM model)**  

All sensitive data was anonymized.

---

##  Methodology
1. **Data Cleaning:** handled missing values, normalized numerical columns  
2. **Feature Engineering:** created RFM features and log-transformed skewed data  
3. **Clustering:** applied *K-Means* and *Elbow Method* to determine optimal cluster count  
4. **Evaluation:** compared silhouette scores and visualized clusters using PCA  
5. **Business Interpretation:** profiled clusters and proposed retention tactics  

---

##  Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- Jupyter Notebook  
- Excel for initial exploration  
- Power BI for visualization  

---

##  Repository Structure
customer-segmentation/
├── data/ # anonymized dataset (CSV)
├── notebooks/ # Jupyter notebooks for analysis
├── visuals/ # plots and charts
└── README.md # project documentation
## 📊 Example Results
| Cluster | Description | % of Users | Strategy |
|----------|--------------|-------------|-----------|
| 0 | High-value loyal customers | 22% | Maintain engagement through loyalty benefits |
| 1 | New and low-frequency buyers | 31% | Offer onboarding discounts |
| 2 | Lapsed customers | 18% | Target with reactivation campaigns |
| 3 | Mid-value active users | 29% | Upsell with personalized recommendations |

---

## 🔍 Key Insights
- Top 20% of customers generate over 60% of revenue  
- Reactivation campaigns improved retention by ~15%  
- Segmentation helped prioritize marketing budget and improve ROI  

---

##  Author
**Simurzar Farkhadova**  
 Warsaw, Poland | [LinkedIn](https://linkedin.com/in/simurzar) | [Email](mailto:simurzar@gmail.com)

---

> *“Turning behavioral data into clear marketing actions.”*
