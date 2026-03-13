# tf-module-rds

This is the backend module for expense-terraform.

> All the code needed to create RDS (MySQL) will be hosted here.

## Relational Databse Service (RDS)
RDS Relational DB Service PaaS offering from AWS for sequel workload
Databses supported by RDS (Always refer docs) -
    - SQL DB
    - MYSQL DB
    - Maria DB
    - Aurora MySQL DB - EC2 linux
    - Aurora Postgress
    - Postgress
    - IBM DB2
    - Oracle

 famous DB replication software comes with huge cost.
 stateless workloads (Non-Data) on cloud
 DB related work on On-Premise

 # RDS
 1. you can create the cluster either in instance mode or cluster Mode
 2. In training, will go with instance mode.
 3. In corporate Cluster mode DB will be setup.
 4. In Cluster mode there will be 1 write DB alongwith 2 read only DB.
 5. In cluster mode, Cost also increases as per DB.
 6. In Instance mode there will be main DB & replica DB, so continuously Main DB will be writing if in case of failover replica DB will take the workload.
 7. In instance mode, main DB & replica DB will be in different zones.