# Pyspark Recap

![PySpark Overview](/61515pyspark-filter.png)

This repository provides a concise recap of PySpark operations focusing on RDD (Resilient Distributed Dataset) and DataFrame operations. It includes Jupyter notebooks and datasets to help understand the key concepts and functionalities of PySpark.

## Repository Structure

- **1- SparkRDD Operations & DFs.ipynb**: 
  - This notebook covers various operations that can be performed on Spark RDDs and DataFrames. It includes examples of transformations and actions, highlighting the differences and similarities between RDD and DataFrame APIs.

- **2- SparkDataFrameOperations.ipynb**:
  - This notebook dives deeper into DataFrame operations, focusing on more advanced DataFrame manipulations, SQL queries, and schema management. It also demonstrates how to work with different file formats such as JSON and CSV.

- **RDD operations.ipynb**:
  - This notebook provides a focused exploration of RDD operations, detailing common transformations like `map`, `filter`, `reduceByKey`, and `groupByKey`, as well as actions like `collect`, `count`, and `take`.

- **Datasets**:
  - `NullData.csv`: A sample CSV file with missing data, used for DataFrame operations.
  - `people.json`: A sample JSON file containing people’s data, used for loading and processing data in DataFrames.
  - `sf-fire-calls.zip`: A compressed dataset related to San Francisco fire department calls, used for demonstrating real-world DataFrame operations.

## Getting Started

To get started with the notebooks in this repository:

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/Pyspark-Recap.git ```

Install the required dependencies:
```
  pip install pyspark jupyterlab
```


Launch Jupyter Lab or Notebook:

jupyter lab

or
    
    jupyter notebook

    Open and run the notebooks to explore various PySpark operations.

Requirements

    Python 3.x
    PySpark
    Jupyter Lab or Jupyter Notebook

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Thanks to the Apache Spark community for their excellent documentation and resources.
