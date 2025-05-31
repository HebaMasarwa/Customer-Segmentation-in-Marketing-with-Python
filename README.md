# Customer Segmentation in Marketing with Python 

This project explores how acquisition channels and geographic regions relate to student engagement on an educational platform. Using clustering techniques and exploratory data analysis, we identify meaningful customer segments to guide marketing strategies and optimize resource allocation.

## Objective

The goal is to analyze whether acquisition **channel** and **region** provide insight into student **engagement**—measured by learning minutes—and **spending behavior**. We aim to identify high-performing customer segments and suggest targeted marketing actions.

## Data

The dataset includes:
- Features for:
  - **Acquisition Channel** (e.g., YouTube, LinkedIn, Facebook)
  - **Region** (e.g., Anglo-Saxon, Europe, Rest of World)
- **Engagement Metrics**: Learning minutes
- **Spending Metrics**: Customer Lifetime Value (CLV)

## Methodology

### 1. Data Preprocessing
- Cleaning the data
- Standardization of features for clustering

### 2. Clustering
- **K-Means Clustering** with Hierarchical Clustering and the use of the Elbow Method to determine optimal number of clusters
- Assignment of each customer to a segment based on engagement, region, and channel

### 3. Segment Analysis
For each segment:
- Count of observations
- Proportion of customer base
- Average learning minutes and CLV
- Dominant region and acquisition channel

## Key Insights

- **Anglo-Saxon Multi-Channel**: Largest and most profitable group (27%), strong presence on YouTube and LinkedIn.
- **European Multi-Channel**: High engagement and CLV, mostly from YouTube. Worth expanding marketing in Europe.
- **Facebook Followers**: Small but highly engaged (highest learning minutes). Recommend focused, education-centered campaigns.
- **LinkedIn Networkers**: Career-focused users with moderate engagement. Suggest professional success stories in campaigns.
- **Friends’ Influence**: Strong performance via referrals. Consider referral incentives to grow this group.
- **Google Group**: Performs well; continue investing in intent-based search strategies.
- **Instagram Explorers**: Moderate spending but lower engagement. Explore more educational content to improve.
- **Twitter Devotees**: Lowest engagement and CLV. Recommend cutting back investment and monitoring alternative platforms like Threads.

## Conclusion

This segmentation provides actionable insights into where marketing efforts should be focused. By prioritizing high-CLV and highly engaged segments, the company can improve ROI and better serve learners.

## Tools Used

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn) (version 3.13.1)
- Jupyter Notebook

## Folder Structure
📁 customer-segmentation-project/

├── **eda.ipynb:** Exploratory Data Analysis including cleaning and preparing the data for modeling

├── **modeling.ipynb:** Clustering and modeling workflow including K-Means and customer segmentation

├── **customer_segmentation_data.csv:** Original raw dataset

├── **cleaned_segmentation_data.csv:** Cleaned and processed dataset used for modeling


