##Customer Segmentation with K-Means Clustering
This project applies K-Means clustering to segment customers based on their Annual Income and Spending Score.
The goal is to help businesses understand and target different customer types more effectively.

##Data Used
- Annual Income (k$)
- Spending Score (1–100)
- 200 customer records from a mall dataset

##Key Findings
Based on K-Means with 5 clusters, we identified the following customer segments:
1. **High income, high spenders** – valuable customers
2. **High income, low spenders** – potential for upselling
3. **Low income, high spenders** – price-sensitive but active
4. **Low income, low spenders** – budget shoppers
5. **Moderate income and spending** – general audience
These insights can guide personalized marketing strategies, promotional offers, and better customer engagement.

##Tools Used
- Python (Jupyter Notebook)
- pandas, seaborn, matplotlib
- scikit-learn (KMeans)

##Folder Structure
customer-segmentation/
├── data/                      # Dataset (CSV)
├── notebooks/                # Jupyter notebook
│   └── 01_customer_segmentation.ipynb
├── outputs/                  # Plots and visuals
├── README.md                 # Project overview

##How to Run
1. Clone this repository
2. Open the notebook `01_customer_segmentation.ipynb` in Jupyter
3. Run all cells to reproduce the clustering analysis and plots
