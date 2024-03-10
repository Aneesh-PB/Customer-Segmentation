# Customer-Segmentation
## Customer Segmentation in Python

This project implements customer segmentation techniques in Python to group customers based on their purchase behavior. 

### Functionality

The script performs the following actions:

1. **Data Acquisition:** Loads customer purchase data from a public UCI Machine Learning Repository dataset.
2. **Data Cleaning:** Prepares the data by handling missing values, removing outliers, and converting data types.
3. **RFM Analysis:** Calculates Recency, Frequency, and Monetary Value for each customer based on their purchase history.
4. **RFM Scoring:** Assigns scores to Recency, Frequency, and Monetary Value based on predefined ranges.
5. **K-Means Clustering:** Segments customers into distinct groups using the K-means clustering algorithm. The optimal number of clusters is determined using the elbow method.
6. **Cluster Interpretation:** Analyzes the characteristics of each segment by calculating average RFM scores.
7. **Customer Distribution:** Visualizes the distribution of customers across the identified segments.

###  Outputs

The script generates the following outputs:

* **Customer Segmentation:** Customers are segmented into a predefined number of clusters based on their RFM scores.
* **Cluster Analysis:** A report detailing the average RFM scores for each cluster, helping to identify distinct customer segments.
* **Customer Distribution:** A pie chart visualizing the percentage of customers belonging to each segment. 

### Dependencies

The script relies on the following Python libraries:

* pandas
* matplotlib.pyplot
* sklearn.preprocessing.StandardScaler
* sklearn.cluster.KMeans

### Instructions

1. **Prerequisites:** Ensure you have Python and the mentioned libraries installed.
2. **Run the Script:** Execute the Python script (`Customer_Segmentation_in_Python.ipynb`) using a Jupyter Notebook environment.

###  Additional Notes

* This is a basic customer segmentation approach. 
* Consider incorporating more customer data and exploring advanced machine learning algorithms for enhanced segmentation.
* Further analysis can be conducted to define targeted marketing strategies for each segment.
