# Prerequisites

**Deployment Instructions**

To deploy Enterprise RAG and get your solution up and running, you will use azd, Python, Git, Node.js, and PowerShell (only if you are using Windows).

### 🛠 Tools Pre-reqs links:

-  Azure CLI Installed & Configured `az` - [Get help here](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Azure Developer CLI `azd` : [Download azd for Windows](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/install-azd), Other OS's.
- Powershell (Windows only): [Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-window)
- `git`: [Download Git](https://git-scm.com/downloads)
- Node.js: [ windows/mac](https://nodejs.org/en/download/) / [linux/wsl](https://nodejs.org/en/download/package-manager/)
- `Python`: [Download Python](https://www.python.org/downloads/)
- Jupyter Notebook: [Download Jupyter](https://jupyter.org/install)
- `jq` - [Get help here](https://stedolan.github.io/jq/download/)
- `bash` or git bash (for windows only) - [Get help here](https://git-scm.com/downloads)
- Azure Bicep - [Download Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install)
- Visual Studio Code: [Download VS Code](https://code.visualstudio.com/download) & following VS Code extensions:

    - [Azure Account](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account)
    - [Azure Bicep](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep)
    - [Azure CLI Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli)
    - [Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions)
    - [MSFT Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter), Jupyter Cell Tags 
    - [MSFT Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
    - [Red Hat YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
    - GitHub Copilot / [MSFT IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
    - [Prettier Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Check your access
After installing the pre-requirements you just need to execute the next four steps using - Azure CLI (az) in a terminal:

```bash
jq --version
func --version
bicep --version
bash --version
az account show
```