Spark-submit options:
--class RandomForest

Example:

Application location:
s3://randomforestbuccket/randomforest_2.11-0.1.jar

Argumants:
s3://randomforestbuccket/mushrooms.csv
s3://randomforestbuccket/mushroomModel
s3://randomforestbuccket/mushroomConfusion

Note:
The following arguments must be provided to the program in the specified order- 
1) The input mushroom.csv file
2) The s3 bucket file path for mushroomModel
3) The s3 bucket file path for mushroomConfusion.


The zip file contains the folloqing files:

1)build.sbt
2)project
3)spark-warehouse
4)src
5)target
6)mushrrom.csv
7)readme.txt
8)awscli.txt
9)target/scala-2.11/randomforest_2.11-0.1.jar

