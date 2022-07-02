# Deploying 3 Tier Application to Azure App Service via Terraform

This Project deploys a web app to Azure App Service, connecting your webfiles from from github, deploys database and it's required dependencies.

## Requirements and Knowledge
* Git Account
* Azure Account
* Terraform 
* MSSQL 

## Providers

| Name | Version |
|------|---------|
| azurerm | >= 3.6.0 |


## Results

Name | Description
---- | -----------
`resource_group_name` | The resource group is a like a container or room to hold your resources. 
`Azure App Service `| Azure Paas for hosting web application, in this project We deployed Linux App service for deploying a PHP simple app
`App Service Plan`|The name of the storage account
`storage_account`| A storage account for Auditing purposes
`MSSQL Server`| Microsoft SQL Server  for the app DB
`MSSQL Database`| Microsoft SQL Database for your Webapp


## Author

Created by [Chisom Jude](https://chisomjude.net) For She Code Africa Cloud School 2022 Project <br/>
Web APP Git Url : https://github.com/ChisomJude/covidsearchcenter/tree/SCA-Project <br/>
Visit My blog for more details on this project [Deploying 3 Tier Application to Azure App Service via Terraform](https://blog.chisomjude.net)



## Useful Links

* [App Service App Using Teraform Template](https://docs.microsoft.com/en-us/azure/app-service/provision-resource-terraform)

* [Azure SQL Database documentation](https://docs.microsoft.com/en-us/azure/sql-database/)

* [Terraform AzureRM Provider Documentation](https://www.terraform.io/docs/providers/azurerm/index.html)

