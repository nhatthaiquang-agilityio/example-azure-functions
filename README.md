# Example Azure Functions
## Create an Azure Function example and deploy with package zip via Azure DevOps
- Create manual Azure Functions in Azure Portal
- Deploy package zip via Azure DevOps

## Create Azure Functions and setup infrastructure with Terraform via Azure DevOps
- Create manual Resource Group, Storage Name and Container Name
- Setup Infrastructure Azure Function with Terraform
- Deploy package zip

## Create Azure DevOps
- Create an account in Azure DevOps
- Create Parallel Jobs for building and deployment app (Microsoft-Hosted)
- Link GitHub repo with Azure DevOps (GitHub Connections)
- Create a Service Connection between Azure DevOps and Azure Portal for Deployment
![Service Connection](./images/Service-Connection.png)

### Create Azure Pipeline and deploy with zip package
+ ![Run Pipeline](./Images/Pipeline.png)

### Check Azure Function in Azure Portal
+ Home Page with Environment setting (AzureWebJobsDisableHomepage=false)
![Home Page Azure Function](./Images/HomePage-Azure.png)
+ Show Azure Functions
![Azure Function](./Images/Show-Functions.png)

### Test Azure Function
![Http Trigger Azure Function](./Images/Http-Trigger.png)

## Deploy Azure Function with Terraform
- Create ResourceGroup
- Create Storage Account & Container
    + Save terraform state file
- Run azure-deployment-with-terraform.yml

### Check in Azure Portal
+ Azure Deployment with Terraform
![Azure Pipeline With Terraform](./Images/Azure-Pipeline-W-Terraform.png)

+ Store terraform file
![Terraform State File](./Images/statefiles.png)

+ Azure Function Overview
![Overview](./Images/Azure-Func-Overview.png)

+ Test Azure Function

![Http Trigger Azure Function](./Images/Test-Azure-Function.png)
