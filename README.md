# databases #
# Mysql-MariaDB-PostgreSQL-Cassandra-MongoDB #
mysql> use classicmodels;
mysql> show tables;
+-------------------------+
| Tables_in_classicmodels |
+-------------------------+
| customers               |
| employees               |
| offices                 |
| orderdetails            |
| orders                  |
| payments                |
| productlines            |
| products                |
+-------------------------+
8 rows in set (0.00 sec)
mysql> select count(*) from offices;
+----------+
| count(*) |
+----------+
|        7 |
+----------+
1 row in set (0.00 sec)
