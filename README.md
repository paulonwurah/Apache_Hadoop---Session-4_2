# Apache_Hadoop---Session-4_2

1.	The name node is the heart of an HDFS file system. It keeps the metadata such as directory tree of all files in the file system and tracks the cluster where the file data is present. The actual data is stored on data node as HDFS blocks. (C)

2.	When the end of the block is reached DFSInputStream closes the connection to the datanode, then finds the best datanode for the next block (C)

3.	When the client finishes reading, it calls close() method on the close stream. – D

4.	Which configuration file contains Environmental variable settings used by Hadoop?  Hadoop-env.sh(D)

5.	Which MapReduce daemon instantiates user code, and executes map and reduce tasks on a cluster running MapReduce vl (MRvl)? Task Tracker (D)

6.	Identify the function performed by the Secondary NameNode daemon on a cluster configured to run with a single NameNode. In this configuration, the Secondary NameNode performs a checkpoint operation on the files by the NameNode. (A)

7.	Hadoop administrators write a script called Topology script to determine the rack location of nodes. It triggers to know the distance of the nodes to replicate the data and Configures this script in core-site.xml (C)

8.	ResourceManager (RM) is the master that arbitrates all the available cluster resources and thus helps manage the distributed applications running on the YARN system (A)

9.	NodeManager take instructions from the ResourceManager and manage resources available on a single node. (A)

10.	How does HDFS Federation help HDFS Scale horizontally? HDFS Federation reduces the load on any single NameNode by using the multiple, independent NameNode to manage individual pars of the filesystem namespace.(E)
