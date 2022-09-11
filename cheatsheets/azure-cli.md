# Azure CLI

### Account
```bash
# Sign in to Azure
az login

# List all subscriptions under current account
az account list --output table

# Set active/default subscription
az account set --subscription Proof-Of-Concept
```

### Event Grid
```bash
# List all Event Grid(topic) under current subscription
az eventgrid topic list
```

<br /><br />
**_Author: Steve Mak_**<br />
_Last Update: 9/11/2022, 5:25:27 PM_

