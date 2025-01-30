Welcome to **QuestOpsHub-Guide**! 🚀 This repository serves as the central hub for navigating and utilizing the QuestOpsHub ecosystem. Here, you'll find essential documentation, best practices, and step-by-step guides to explore, contribute to, and integrate with various QuestOpsHub Projects & Repositories.

# ⚙️ Projects & Status

> **Legend:** ✅ Active | 🚧 In Progress | 🔍 Planning

| 🔹 **Project**                                                                                    | 📜 **Description**                                                                                                                                                                                                                                                                                              | 🚀 **Status** |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| [self-hosted-github-runners-aks](https://github.com/QuestOpsHub/self-hosted-github-runners-aks)   | This repository enables the deployment and management of self-hosted GitHub runners on Azure Kubernetes Service (AKS), offering a scalable, private, and customizable solution for CI/CD workflows.                                                                                                             | ✅ Active     |
| [azure-hubspoke-network-topology](https://github.com/QuestOpsHub/azure-hubspoke-network-topology) | Implementation and documentation of a hub-and-spoke network topology in Azure, including VNet peering, secured traffic flow, and on-premises connectivity.                                                                                                                                                      | 🔍 Planning   |
| [azure-webapp-ci-cd-deployment](https://github.com/QuestOpsHub/azure-webapp-ci-cd-deployment)     | This repository contains the CI/CD pipeline and deployment automation for Azure Web Apps, including integration with Azure Key Vault, Azure Container Registry (ACR), and Managed Identity. It supports deploying ASP.NET Core, Java, Python and other applications to Azure Web Apps securely and efficiently. | 🔍 Planning   |
|                                                                                                   |                                                                                                                                                                                                                                                                                                                 |               |

# 🛠️ Terraform Modules for Azure

> **Legend:** ✅ Active | 🚧 In Progress | 🔍 Planning

## Table of Contents

| **Category**                       | **Resource Type**                    | **Repository**                                                                                                      | **Description**                                                                                   | **Status** |
| ---------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------- |
| **Compute**                        | **App Service (Web App)**            | [terraform-azurerm-linux-webapp](https://github.com/QuestOpsHub/terraform-azurerm-linux-webapp)                     | Terraform module to create a Linux Web App along with a deployment slot and management lock.      | ✅ Active  |
| **Identity and Access Management** | **Role-Based Access Control (RBAC)** | [terraform-azurerm-role-assignment](https://github.com/QuestOpsHub/terraform-azurerm-role-assignment)               | Terraform module to assign a specified Role to a given Principal (User or Group).                 | ✅ Active  |
| **Identity and Access Management** | **Managed Identity**                 | [terraform-azurerm-user-assigned-identity](https://github.com/QuestOpsHub/terraform-azurerm-user-assigned-identity) | Terraform module to create a User Assigned Managed Identity.                                      | ✅ Active  |
| **Containers**                     | **Azure Kubernetes Service (AKS)**   | [terraform-azurerm-kubernetes-cluster](https://github.com/QuestOpsHub/terraform-azurerm-kubernetes-cluster)         | Terraform module to create a Managed Kubernetes Cluster.                                          | ✅ Active  |
| **Containers**                     | **Kubernetes Namespace**             | [terraform-kubernetes-namespace](https://github.com/QuestOpsHub/terraform-kubernetes-namespace)                     | Terraform module to create Kubernetes Namespace.                                                  | ✅ Active  |
| **Containers**                     | **Helm Release**                     | [terraform-helm-release](https://github.com/QuestOpsHub/terraform-helm-release)                                     | A Release is an instance of a chart running in a Kubernetes cluster.                              | ✅ Active  |
| **Containers**                     | **Container Registry (ACR)**         | [terraform-azurerm-container-registry](https://github.com/QuestOpsHub/terraform-azurerm-container-registry)         | Terraform module to create a Container Registry.                                                  | ✅ Active  |
| **Networking**                     | **Virtual Network (VNET)**           | [terraform-azurerm-virtual-network](https://github.com/QuestOpsHub/terraform-azurerm-virtual-network)               | Terraform module to create a Virtual Network and Subnets.                                         | ✅ Active  |
| **Security**                       | **Key Vault**                        | [terraform-azurerm-key-vault](https://github.com/QuestOpsHub/terraform-azurerm-key-vault)                           | Terraform module to create a Key Vault.                                                           | ✅ Active  |
| **Management and Governance**      | **Resource Group**                   | [terraform-azurerm-resource-group](https://github.com/QuestOpsHub/terraform-azurerm-resource-group)                 | Terraform module to create an Azure Resource Group.                                               | ✅ Active  |
| **Miscellaneous**                  | **Random String**                    | [terraform-azurerm-random-string](https://github.com/QuestOpsHub/terraform-azurerm-random-string)                   | Terraform module to generate secure random alphanumeric strings with optional special characters. | ✅ Active  |

---
# 🤝 How to Contribute

Thank you for your interest in contributing! 🚀 Follow these steps to get started:

### 📝 Contribution Steps

1. **Fork the Repository**: Create a fork of this project to your GitHub account.
2. **Clone the Repository**: Clone your fork to your local machine.
3. **Create a Branch**: Create a new branch for your changes.
4. **Make Changes**: Implement your changes or fixes while following project guidelines.
5. **Submit a Pull Request**: Push your changes and open a **Pull Request (PR)** with a clear description.

### ✅ Contribution Guidelines

- Ensure your code follows the project's **style and best practices**.
- Write **clear commit messages** that describe your changes.
- Before submitting a PR, check for **existing issues** to avoid duplication.
- Be respectful and collaborative in discussions.

### 📢 Need Help?

If you have any questions, feel free to open an issue or start a discussion. We're happy to help! 😊