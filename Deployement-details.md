# Create a new Resource Group Exists
Create a resource group `rg-eastus-001` using the following command:

```bash
az group create --name rg-eastus-001 --location "East US 2"
``` 
# Deploying Azure Resources via CLI
```bash
az deployment group create \
  --resource-group rg-eastus-001 \
  --template-file azuredeploy.json \
  --parameters @azuredeploy.parameters.json
```
