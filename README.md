# Customer Segmentation Using Machine Learning

This project focuses on segmenting wholesale customers based on their purchasing behavior using various machine learning techniques. The goal was to uncover meaningful patterns in the data that could inform and optimize customer service strategies.

## Project Overview

### 1. **Data Exploration and Preprocessing**
   - **Data Exploration:** Analyzed the dataset to understand the distribution and relationships between features.
   - **Feature Selection:** Identified relevant features for clustering by analyzing their correlations and significance.
   - **Feature Scaling:** Applied standardization to ensure all features contributed equally to the model.

### 2. **Feature Transformation**
   - **Principal Component Analysis (PCA):** Reduced the dimensionality of the data while preserving most of the variance. This step helped in simplifying the clustering process and visualizing high-dimensional data in two dimensions.

### 3. **Clustering Algorithms**
   - **K-Means vs. Gaussian Mixture Models:** Compared these two clustering algorithms to determine the optimal segmentation of customers. Evaluated each algorithm using silhouette scores to identify the best number of clusters.

### 4. **A/B Testing**
   - Designed an A/B test to evaluate the impact of changing the delivery service frequency on different customer segments. This helped determine which customer groups would react positively to changes in service.

### 5. **Supervised Learning for Segment Prediction**
   - Trained a supervised learning model on the clustered data to predict customer segments for new clients based on their estimated spending. This approach enabled the wholesale distributor to classify new customers accurately and tailor services accordingly.

## Key Insights
- **Customer Segments:** Successfully identified distinct customer segments, such as restaurants and retailers, based on their purchasing patterns.
- **Optimization:** Provided recommendations for optimizing delivery schedules and customer service strategies based on segment behavior.
- **Scalability:** The supervised learning model allows for easy classification of new customers, enabling scalable and personalized service.

## Conclusion
This project demonstrates the power of machine learning in understanding customer behavior and optimizing business strategies. By leveraging clustering and predictive modeling, businesses can make data-driven decisions that enhance customer satisfaction and operational efficiency.

## How to Use
Clone this repository and explore the notebooks to see the step-by-step implementation of customer segmentation using machine learning.

## GitHub Link
[Link to Project Repository](https://github.com/icodebest/Creating-Customer-Segments) 

