## MIGRATION OF SQL SERVER TO AZURE SQL DB 
create a target instance of Azure SQL Database on Azure portal
<img width="913" alt="Screenshot 2024-05-01 130937" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/c731082f-7931-4f2c-a4d6-14b98974c6da">

Fill necessary info like subscription, Resource group,dabase name, server, add current Ip address, tag.
Once done, copy the second Ip address of the souce server to Azure Data studio or SSMS. Make sure that the SQL Server login that 
connects to the source SQL Server instance is a member of the db_datareader role and that the login for the target SQL Server instance is a member of the db_owner role.
Then connect to the server 
To migrate the database schema from source to target Azure SQL DB by using the Database Migration Service or SSMS.
On SSMS, select the on-premises of the SQL service you want to migrate
