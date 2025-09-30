# 🚀 MCP DevContainer for Azure DevOps

[![Made with VS Code](https://img.shields.io/badge/Made%20with-VS%20Code-1f425f.svg)](https://code.visualstudio.com/)
[![Azure DevOps](https://img.shields.io/badge/Azure-DevOps-0078D7?logo=azure-devops)](https://azure.microsoft.com/en-us/services/devops/)
[![Docker](https://img.shields.io/badge/Powered%20by-Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

A ready-to-use **Dev Container** setup for running the [Azure DevOps MCP server](https://github.com/microsoft/azure-devops-mcp) locally.  
This container lets you connect **GitHub Copilot (Chat)** with your Azure DevOps organization — so you can **query projects, work items, pipelines and more directly from VS Code**.

---

## ✨ Features

- ⚡ **Node.js 24** base image  
- 🛠️ **Azure CLI** preinstalled for `az login`  
- 🤖 **Azure DevOps MCP server** wired up via `.vscode/mcp.json`  
- 💡 **GitHub Copilot & Copilot Chat** extensions preinstalled  
- 🔑 **Environment variable support** via `.env` (ignored by git)

---

## ✅ Prerequisites

Before you start, make sure you have:

1. **Docker Desktop** installed and running  
   → [Download Docker](https://www.docker.com/products/docker-desktop)  
2. **Visual Studio Code** installed  
   → [Download VS Code](https://code.visualstudio.com/)  
3. VS Code extension **Dev Containers** (`ms-vscode-remote.remote-containers`)  
4. VS Code extension **Azure Resources** (`ms-azuretools.vscode-azureresourcegroups`)  

---

## 🚀 Getting Started

### 1️⃣ Clone this repository
```bash
git clone https://github.com/bahto/mcp-devcontainer.git
cd mcp-devcontainer
