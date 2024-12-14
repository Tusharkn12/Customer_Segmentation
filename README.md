# Customer Segmentation Project

## 🧠 Introduction to Customer Segmentation
Customer segmentation is the process of dividing a customer base into distinct groups based on shared attributes, behaviors, or preferences. This approach allows businesses to:

- Tailor marketing strategies to specific customer needs.
- Improve customer engagement and satisfaction.
- Enhance overall business performance through data-driven decisions.

This project utilizes advanced machine learning algorithms to achieve effective segmentation, offering insights into customer behavior and preferences. 

## 🔍 Project Overview
This project aims to explore customer segmentation using robust clustering techniques. Building on prior work, it employs sophisticated algorithms and comprehensive data analysis to uncover meaningful patterns. The dataset, sourced from Kaggle, serves as a practical example for applying machine learning in business intelligence.

## 📂 Dataset Details
- **Source**: Kaggle
- **Description**: The dataset includes demographic and behavioral attributes of customers.
- **Preprocessing Steps**:
  - Data standardization using `StandardScaler` for improved model performance.
  - Encoding categorical variables to ensure compatibility with machine learning algorithms.

## 📈 Algorithm Highlights

### 1. K-means Clustering
- Clustered customers into distinct groups using the K-means algorithm.
- Determined the optimal number of clusters using the Elbow Method.
- Segmented data into **3 clusters**, highlighting key behavioral patterns.

### 2. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Leveraged DBSCAN for handling datasets with irregular cluster shapes.
- Identified outliers and noise for nuanced segmentation.
- Enhanced K-means clustering with additional insights.

## 🔧 Technical Stack
- **Programming Language**: Python
- **Libraries Used**:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`

## 📊 Evaluation Metrics
- **Silhouette Score**: Assessed the quality of clustering by measuring intra-cluster cohesion and inter-cluster separation.
- Comparative analysis of K-means and DBSCAN performance using metrics and visualizations.

## 🚀 Results and Insights

### Key Findings
- Successfully identified three customer clusters:
  - **Cluster A**: Dominated by **Artists**.
  - **Cluster B**: Balanced demographics with diverse occupations.
  - **Cluster C**: Features a significant number of healthcare professionals.
- Most customers belong to households with a **family size of 2**.
- Top three professions across clusters:
  1. **Artists**
  2. **HealthCare**
  3. **Entertainment**

### Visualizations
Data visualizations are included to:
- Illustrate cluster distributions.
- Highlight dominant professions within each cluster.
- Display trends in family size and demographics.
- ![download](https://github.com/user-attachments/assets/a7d58d60-b14e-409c-8ce5-79937e405e1a)
![download](https://github.com/user-attachments/assets/902a4e0b-6b87-4d04-9dec-8cd51eaaa5a0)
![download](https://github.com/user-attachments/assets/e8f55ec2-d488-4bd8-a1cc-e5415590fb86)


## 🔗 How to Get Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Tusharkn12/customer-segmentation.git
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project notebook:
   ```bash
   jupyter notebook Customer_Segmentation_2.ipynb
   ```

## 📥 Dataset Access
To access the Kaggle dataset:
1. Install Open Datasets:
   ```bash
   pip install opendatasets
   ```
2. Use the script provided in the notebook to download and preprocess the dataset.

## 📚 Key Learnings
- Preprocessing is critical for effective clustering and improved algorithm performance.
- K-means is efficient for structured data, while DBSCAN excels at detecting outliers and irregular clusters.
- Visualization is invaluable for validating clusters and communicating insights.

## 🤝 Contributing
Contributions are encouraged! If you'd like to add new features or improve existing ones, please fork the repository and submit a pull request.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.

