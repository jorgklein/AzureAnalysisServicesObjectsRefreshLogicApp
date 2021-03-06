# Azure Analysis Services Objects Refresh Logic App
Logic App to refresh your Azure Analysis Services objects.

## Prerequisites ##

* Read the accompanying blog post from Jorg Klein here: https://jorgklein.com/2018/02/28/process-azure-analysis-services-objects-using-a-logic-app-part-2/
* Create service principal that has the 3 permissions below. A step-by-step guide to create a service principal and grant permissions i and ii can be found here: https://jorgklein.com/2018/01/30/process-azure-analysis-services-objects-from-azure-data-factory-v2-using-a-logic-app/
  1. Azure Analysis Services Server administrator
  2. API Access: Azure Analysis Services (SQL Server Analysis Services Azure) - Read and Write all Models
  3. Contributor role on the Azure Analysis Services service in Azure

## Deployment ##

1. Click this button (hold CTRL while clicking to open in a new tab):

<a target="_blank" id="deploy-to-azure"  href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjorgklein%2FAzureAnalysisServicesObjectsRefreshLogicApp%2Fmaster%2FLogicApp.json"><img src="http://azuredeploy.net/deploybutton.png"/></a>

2. Fill the required parameters, agree with the terms and click on Purchase
3. After the deployment go to the created resource group and click on the Logic App resource
6. Click on Edit and verify that it was deployed correctly
7. Run the Logic App
