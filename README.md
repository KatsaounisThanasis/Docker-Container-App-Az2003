# 🚀 Deploy and Manage a C# Web App with Azure Container Apps

This project is based on a **Microsoft Learn guided module** where I deployed and managed a containerized .NET application using **Azure Container Apps** and **Azure DevOps Pipelines**.

> 📚 Original module:  
> [Deploy and manage a containerized application using Azure Container Apps](https://learn.microsoft.com/en-us/training/modules/deploy-manage-container-app-using-azure-container-apps/)

---

## 🧠 What I Learned

✅ How to containerize a .NET web API using Docker  
✅ Push and store container images in Azure Container Registry  
✅ Deploy to Azure Container Apps using Azure CLI and Azure DevOps  
✅ Scale applications based on HTTP traffic  
✅ Manage revisions and traffic splitting  
✅ Use managed identities to secure access to other Azure resources  

---

## 🛠 Tech Stack

- C# (.NET)
- Docker
- Azure Container Apps
- Azure Container Registry
- Azure DevOps Pipelines
- YAML (GitHub workflows)
- Managed Identity
- Azure CLI

---

## 📁 Project Structure
├── .github/workflows/ # CI/CD pipeline (Azure DevOps or GitHub Actions)

├── Properties/ # .NET project properties

├── Az2003.sln # Solution file

├── Az2003.csproj # Project file

├── Program.cs # Main application logic

├── Dockerfile # Docker image definition

├── appsettings.json # App config

├── appsettings.Development.json

├── Az2003.http # HTTP test file (for REST endpoints)

├── .gitignore

├── .dockerignore

├── README.md
