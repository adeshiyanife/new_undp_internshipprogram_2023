# STEPS TAKEN IN BACKINGUP IN AZURE PORTAL
1. Login to Azure portal
2. Go to resource and create a storage account.
3. Create a new container.
4. Navigate to shared access token and configure the permission to what action to take on the container and the validity.
5. Generate  the SAS token and url.
6. Create credential by clicking on NEW QUERY
7. In SSMS Create backup by using the url generated
8. Confirm the backup in Azure container.
9. After backing up the data, DELETE the database so as to RESTORE the database.
10. To restore, use the generated url too.
