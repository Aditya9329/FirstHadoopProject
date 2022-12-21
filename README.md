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
COPY TO HDFS TO LOCAL FS
```bash
hadoop fs -copyToLocal /hadoop-user/trees.csv ./
```

Delete the directory in hadoop
```bash
hadoop fs -rm -r /test
```
To load data from local file system to Hive then command is
```bash
load data local inpath 'filepath' into table table_name;
```
To load data from HDFS to hive the command is
```bash
load data inpath 'hadoop data dir_path' into table employee;
```
