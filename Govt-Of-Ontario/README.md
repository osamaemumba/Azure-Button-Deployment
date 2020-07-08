## Storage Account

#### Prerequisites:
1. Resource group for deployment of storage account.

#### To be provided:
1. Resource Group
2. Storage Account Name

Click the following button to deploy a new storage account and provide the above values.

[![Deploy Storage Account to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fosamaemumba%2FAzure-Button-Deployment%2Fmaster%2FGovt-Of-Ontario%2FARM-Template-StorageAccount%2Fstorage_account_arm_template.json)

## Data Factory

#### Prerequisites:
1. Resource group for deployment of data factory.
2. A storage account for storing raw and curated files.

#### To be provided:
1. Resource Group
2. Data Factory Name
3. Storage Account Name

Click the following button to deploy a new data factory and provide the above values. Here the storage account name refers to that storage account which will be used for storing the raw and curated files.

[![Deploy Data Factory to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fosamaemumba%2FAzure-Button-Deployment%2Fmaster%2FGovt-Of-Ontario%2FARM-Template-One-Click%2Fone_click_arm_template.json)


## One Click Deployment

#### Prerequisites:
1. Resource group for deployment of storage account and data factory.

#### To be provided:
1. Resource Group
2. Data Factory Name
3. Storage Account Name

Click the following button to deploy a new storage account and a new data factory and provide the above values. The latter resource will use the former one to store the raw and curated files.

[![Deploy Storage Account and Data Factory to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fosamaemumba%2FAzure-Button-Deployment%2Fmaster%2FGovt-Of-British-Columbia%2FARM-Template-One-Click%2Fone_click_arm_template.json)
