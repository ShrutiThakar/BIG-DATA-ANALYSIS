# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHRUTI ASHOK THAKAR

*INTERN ID*: CT08DF1127

*DOMAIN*: DATA ANALYSIS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: This code executed on Google Colab demonstrates how to use PySpark for large-scale data processing and analysis. It begins by installing the PySpark library and importing essential modules such as SparkSession, pandas, numpy, and utility tools like shutil and FileLink. A Spark session is initialized with the application name "BigDataProcessing", which sets up the environment for distributed computing. Using Pandas and NumPy, a synthetic dataset of one million employee records is generated, containing columns such as id, age, salary, and department, and saved as a CSV file named synthetic_data.csv. This dataset is then loaded into a PySpark DataFrame with schema inference enabled. The code proceeds to perform various data processing tasks: filtering employees earning over 100,000, calculating average salary by department, and counting employees grouped by age ranges (in decades). The results of these operations are displayed using the show() function. To enable download, the average salary output is saved as a CSV file, compressed into a ZIP archive, and a downloadable link is generated using FileLink. Overall, the code illustrates how PySpark in Colab can be used for scalable data generation, analysis, and result sharing in a cloud-based notebook environment.
In conclusion, this code effectively demonstrates the end-to-end process of generating, processing, analyzing, and exporting a large dataset using PySpark on Google Colab. It combines the ease of Python with the scalability of Spark, allowing users to handle datasets with millions of records even in a notebook environment. By simulating a real-world HR analytics scenario, this code showcases PySpark’s potential for big data applications, such as employee analysis, reporting, and decision-making support.
