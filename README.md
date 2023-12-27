# Hadoop
1. Hive, Oozy, Sqoop are installed on the top of hadoop.
2. Hadoop usually has two components: HDFS & Map Reduce.

#### FAQ

Q1. What is a file system?
- used to read, write from and to Hard disk Ex NTFS, EXT, HDFS, S3 ....
- It is nothing but a layer.
- NTFS - New Technology file system (windows), EXT - EXTENSIBLE file system (Linux), Mac FS (Macbook)

Q2. What is block ? 
- Big files into smal chunk.
- Block size: 16kb (NTFS), 512kb (Linux), 128MB default (HDFS) -- 3 replicas or we can say 2copies & 1 actual 

Q3. Client (send request) & server (recive request).

Q4. Types of file system ?
- Standalone FS - NTFS, EXT (data gets stored in a single block)
- Distributed FS - HDFS, S3 (data gets stored in a multiple block)
- to install any distributed file system, you need some standalone FS before on the top of that only we can install Distributd FS.

Q5. Types of Distributed systems ? 
- Master-Slave: Master will communicate with slave and vice-versa. There is no communication between the salves. Ex: Hadoop, Spark
  Cons: Single point of communication/ Failure. We never connect directly to slave node. We usually use Edge node to connect to slave node.
- Peer-to-Peer: There is no M-S concept. Every node communicates with each other. Ex: Cassandra

Q6. Daemon Process - Background Process.unique name for every daemon process.

Q7. Cluster & Node ? 
- Node: Individual Physical or Virtual machine.
- Cluster Node:  Group of node is a cluster.

Q8. HDFS (Hadoop Distributed File Systems) 
- Suitable to use on top of Linux. 
