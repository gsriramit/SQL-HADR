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

