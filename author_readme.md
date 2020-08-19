# Azure Active Directory Domain Services - ADDS Domain Controller Setup

This template deploys a Windows Server 2016 VM, and configuring it as an ADDS Server

# Settings
- local admin: labadmin
- local admin password: L@BadminPa55w.rd
- Azure VNET: jumpVMVNet (10.1.0.0./16)
- Subnet: SubNet (10.1.0.0/24)
- Public IP: addsrdpip (basic / static)

# Operating System and core tools
- Operating System Windows Server 2016 Enterprise
- Active Directory Domain Services (ADDS)
- 

# Active Directory Domain
- addomain.demo

**Note: the AADS VM deployment takes +/- 30 minutes in total**

## Setup Instructions ##

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpdtit%2FARMTemplates%2Fmaster%2FAzureIdentity%2Fazuredeploy.json)

You can use the "Deploy to Azure" button to have this ADDSVM deployed into your Azure subscription right away. 

Another option is deploying this template from the Azure Portal, using the following steps:
1. Create New Resource
2. type "Template Deployment" in the Search Marketplace field
3. choose Build your own template in the editor
4. open the "jumpvm_woutput.json" in raw format in GitHub 
5. Copy / Paste the content of the template file into the Azure portal - Template editor
6. Accept the default values or replace with your own choices

