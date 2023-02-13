# Time Processing Comparison of ETL process using pandas and Spark

#### Extraction, Transforming and Load of two datasets, one with 156Kb (small) and other with 627Mb (big)
###### The times of processing for each step was saved in a dictionary and after that, it was possible to create bar graphics to compare the times.

To run it's only run the cells of the notebooks `pandas_treatment.ipynb` and `pyspark_treatment.ipynb`
* Note: To load the final data with Spark script, it's necessary to run the notebook in a cluster, so it's was used the Databricks for it.