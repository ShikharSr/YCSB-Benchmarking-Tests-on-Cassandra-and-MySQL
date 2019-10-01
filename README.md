# YCSB-Benchmarking-Tests-on-Cassandra-and-MySQL
Project uses YCSB Workload A and Workload E for carrying out performance analysis on Cassandra and MySQL. YCSB provides metrics like the overall throughput of
database, its average latency along with operation counts that can be obtained for six different kinds of workloads present in YCSB as mentioned below:

1. Workload A - This workload performs 50% read and 50% write operations.
2. Workload B - Workload performs 95% read operations and 5% write operations.
3. Workload C - Performs 100% read operations.
4. Workload D - It reads latest records inserted in the database.
5. Workload E - This workload queries short ranges of records.
6. Workload F - Here records are read, modified and then modified records are inserted back to the database.

Project uses Workload A and Workload E for carrying out performance analysis on Cassandra and MySQL. Both YCSB workloads are run for four different operation
counts i.e. 25000, 50000, 100000, 200000. For each database, each workload and each operation count performance metrics like throughput, average latency w.r.t. insert, read,
update operations are measured through YCSB. The benchmark test was run 3 times for both databases and an average value of three runs was taken to get a better picture.
