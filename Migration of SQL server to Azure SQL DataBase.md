## MIGRATION OF SQL SERVER TO AZURE SQL DB 
1. create a target instance of Azure SQL Database on Azure portal
<img width="913" alt="Screenshot 2024-05-01 130937" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/c731082f-7931-4f2c-a4d6-14b98974c6da">

2. Fill necessary info like subscription, Resource group,dabase name, server, add current Ip address, tag.
3. Once done, copy the second Ip address of the souce server to Azure Data studio or SSMS. Make sure that the SQL Server login that <img width="848" alt="Screenshot 2024-05-01 153244" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/66b15662-9242-4463-9311-fc4d23df86fa">

4. connects to the source SQL Server instance is a member of the datareader role and that the login for the target SQL Server instance is a member of the db_owner role.<img width="931" alt="Screenshot 2024-05-01 210659" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/5c1d6620-531f-4620-b181-593a266296df">

5. Then connect to the server 
6. To migrate the database schema from source to target Azure SQL DB by using the Database Migration Service or SSMS.<img width="810" alt="Screenshot 2024-05-01 125125" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/1ebe548f-e419-4ff6-9a04-7ef205c8e22d">

7. On SSMS, select the on-premises of the SQL service you want to migrate<img width="810" alt="Screenshot 2024-05-01 125125" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/7536554f-4984-4df7-b916-250bef97ddb4">
8. Click on Tasks, dploy database to Azure SQL Databse<img width="960" alt="Screenshot 2024-05-01 125253" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/7b660a37-a707-4b33-8097-32b750001f31">
9. The deployement interface will show deployment settings where it will connect to the server.<img width="953" alt="Screenshot 2024-05-01 125425" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/772de7b4-e2ed-4841-9264-6196e429c479">
10. The overview of the deployment settings will be shown.<img width="956" alt="Screenshot 2024-05-01 125451" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/1757d674-a277-4009-8405-98a2d2376628">
11. Then click on Finish <img width="957" alt="Screenshot 2024-05-01 125519" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/5eee471c-39a5-4f8a-8fc3-89c350336844">
12. The result will show successful.<img width="957" alt="Screenshot 2024-05-01 130333" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/623e5e41-bc4e-4e27-b0b9-e14074700e19">
13. Connect to the target SQL Server instance, there you will see the migrated server <img width="951" alt="Screenshot 2024-05-01 213745" src="https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/62612681-4ed1-486e-a1e8-afc7d9e7b360">


