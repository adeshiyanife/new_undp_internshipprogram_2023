# STEPS IN ACHIEVING THE ASSESSMENT
#### Set up the SSMS and download Data migration instance.  
##### Download the two database instance. Do that by clicking on the first link 
#### I depolyed an instance of (https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0) and https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
1. Go to SSMS, connect and restore the database by right clicking on the **DATABASE* to restore the database.![Screenshot 2023-09-05 220015](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/776dd25d-7ca0-429e-8a03-34a456c95e1a)
 
4. Click on Device, locate the device, click add,copy the link and go to file explorer and paste(This pc).
5. ![Screenshot 2023-09-05 220303](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/5ab5a613-16c7-4227-a20c-4bc4ffb5493c)

6. Copy the backup file;(Adventurework)
7. To continue in restoring the database,refresh and click ok. It will show restore successful.
8. click on the Adventurework database
9. Go to Data migration instance, click on the + icon to perform the assessement.
10. ![Screenshot 2023-09-05 222534](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/84d665db-c9c3-4e7d-a30a-1b34ccd847ca)

11. Give the project a name e.g Adventurework_DB,check and choose the target server type(Azure SQL database) and click create.
12. ![Screenshot 2023-09-05 222817](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/a0c89ed6-d5bf-4878-8925-97ba62e3cfaf)

13. Connect to a server by pasting the server name copied frm SSMS and connect.
14. ![Screenshot 2023-09-05 223012](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/b47d7517-4386-4f88-98a6-2c0541478819)

15. Click on the database been worked on(Adventurework) on the server. Click add, start the assessment and save.
16. ![Screenshot 2023-09-05 223047](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/1ae59746-7c4d-41cf-98f5-461d6191dada)

17. Test against Azure SQL managed instance, the Azure VM.
