Customer Segmentation on Shopping Trends Dataset
📌 Project Overview

This project focuses on Customer Segmentation using the Customer Shopping Trends Dataset.
The goal is to identify different groups of customers based on their demographics and purchasing behavior, which can help businesses:

Understand customer needs better

Personalize marketing campaigns

Improve product recommendations

Enhance overall customer experience

The project demonstrates the end-to-end workflow of a data science solution, from data preprocessing to deriving insights.

⚙️ Project Workflow
1. Data Preprocessing

Handled missing values and duplicates

Applied encoding to categorical features and scaling to numerical features

Used ColumnTransformer for efficient transformations

2. Exploratory Data Analysis (EDA)

Univariate and bivariate analysis of demographics & purchase behavior

Visualized customer spending patterns with Matplotlib & Seaborn

3. Clustering with KMeans

Applied KMeans Clustering to group customers

Determined optimal clusters using Elbow Method & Silhouette Analysis

4. Model Evaluation

Silhouette Score

Davies-Bouldin Index

Calinski-Harabasz Score

5. Visualization & Insights

Applied PCA (Principal Component Analysis) to reduce dimensions for visualization

Visualized clusters in 2D

Profiled clusters to derive customer personas

🛠️ Tech Stack

Programming Language: Python 🐍

Libraries Used:

pandas – data manipulation

numpy – numerical operations

matplotlib, seaborn – visualization

scikit-learn – clustering & preprocessing

📂 Repository Structure
├── Customer_segmentation.ipynb   # Main Jupyter Notebook
├── data/                         # Dataset (or link in README)
├── images/                       # EDA & clustering plots
├── video_demo.mp4                 # Short demo video (optional)
└── README.md                     # Project documentation

🚀 How to Run

Clone the repository

git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook Customer_segmentation.ipynb

📊 Results & Insights

Successfully segmented customers into distinct clusters

Derived customer personas such as:

Budget-conscious shoppers

Loyal frequent buyers

High-value customers

📈 These insights can help businesses improve targeted marketing and customer retention strategies.

🔗 Dataset

The dataset used: Customer Shopping Trends Dataset
.

🙌 Acknowledgements

This project was created as part of my Data Science learning journey.
Special thanks to the open-source community for tools & resources.

🏷️ Tags

#DataScience #MachineLearning #Clustering #CustomerSegmentation #EDA
