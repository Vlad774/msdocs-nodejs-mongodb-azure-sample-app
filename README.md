# Nodejs + MongoDB App Deploy To Azure App Service Classic & Yaml Pipeline 🚀
📌 Description
This project demonstrates deploying a Node.js + MongoDB app to Azure Web App for Linux using both Classic and YAML pipelines in Azure DevOps.
The CI/CD pipeline runs on a self-hosted Azure DevOps agent deployed on an AWS EC2 instance, showcasing a hybrid AWS + Azure setup. The app is built, zipped, published as an artifact, and deployed to Azure App Service.

## 🛠Technologies
- Node.js 18+, Express.js
- MongoDB / CosmosDB
- Azure DevOps (Classic + YAML)
- Azure Web App (Linux)
- Self-hosted agent on AWS EC2
  
## 🔄 CI/CD Workflow
- Code push triggers Azure Pipeline
- Self-hosted agent (on AWS) runs build & archive steps
- ZIP (cd.zip) is published as artifact
- AzureRmWebAppDeployment task deploys app to Azure
    
     
## ✨ Key Features
- ✔ Classic & YAML CI/CD pipeline examples
- ✔ Hybrid AWS (agent) + Azure (App Service) architecture
- ✔ ZIP-based deployment using Azure DevOps
- ✔ Full automation, no manual deployment
 

## Walk-through:

 ![First try](https://github.com/Vlad774/msdocs-nodejs-mongodb-azure-sample-app/blob/main/images/AWS_Instance.png) 
 ![First try](https://github.com/Vlad774/msdocs-nodejs-mongodb-azure-sample-app/blob/main/images/deploy.png) 
 ![First try](https://github.com/Vlad774/msdocs-nodejs-mongodb-azure-sample-app/blob/main/images/logs.png)
 ![First try](https://github.com/Vlad774/msdocs-nodejs-mongodb-azure-sample-app/blob/main/images/service_running.png)

