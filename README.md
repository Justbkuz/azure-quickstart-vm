# Deployment of a Ubuntu VM with Dynatrace OneAgent Extension

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdynatrace-innovationlab%2Fazure-quickstart-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fdynatrace-innovationlab%2Fazure-quickstart-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

<br><br>

![Dynatrace Logo](./images/Dynatrace_Logo_RGB_CPH_512x92px.png)

This template allows you to deploy a Ubuntu VM with the Dynatrace OneAgent VM extension installed and fully configured.
The concrete size for the VM can be chosen during the deployment process.

# Bring your own license
During the installation procedure, a Dynatrace tenant ID and a token have to be provided. Get your own free trial here: <a href="https://www.dynatrace.com/trial/">Dynatrace free trial</a>. 

# Installation

Click the "Deploy to Azure" button on top to begin deployment of the VM+OneAgent.
For the installation, a couple of parameters are needed:

- Azure subscription
- Resource group
- Location
- Admin username
- Admin password
- DNS Prefix (has to be unique)
- Ubuntu OS Version
- VM Size
- Dynatrace Tenant ID
- Dynatrace Tenant PaaS Token



# Screenshot

![Installation](./images/template.png)