# 6156-cassandra
**Challenges of setting up a scientific environment with Cassandra** 

**Gabriela Concolin Schimidt – gc2658@columbia.edu**

**COMSE6156 - Topics on Software Engineering**

This repository represents a fraction of the final project for COMSE6156.

**/apache-cassandra-2.2.6**
The directory /apache-cassandra-2.2.6 has the files each node that composes the cluster should have.
The key file is conf/cassandra.yaml, which contains the listening IP (the own node address) and the seeds (the main node)

**/scripts**
The directory /scripts contain the testing queries performed during evaluation testing

**/diagrams**
The directory /diagrams contain visual data on cluster architecture and server architecture, as described on final report.

**data modelling**
The files exceed any public repository service limit, so here are their external links.
https://www.dropbox.com/sh/mrxo5ntyzye32mz/AACWp5o0vZR4teOnTCVkEQh1a?dl=0

The file genome.tsv is the raw genome file. 
The file gen.csv is the result of mining on genome.tsv. This is the file imported to Cassandra. 

