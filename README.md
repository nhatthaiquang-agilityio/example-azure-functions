# example-azure-functions
Create an Azure Functions example and deploy with package zip via Azure DevOps
- Create manual Azure Functions in Azure Portal
- Deploy package zip via Azure DevOps

# Create Azure DevOps
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