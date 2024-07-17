
# Customer Segmentation Using Machine Learning Models

The most successful companies today are the one's who know their customers so well that they are able to anticipate their needs beforehand. This can better be achieved if we can segment the customers into different groups that reflect the similarities among the customers in each group. The goal of the segmentation is to foresee the needs of customers, get to know their interests, lifestyles, priorities and learn their spending habits so that to maximize the value of customers to the business. In other words to find the most profitable customers amoung a large set of customer group.




## Installation


### Prerequisites

1. Ensure you have Python installed (preferably Python 3.7+).
2. Install the required libraries. You can do this by running

```bash

  pip install numpy pandas matplotlib seaborn scikit-learn


```
    
### Instructions to Execute the . py Script
   
#### Using the Command Line:

  
 1. Save the Script:

Save the provided script as customer_segmentation.py.

 2. Ensure Data File Availability:
    
The script reads the dataset from "/content/sample_data/   Mall_Customers.csv". Make sure you have the Mall_Customers.csv file in the specified location or update the script with the correct path to your dataset.

3. Run the Script:

Open a terminal or command prompt and navigate to the directory where customer_segmentation.py is saved. Then, run the script using:

 ```bash

python customer_segmentation.py


```





### Instructions to Execute the .ipynb script

#### Using Jupyter Notebook:

Ensure you have Jupyter Notebook installed. You can install it using pip if it's not already installed:

```bash

  pip install notebook


```

1. Open your terminal or command prompt.

2. Navigate to the directory containing customer_segmentation.
   ipynb file.

3. Start the Jupyter Notebook server by typing:
    

```bash

  jupyter notebook


```

1. This will open a new tab in your web browser with the Jupyter Notebook interface.

2. Navigate through the interface to open the
   customer_segmentation.ipynb file.


#### Using JupyterLab:

Ensure you have JupyterLab installed. You can install it using pip:


```bash

  jupyter notebookpip install jupyterlab

```

1. Open your terminal or command prompt.
2. Navigate to the directory containing the customer_segmentation.
   ipynb file.
3. Start JupyterLab by typing.


```bash

  jupyter lab

```

1. This will open a new tab in your web browser with the JupyterLab interface.
2. Navigate through the interface to open customer_segmentation.
   ipynb file.


####  Using Visual Studio Code (VSCode):

1. Ensure you have the Python extension installed in VSCode.
2. Open VSCode and load your .ipynb file.
3. You should see the notebook interface within VSCode, allowing you to run cells interactively.





## Dataset

The dataset we have taken from Kaggle. Below is the link to the dataset.

https://www.kaggle.com/datasets/shwetabh123/mall-customers

Place the Mall_Customers.csv dataset in the appropriate path or update the script with the correct path to your dataset.

The dataset contains the following deatils of different customers.


1. CustomerID: Unique ID assigned to each customer.

2. Gender: Gender of the customer.

3. Age: Age of the customer.

4. Annual Income (k$): Annual income of the customer in thousands of dollars.

5. Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

But we are only considering Gender, Age , Annual Income and Spending Score as the features for the analysis and prediction of customer segmentation.
## Project Structure


The code is divided into the following sections:

1. Load Dataset: Load the customer data from a CSV file.

2. Preprocess the Data: Clean the data by removing unnecessary
   columns and selecting relevant features.

3. Scale the Data: Standardize the features to have zero mean and
   unit variance.

4. Apply K-MEANS/Agglomerative/DBSCAN: Perform clustering using
   any of the algorithm

5. Analyze Clusters: Generate summary statistics for each cluster.
## Algorithms Involved

K-means Clustering

K-Means is a centroid-based algorithm that partitions the data into K clusters. It minimizes the sum of squared distances between data points and their assigned cluster centers.


Agglomerative Clustering

Agglomerative Clustering is a hierarchical clustering method that builds a hierarchy of clusters by merging smaller clusters into larger ones based on similarity.

DBSCAN(Density-Based Spatial Clustering of Applications with Noise)

DBSCAN groups together points that are closely packed and marks points in low-density regions as outliers. It does not require the number of clusters to be specified beforehand. Unlike other clustering algorithms, such as k-means, DBSCAN does not require the user to specify the number of clusters in advance. Instead, it relies on two key parameters: epsilon (ε) and minimum points (minPts).
## Conclusion

This project successfully demonstrates the application of three distinct clustering algorithms—K-Means, Agglomerative Clustering, and DBSCAN—to achieve effective customer segmentation. By analyzing customer data, we have highlighted the strengths and unique benefits of each algorithm in uncovering meaningful patterns and segmenting customers into distinct groups.

## Key Features

K-Means Clustering: Provides a simple and efficient way to segment customers based on their similarities.
Agglomerative Clustering: Offers a hierarchical approach, revealing the nested structures within the data.
DBSCAN: Effectively identifies clusters of varying densities and shapes, as well as outliers.

## Observations


Conservative Spenders: This cluster includes customers with a higher average age and annual
income, but a lower spending score. They may be more conservative with their spending and
focused on saving their money.


Young and Wealthy: This cluster includes customers with a lower average age and a high annual
income and spending score. They are likely younger, wealthier customers who are more likely to
spend on luxury goods and experiences.

Budget Shoppers: This cluster includes customers with a lower average age and annual income, but
a relatively high spending score. They may be focused on getting the most for their money and
finding deals and discounts.

Middle-Aged Moderates: This cluster includes customers with a higher average age and a moderate
annual income and spending score. They may be more conservative with their spending than the
Young and Wealthy cluster but still have more disposable income than the Budget Shoppers cluster.
## Contacts

Email: ajilaleyas@gmail.com 

LinkedIn: www.linkedin.com/in/ajilaleyas

Github: ajilaleyas



## Project URL

https://github.com/ajilaleyas/machine_learning-works