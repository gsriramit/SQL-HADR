# VCore Model - Choosing Service Tiers 
https://learn.microsoft.com/en-us/azure/azure-sql/database/service-tiers-sql-database-vcore?view=azuresql


# SQL-HADR (WIP)
High Availability and Disaster Recovery mechanisms in the design of Azure SQLDB, SQL MI and SQL Server on Azure VMs

## References

### SQL On Azure VMs
#### Always On AG 
https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/availability-group-overview?view=azuresql  
** Tutorial on creating Always on AG for SQL on VMs (With architecture diagrams)**  
1. Multiple Subnets
https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/availability-group-manually-configure-tutorial-multi-subnet?view=azuresql
2. Multiple subnets configuration extended to multiple regions
https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/availability-group-manually-configure-multi-subnet-multiple-regions?view=azuresql
#### Failover Cluster Instances (FCI)
https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/failover-cluster-instance-overview?view=azuresql
#### Windows Server Failover Cluster
https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/hadr-windows-server-failover-cluster-overview?view=azuresql
#### Deployment References
1. Creating WSFC and join the SQL VMs to it
https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.sqlvirtualmachine/sql-vm-ag-setup
2. Creating the AG listener and configuring the ILB
https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.sqlvirtualmachine/sql-vm-aglistener-setup
3. Setting up Domain Controller in HA mode
https://github.com/Azure/azure-quickstart-templates/tree/master/application-workloads/active-directory/active-directory-new-domain-ha-2-dc

### Azure SQL DB
**High Availability for Azure SQLDB**
https://learn.microsoft.com/en-us/azure/azure-sql/database/high-availability-sla?view=azuresql&tabs=azure-powershell  
**Active Geo-Replication**
https://learn.microsoft.com/en-us/azure/azure-sql/database/active-geo-replication-overview?view=azuresql  
**Azure SQL HA by Service Tier**
https://www.youtube.com/watch?v=2WbRgjrpXkU

### Azure SQL Managed Instance
**High Availability of Azure SQL MI General Purpose Service Tier**
https://techcommunity.microsoft.com/t5/azure-sql-blog/high-availability-in-azure-sql-mi-general-purpose-service-tier/ba-p/3298977
**High Availability and SLA for SQL MI**
https://www.youtube.com/watch?v=gC9KSnNtSnM
**Official documentation on SQL MI HA**
https://learn.microsoft.com/en-us/azure/azure-sql/managed-instance/high-availability-sla?view=azuresql

### Azure SQL Managed Instance on Azure Arc-Enabled Kubernetes
https://learn.microsoft.com/en-us/azure/azure-arc/data/managed-instance-high-availability

# Query Performance Insights for Azure SQLDB
https://learn.microsoft.com/en-us/azure/azure-sql/database/query-performance-insight-use?view=azuresql

# Security
## Azure SQLDB

***Src***: Microsoft Virtual Event: **Securely Migrate and Optimize with Azure** (Section: Modernize apps on intelligent, secure, and fully-managed Azure databases)
![Screenshot 2023-05-14 104528](https://github.com/gsriramit/SQL-HADR/assets/13979783/998076a9-36d9-4fc6-92e2-f732d4fc4871)


