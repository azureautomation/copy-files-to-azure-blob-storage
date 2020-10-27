Copy files to Azure Blob Storage
================================

            

 

Copy-ToAzureBlob will copy files from $path to Azure Blob. The Azure powershell module should be installed, otherwise the script will fail. You can download it from https://www.powershellgallery.com/.
Update with your information like Application ID, Tenant ID, Storage Account and Storage Key from line 56 to 66.



 






The script use Service principal to authenticate to azure. You can read more here on how to create an Azure Active Directory application and service principal that can access resources here: https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-create-service-principal-portal










![Image](https://github.com/azureautomation/copy-files-to-azure-blob-storage/raw/master/azure2.png)


![Image](https://github.com/azureautomation/copy-files-to-azure-blob-storage/raw/master/azure.png)


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
