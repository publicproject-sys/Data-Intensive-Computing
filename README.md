# Data-Intensive-Computing

In the following the assignments for the course "Data-Intesive Computing" at TU Vienna SS23 are given. [Course website](https://tiss.tuwien.ac.at/course/courseDetails.xhtml?courseNr=194048&semester=2023S&dswid=2209&dsrid=82) 

We have successfully completed a series of assignments focused on advanced data processing and machine learning techniques.

In *Exercise 1*, we implemented a MapReduce pipeline to process large text corpora, specifically focusing on calculating chi-square values for unigrams in Amazon reviews. This allowed us to identify the most discriminative terms per product category. The project culminated in a ranked list of terms and a comprehensive dictionary, with an emphasis on efficiency and correctness in handling large datasets.

For *Exercise 2*, we extended our text processing capabilities by utilizing Apache Spark. We reimplemented the chi-square term selection using RDDs and built a TF-IDF transformation pipeline using Spark DataFrames/Datasets. Additionally, we trained a Support Vector Machine (SVM) classifier to predict product categories from review texts. Our results were compared with the MapReduce implementation, and we successfully demonstrated the advantages of using Spark for large-scale text processing and classification.

In *Exercise 3*, we developed an object detection application using Docker, Python, and TensorFlow, which was successfully deployed both locally and on AWS. We analyzed the application's inference times in both environments, evaluating the benefits of offloading computation to the cloud. The project provided valuable insights into cloud-based processing and the practicalities of deploying machine learning applications at scale.
