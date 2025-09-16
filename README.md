🛍️ Customer Segmentation on Shopping Trends Dataset

📌 Project Overview

This project focuses on Customer Segmentation using the Customer Shopping Trends Dataset.
The goal is to identify different groups of customers based on their demographics and purchasing behavior, which can help businesses:
•	Understand customer needs better
•	Personalize marketing campaigns
•	Improve product recommendations
•	Enhance overall customer experience

⚙️ Workflow

1.	Data Preprocessing
-	Handled missing values and duplicates
-	Encoded categorical features & scaled numerical features
-	Used ColumnTransformer for efficient transformations
2.	Exploratory Data Analysis (EDA)
-	Univariate & bivariate analysis of demographics and purchases
-	Visualized spending patterns with Matplotlib & Seaborn
3.	Clustering (KMeans)
-	Applied KMeans to group customers
-	Determined optimal clusters using Elbow Method & Silhouette Analysis
4.	Model Evaluation
-	Silhouette Score
-	Davies-Bouldin Index
-	Calinski-Harabasz Score
5.	Visualization & Insights
-	Applied PCA for dimensionality reduction
-	Visualized clusters in 2D
-	Profiled clusters to derive customer personas

🛠️ Tech Stack

•	Python 🐍
•	pandas, numpy
•	matplotlib, seaborn
•	scikit-learn

📂 Repository Structure

├── Customer_segmentation.ipynb   # Main Jupyter Notebook
├── data/                         # Dataset or link
├── images/                       # Plots & visualizations
├── video_demo.mp4                 # Short demo video (optional)
└── README.md                     # Documentation

🚀 How to Run

1.	Clone the repository:
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
2.	Install dependencies:
pip install -r requirements.txt
3.	Open Jupyter Notebook:
jupyter notebook Customer_segmentation.ipynb

Results & Insights

•	Segmented customers into distinct groups
•	Derived personas such as:
-	Budget-conscious shoppers
-	Loyal frequent buyers
-	High-value customers
These insights can help businesses with targeted marketing and customer retention strategies.

🔗 Dataset
Dataset: Customer Shopping Trends Dataset

🙌 Acknowledgements
This project is part of my Data Science learning journey.
Thanks to the open-source community for tools and resources.

🏷️ Tags

#DataScience #MachineLearning #Clustering #CustomerSegmentation #EDA
