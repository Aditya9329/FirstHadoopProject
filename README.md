# FirstHadoopProject
- In HDFS / is the root
command to check the files in root HDFS dirctory
```bash
hadoop fs -ls /
```
Command to create directory in hadoop
```bash
hadoop fs -mkdir /input_data
```
Command to copy datafrom local file system to HDFS
```bash
hadoop fs -put test_demo/trees.csv /input_data
```
