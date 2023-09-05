# STEPS IN ACHIEVING THE ASSESSMENT
#### Set up the SSMS and download Data migration instance.  
##### Download the two database instance. Do that by clicking on the first link 
#### I depolyed an instance of (https://github.com/Microsoft/sql-server-samples/releases/tag/wide-world-importers-v1.0) and https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms
1. Go to SSMS, connect and restore the database by right clicking on the **DATABASE* to restore the database.
2. 
3. Click on Device, locate the device, click add,copy the link and go to file explorer and paste(This pc)
4. Copy the backup file;(Adventurework)
5. To continue in restoring the database,refresh and click ok. It will show restore successful.
6. click on the Adventurework database
7. Go to Data migration instance, click on the + icon to perform the assessement.
8. Give the project a name e.g Adventurework_DB,check and choose the target server type(Azure SQL database) and click create.
9. Connect to a server by pasting the server name copied frm SSMS and connect.
10. Click on the database been worked on(Adventurework) on the sewrver. Click add, start the assessment and save.
11. Test against Azure SQL managed instance, the Azure VM.
