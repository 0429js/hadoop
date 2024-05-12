# hadoop
sqoop import --connect jdbc:mysql://localhost/retail_db -username=root -passowrd=cloudera -table=categories -target-dir=/user/cloudera/test_import -m 1

hadoop jar /usr/lib/hadoop-mapreduce/hadoop-mapreduce-examples.jar wordcount finish/* out/

