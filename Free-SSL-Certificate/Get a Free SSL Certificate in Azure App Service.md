Get a Free SSL Certificate in Azure App Service
--
Free SSL Certificate is now available in Azure App Service. Finally, we can enable HTTPS for our websites for free on Azure App Service. The feature is named App Service Managed Certificate that is fully managed by App Service.  The certificate will be valid for six months and it will renew automatically.

The free certificate comes with the following limitations:
-	Naked domains are not supported.
-	Does not support wildcard certificates.
-	Cannot export the certificate.

How to add free SSL certificates to Web Apps on Azure
Let’s follow the steps: 

Step 1


In the Azure portal, from the left menu, select App Services and then select your website name.

![Image](https://github.com/cloudstk/DNS/blob/b19bdf16929551ba2b9d70cc314b01131b775c92/Free-SSL-Certificate/media/SSL_CERT_1.jpg "icon")


Step 2

From the left navigation of your app, select TLS/SSL setting, and click on the Private Key Certificates (.pfx) button, and then click on Create App Service Managed Certificate to request an App Service Managed Certificate.

![Image](https://github.com/cloudstk/DNS/blob/b19bdf16929551ba2b9d70cc314b01131b775c92/Free-SSL-Certificate/media/SSL_CERT_02.jpg "icon")
