# Deploying 3 Tier Application to Azure App Service via Terraform

This Project deploys a web app to Azure App Service, connecting your webfiles from from github, deploys database and it's required dependencies.

## Providers

| Name | Version |
|------|---------|
| azurerm | >= 3.6.0 |


## Requirements and Knowledge
* Git Account
* Azure Account
* Terraform 
* MSSQL 

## Usage

> If you have teraform installed, and an [Azure account](https://azure.microsoft.com/en-us/free/) and [Azure CLI install](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

> Open your bash terminal, make a new directory 
```
mkdir <foldername>
```

> Clone this project 
```
git clone  https://github.com/ChisomJude/IAC-Project4SCA.git
```

> Run the script below
```
terraform Init
terraform plan #optional
terraform apply
```

> Login to Azure and confirm all infrastructures are deployed 


## Expected Results

Name | Description
---- | -----------
`resource_group_name` | The resource group is a like a container or room to hold your resources. 
`Azure App Service `| Azure PAAS for hosting web application, in this project We deployed Linux App service for deploying a PHP simple app, Azure will project your project url. For this project I have - https://mywebapp4sca.azurewebsites.net/ (PS:For Cost purposes, this will be deleted after a while)
`App Service Plan`|The name of the app service plan, for this project - Linux B1
`storage_account`| A storage account for Auditing purposes
`MSSQL Server`| Microsoft SQL Server  for the app DB
`MSSQL Database`| Microsoft SQL Database for your Webapp


## Author

Created by [Chisom Jude](https://chisomjude.net) For She Code Africa Cloud School 2022 Project <br/>
Web APP Git Url : https://github.com/ChisomJude/covidsearchcenter/tree/SCA-Project <br/>
Visit My blog for more details on this project [Deploying 3 Tier Application to Azure App Service via Terraform](https://blog.chisomjude.net)

<br/>

If this was helpful, remember to star :star: this project. Thank you :thumbsup:  <br/>
Feel free to [reach me](mailto:hello@chisomjude.net) if your have further concerns 

<br/>

## Useful Links

* [App Service App Using Teraform Template](https://docs.microsoft.com/en-us/azure/app-service/provision-resource-terraform)

* [Azure SQL Database documentation](https://docs.microsoft.com/en-us/azure/sql-database/)

* [Terraform AzureRM Provider Documentation](https://www.terraform.io/docs/providers/azurerm/index.html)

