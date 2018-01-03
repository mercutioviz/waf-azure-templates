# Barracuda Web Application Firewall for Azure - VMSS Cluster

![Network diagram](https://raw.githubusercontent.com/mercutioviz/ngf-azure-templates/master/HA%20ILB/Azure%20-%20ha%20ilb%20with%20subnets.png)

## Prerequisites

Azure account has access to create network elements, storage, and virtual machines.

## Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmercutioviz%2Fngf-azure-templates%2Fmaster%2FHA%20ILB%2Ftemplate.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmercutioviz%2Fngf-azure-templates%2Fmaster%2FHA%20ILB%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
## Next Steps

Access each WAF via Web GUI on HTTP ports 8000, 8001, etc. and accept license agreement.
After logging in to each WAF once, test HTTPS to ports 8400, 8401, etc.
