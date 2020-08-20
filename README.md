# DBSCAN-on-Spark
Small Example demonstrating how we can use DBSCAN with a groupby in a distributed manner across multiple worker nodes, using Pandas UDF in Spark. Pandas UDF was introduced in Spark 2.3 and was a drastic step for improvement from older Spark version. They showed promising results and can solve a lot of 
problems that are not easy to solve in Native Spark. In this example, we look at how we can use the scikit-learn DBSCAN implementation to scale the algorithm for big data if we plan to use it with a groupBy(which is most often a valid use-case).
