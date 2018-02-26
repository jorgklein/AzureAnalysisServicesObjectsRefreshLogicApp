# Azure Analysis Services Model Refresh Logic App
Logic App to refresh your Azure Analysis Services model.

## Prerequisites ##

* Read the accompanying blog post from Jorg Klein here: https://jorgklein.com/
* Create service principal that has the following permissions:
  - Access to the AAS models
  - Contributor role on the AAS instance in Azure

## Deployment ##

1. Click this button (hold CTRL while clicking to open in a new tab):

    <a target="_blank" id="deploy-to-azure"  href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FStefanPuntNL%2FAzureAnalysisServicesRefreshLogicApp%2Fmaster%2FLogicApp.json"><img src="http://azuredeploy.net/deploybutton.png"/></a>

2. Fill the required parameters, agree with the terms and click on Purchase
3. After the deployment go to the created resource group and click on the Logic App resource
6. Click on Edit and verify that it was deployed correctly
7. Run the Logic App
