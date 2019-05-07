# Azure Stack ARM Template Matrix

The following table contains all of the tagged releases of the F5 ARM templates for Azure Stack, and the corresponding BIG-IP versions, license types and throughput levels available for a specific tagged release.  To view a Tag, from the f5-azure-arm-templates repo (https://github.com/F5Networks/f5-azure-stack-arm-templates/ or a sub directory), click the Branch < current branch > button, and then click the Tags tab.  You see a list of all of the F5 tagged releases.

**Note:** If using a BYOL (bring your own license) license the throughput available may be greater than what is described on the matrix.

> **_CRITICAL:_**  As of F5 Azure Stack ARM template GitHub release 1.2.0.0, BIG-IP version 12.1 is no longer supported, and Microsoft Azure has removed Azure BIG-IP image version 12.1.30300 (BIG-IP version 12.1.3.3 Build 0.0.4) from the Marketplace. While this change won't affect most users, if you have deployed templates as part of an automated process that updates Azure resources, and you have previously downloaded the BIG-IP v12.1.3 image you can you can use a previously released template to deploy this image.  To find a previously released template, from the Branch drop-down, click the Tabs tab, and then select v1.1.3.0 or earlier.

| Release Tag | Template Family | BIG-IP Versions | BIG-IQ Versions | Image Names |
| --- | --- | --- | --- | 
| [v1.2.0.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.2.0.0) | Standalone | Latest, BIG-IP v14.003000, BIG-IP v13.1.100000 | BIG-IQ v5.4, v6.0.1 | *AllTwoBootLocations, AllOnebootLocation, LTMTwoBootLocations, LTMOneBootLocation* |
| [v1.1.3.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.1.2.0) | Standalone | BIG-IP v13.1.10000, 12.1.303000 | BIG-IQ v5.4, v6.0.1 | *AllTwoBootLocations, AllOnebootLocation, LTMTwoBootLocations, LTMOneBootLocation* |
| [v1.1.2.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.1.2.0) | Standalone | BIG-IP v13.1.10000, 12.1.303000 | BIG-IQ v5.4, v6.0.1 | *AllTwoBootLocations, AllOnebootLocation, LTMTwoBootLocations, LTMOneBootLocation* |
| [v1.1.1.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.1.1.0) | Standalone | BIG-IP v13.1.10000, 12.1.303000 | BIG-IQ v5.4, v6.0.1 | *AllTwoBootLocations, AllOnebootLocation, LTMTwoBootLocations, LTMOneBootLocation* |
| [v1.1.0.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.1.0.0) | Standalone | BIG-IP v13.1.10000, 12.1.303000 | BIG-IQ v5.4, v6.0.1 | *AllTwoBootLocations, AllOnebootLocation, LTMTwoBootLocations, LTMOneBootLocation* |
| [v1.0.0.0](https://github.com/F5Networks/f5-azure-arm-templates/releases/tag/v1.0.0.0) | Standalone | BIG-IP v13.1.0200, 12.1.303000 | BIG-IQ v5.3, 5.4 | *Good/Better/Best* |
