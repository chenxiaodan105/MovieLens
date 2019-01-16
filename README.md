# MovieLens
#### 1. Goal
movie recommendation using 1 million ratings from 6000 users on 4000 movies.

#### 2. Data Source
Released by GroupLens in 2003 

Link: https://grouplens.org/datasets/movielens/1m/
Explaination: http://files.grouplens.org/datasets/movielens/ml-1m-README.txt

#### 3. Tools
AWS EC2(4 instances to simulate 4 nodes: 1 Namenode,1 SecondaryNameNode, 2 Datanodes),
AWS EMR, Hadoop, Spark

#### 4. Methods
There are 2 stages:
a. Conduct exploratory data analysis to figure out the distribution of ratings, users, movies using pyspark shell
b. Conduct movie recommendation for specific users  

#### 5. Impact
Compare advantages and disadvantages of different methods for big data project between AWS EMR, and multiple AWS EC2 instances. 

#### 6. Improvemnet
Try Apache Ambari later and rewrite the project in scala
