# STEPS TAKEN IN BACKINGUP IN AZURE PORTAL
1. Login to Azure portal.![Screenshot 2023-09-13 100500](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/0b07a8df-b421-4526-8252-1e75f97f031f)

2. Go to resource and create a storage account.![Screenshot 2023-09-11 153954](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/e73335f1-64a7-4786-b1cf-77de6003a201)
3. Create a new container.![Screenshot 2023-09-11 154414](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/a9677260-5d41-42bf-9c4a-888808dcc37b)
4. Navigate to shared access token and configure the permission to what action to take on the container and the validity.![Screenshot 2023-09-13 101049](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/dc6b022f-f5dd-47e2-ba37-f906d0f0d7c0)

5. Generate  the SAS token and url.![Screenshot 2023-09-10 224002](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/0a272ac7-0fbc-48ba-b274-ea714af55855)
6. Create credential by clicking on NEW QUERY
7. In SSMS Create backup by using the url generated.![Screenshot 2023-09-11 230241](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/c15fef2d-7a0b-41ee-b3b2-f33e04ea6a4a)
8. Confirm the backup in Azure container.
9. After backing up the data, DELETE the database so as to RESTORE the database.![Screenshot 2023-09-12 092304](https://github.com/adeshiyanife/new_undp_internshipprogram_2023/assets/139870552/e4e3f4b4-3789-4883-bec0-3803766bed78)

10. To restore, use the generated url too.
