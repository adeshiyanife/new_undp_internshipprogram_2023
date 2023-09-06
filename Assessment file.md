# STEPS IN ACHIEVING THE ASSESSMENT
#### Set up the SSMS and download Data migration instance.  
##### Download the two database instance. Do that by clicking on the first link 
#### I depolyed an instance of (https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0) and https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
1. Go to SSMS, connect and restore the database by right clicking on the **DATABASE* to restore the database.![Screenshot 2023-09-05 220015](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/776dd25d-7ca0-429e-8a03-34a456c95e1a)
 
4. Click on Device, locate the device, click add,copy the link and go to file explorer and paste(This pc)
5. Copy the backup file;(Adventurework)
6. To continue in restoring the database,refresh and click ok. It will show restore successful.
7. click on the Adventurework database
8. Go to Data migration instance, click on the + icon to perform the assessement.

9. Give the project a name e.g Adventurework_DB,check and choose the target server type(Azure SQL database) and click create.
10. Connect to a server by pasting the server name copied frm SSMS and connect.
11. Click on the database been worked on(Adventurework) on the sewrver. Click add, start the assessment and save.
12. Test against Azure SQL managed instance, the Azure VM.
