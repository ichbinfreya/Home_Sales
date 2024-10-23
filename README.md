# PySpark Home Sales Analysis

This project uses PySpark to analyze a dataset of home sales. The analysis involves calculating average prices for homes based on different attributes such as the number of bedrooms, bathrooms, floors, and view ratings.

# Dataset

The dataset is accessed from an AWS S3 bucket and loaded into a Spark DataFrame. It contains information about home sales such as the year built, price, number of bedrooms, bathrooms, and view ratings.

## Tasks

The following analyses are performed:
1. Average price of four-bedroom houses sold per year.
2. Average price of homes with three bedrooms and three bathrooms per year.
3. Average price of homes with three bedrooms, three bathrooms, two floors, and a minimum of 2,000 square feet per year.
4. Average price per "view" rating for homes priced above $350,000, along with runtime comparison between cached and uncached data.
5. Partitioning the dataset by the date_built field and querying the parquet data.

## Technologies Used
- PySpark: For distributed data processing.
- Google Colab: For running the code with cloud-based resources.


### Switch from Jupyter to Google Colab

The project was initially developed in Jupyter Notebook, but performance issues and environment setup complexity led to switching to Google Colab. Colab provides:
- Free cloud resources, which handle large datasets and computationally intensive tasks more efficiently.
- Pre-configured environments that simplify the installation and use of PySpark, avoiding local configuration issues.
-----------------------------------------------------------------------------------------------------------------------------------------------------

### Instructions to Run
1. Clone the project or open the notebook in Google Colab.
2. Run each cell sequentially to perform the analyses.
3. Ensure that the dataset is accessible from the specified S3 link or download it locally before running the notebook.
