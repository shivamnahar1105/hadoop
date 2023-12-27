# Hadoop
1. Hive, Oozy, Sqoop are installed on the top of hadoop.
2. Hadoop usually has two components: HDFS & Map Reduce.

#### FAQ

Q1. What is a file system?
- used to read, write from and to Hard disk Ex NTFS, EXT, HDFS, S3 ....
- NTFS - New Technology file system (windows), EXT - EXTENSIBLE file system (Linux), Mac FS (Macbook)

Q2. What is block ? 
- Big files into smal chunk.
- Block size: 16kb (NTFS), 512kb (Linux)

Q3. Client (send request) & server (recive request).

Q4. Types of file system ?
- Standalone FS - NTFS, EXT (data gets stored in a single block)
- Distributed FS - HDFS, S3 (data gets stored in a multiple block)

Q5. Types of Distributed systems ? 
- Master-Slave: Master will communicate with slave and vice-versa. There is no communication between the salves. Ex: Hadoop, Spark
  Cons: Single point of communication/ Failure. 
- Peer-to-Peer: There is no M-S concept. Every node communicates with each other. Ex: Cassandra
