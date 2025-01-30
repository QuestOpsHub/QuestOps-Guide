# 🌟 𝑾𝒆𝒍𝒄𝒐𝒎𝒆 𝒕𝒐 𝑸𝒖𝒆𝒔𝒕𝑶𝒑𝒔𝑯𝒖𝒃-𝑮𝒖𝒊𝒅𝒆!

This repository serves as the central hub for navigating and utilizing the QuestOpsHub ecosystem. Here, you'll find essential documentation, best practices, and step-by-step guides to explore, contribute to, and integrate with various QuestOpsHub Projects & Repositories.

# ⚙️ 𝑷𝒓𝒐𝒋𝒆𝒄𝒕𝒔 𝑺𝒕𝒂𝒕𝒖𝒔 𝑶𝒗𝒆𝒓𝒗𝒊𝒆𝒘

> **Legend:** ✅ Active | 🚧 In Progress | 🔍 Planning

|                                          🔹 **Project**                                           |                                                                                                                                                📜 **Description**                                                                                                                                                |                                            🛠️ **Tools & Languages**                                             | 🚀 **Status** |
|:-------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------:|:-------------:|
|  [self-hosted-github-runners-aks](https://github.com/QuestOpsHub/self-hosted-github-runners-aks)  |                                                       This repository enables the deployment and management of self-hosted GitHub runners on Azure Kubernetes Service (AKS), offering a scalable, private, and customizable solution for CI/CD workflows.                                                        |                  **Cloud**: Azure, **Containerization**: Kubernetes, **CI/CD**: GitHub Actions                  |      ✅       |
| [azure-hubspoke-network-topology](https://github.com/QuestOpsHub/azure-hubspoke-network-topology) |                                                                            Implementation and documentation of a hub-and-spoke network topology in Azure, including VNet peering, secured traffic flow, and on-premises connectivity.                                                                            |                                **Cloud**: Azure, **Networking**: Terraform, VNet                                |      🔍       |
|   [azure-webapp-ci-cd-deployment](https://github.com/QuestOpsHub/azure-webapp-ci-cd-deployment)   | This repository contains the CI/CD pipeline and deployment automation for Azure Web Apps, including integration with Azure Key Vault, Azure Container Registry (ACR), and Managed Identity. It supports deploying ASP.NET Core, Java, Python, and other applications to Azure Web Apps securely and efficiently. | **Cloud**: Azure, **CI/CD**: GitHub Actions, **Security**: Key Vault, ACR, **Languages**: ASP.NET, Java, Python |      🔍       |


# 🌐 𝑨𝒛𝒖𝒓𝒆 𝑻𝒆𝒓𝒓𝒂𝒇𝒐𝒓𝒎 𝑴𝒐𝒅𝒖𝒍𝒆𝒔

> **Legend:** ✅ Active | 🚧 In Progress | 🔍 Planning

## Table of Contents

|            **Category**            |                                                   **Repository**                                                    |                                          **Description**                                          | **Status** |
|:----------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|:----------:|
|            **Compute**             |           [terraform-azurerm-linux-webapp](https://github.com/QuestOpsHub/terraform-azurerm-linux-webapp)           |   Terraform module to create a Linux Web App along with a deployment slot and management lock.    |     ✅     |
| **Identity and Access Management** |        [terraform-azurerm-role-assignment](https://github.com/QuestOpsHub/terraform-azurerm-role-assignment)        |         Terraform module to assign a specified Role to a given Principal (User or Group).         |     ✅     |
| **Identity and Access Management** | [terraform-azurerm-user-assigned-identity](https://github.com/QuestOpsHub/terraform-azurerm-user-assigned-identity) |                   Terraform module to create a User Assigned Managed Identity.                    |     ✅     |
|           **Containers**           |     [terraform-azurerm-kubernetes-cluster](https://github.com/QuestOpsHub/terraform-azurerm-kubernetes-cluster)     |                     Terraform module to create a Managed Kubernetes Cluster.                      |     ✅     |
|           **Containers**           |           [terraform-kubernetes-namespace](https://github.com/QuestOpsHub/terraform-kubernetes-namespace)           |                         Terraform module to create Kubernetes Namespace.                          |     ✅     |
|           **Containers**           |                   [terraform-helm-release](https://github.com/QuestOpsHub/terraform-helm-release)                   |               A Release is an instance of a chart running in a Kubernetes cluster.                |     ✅     |
|           **Containers**           |     [terraform-azurerm-container-registry](https://github.com/QuestOpsHub/terraform-azurerm-container-registry)     |                         Terraform module to create a Container Registry.                          |     ✅     |
|           **Networking**           |        [terraform-azurerm-virtual-network](https://github.com/QuestOpsHub/terraform-azurerm-virtual-network)        |                     Terraform module to create a Virtual Network and Subnets.                     |     ✅     |
|            **Security**            |              [terraform-azurerm-key-vault](https://github.com/QuestOpsHub/terraform-azurerm-key-vault)              |                              Terraform module to create a Key Vault.                              |     ✅     |
|   **Management and Governance**    |         [terraform-azurerm-resource-group](https://github.com/QuestOpsHub/terraform-azurerm-resource-group)         |                        Terraform module to create an Azure Resource Group.                        |     ✅     |
|         **Miscellaneous**          |          [terraform-azurerm-random-string](https://github.com/QuestOpsHub/terraform-azurerm-random-string)          | Terraform module to generate secure random alphanumeric strings with optional special characters. |     ✅     |

---
# 🤝 𝑯𝒐𝒘 𝒕𝒐 𝑪𝒐𝒏𝒕𝒓𝒊𝒃𝒖𝒕𝒆

Thank you for your interest in contributing! Follow these steps to get started:

### 📝 𝑪𝒐𝒏𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏 𝑺𝒕𝒆𝒑𝒔

1. **Fork the Repository**: Create a fork of this project to your GitHub account.
2. **Clone the Repository**: Clone your fork to your local machine.
3. **Create a Branch**: Create a new branch for your changes.
4. **Make Changes**: Implement your changes or fixes while following project guidelines.
5. **Submit a Pull Request**: Push your changes and open a **Pull Request (PR)** with a clear description.

### ✅ 𝑪𝒐𝒏𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏 𝑮𝒖𝒊𝒅𝒆𝒍𝒊𝒏𝒆𝒔

- Ensure your code follows the project's **style and best practices**.
- Write **clear commit messages** that describe your changes.
- Before submitting a PR, check for **existing issues** to avoid duplication.
- Be respectful and collaborative in discussions.

### 📢 𝑵𝒆𝒆𝒅 𝑯𝒆𝒍𝒑?

If you have any questions, feel free to open an issue or start a discussion. We're happy to help! 😊