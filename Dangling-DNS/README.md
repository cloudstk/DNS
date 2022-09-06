# Dangling DNS

Reference list of Azure domains.
| Service        | Type | FQDNproperty |
| ------------- | ------------- |------------- |
|Azure Front |Door	microsoft.network/frontdoors	|xyz.azurefd.net|
|Azure Blob |Storage	microsoft.storage/storageaccounts	|xyz.blob.core.windows.net|
|Azure CDN	|microsoft.cdn/profiles/endpoints	|xyz.azureedge.net|
|Public IP |addresses	microsoft.network/publicipaddresses	|xyz.EastUs.cloudapp.azure.com|
|Azure Traffic Manager	|microsoft.network/trafficmanagerprofiles	|xyz.trafficmanager.net|
|Azure Container Instance	|microsoft.containerinstance/containergroups	|xyz.EastUs.azurecontainer.io|
|Azure API Management	|microsoft.apimanagement/service	|xyz.azure-api.net|
|Azure App Service	|microsoft.web/sites	|xyz.azurewebsites.net|
|Azure App Service - Slots	|microsoft.web/sites/slots	|xyz-def.azurewebsites.net|

[Prevent dangling DNS entries and avoid subdomain takeover](https://docs.microsoft.com/en-us/azure/security/fundamentals/subdomain-takeover)
