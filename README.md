# MovieLens
1. Goal
movie recommendation using 1 million ratings from 6000 users on 4000 movies.

2. Data Source
Released by GroupLens in 2003 
Link: https://grouplens.org/datasets/movielens/1m/

3. Tools
AWS EC2(4 instances to simulate 4 nodes: 1 Namenode,1 SecondaryNode, 2 Datanodes)
AWS EMR, Hadoop, Spark, Ambari

4. Methods
There are 2 stages:
a. Conduct exploratory data analysis to figure out the distribution of ratings, users, movies using pyspark shell
b. Calculate movie similarities and conduct movie recommendation for specific users 

5. Impact
Compare advantages and disadvantages of methods for big data project among Ambari developed by Hortonworks, 
AWS EMR, multiple AWS EC2 instances. 
