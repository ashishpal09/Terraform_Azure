1. To install Azure CLI 
    curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

2. Check Azure Version
    az --version

3. Configure Azure Account with CLI
    az login

4. Initialize the azure cli 
    az init

5. Set config to your Availability Zone and Ressource Group
    az config set defaults.location=eastus2 defaults.group=azure-learning

6. To check the list of available virtaul machine in a specefic region 
    az vm list-usage --location eastus --output table [based on usage]

    az vm list-sizes --location eastus --output table [based on size]


Documentation Links:
1. Azure CLI Configuration: https://learn.microsoft.com/en-us/cli/azure/azure-cli-configuration?view=azure-cli-latest
2. Azure CLI on Linux: https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux?view=azure-cli-latest&pivots=apt
3. Azure VM Creation with Terraform: https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-terraform
4. Create & Manage Azure VMs via Azure CLI: https://learn.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-manage-vm

