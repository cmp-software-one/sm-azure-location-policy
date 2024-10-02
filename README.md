# About this Automation

This policy enables you to restrict the locations your organization can specify when deploying resources and resource groups into Azure. 

Use to enforce meet your geo-compliance regulations. 

Exludes Microsoft.AzureActiveDirectory/b2cDirectories, and resources that use the 'global' region.


## Fields and Best Practices

| Field         | Best practice and Options      | Limitations |
| ------------- | --------------------------------- |-|
| **Request title**       | A friendly short name to remind you why you created this account         | 256 characters|
| **Request description**        | Add more details on the need for the account          |256 characters |
| **Azure subscription ID** | Select your target Subscription ID | NA |
| **Azure Region (e.g. 'west europe', 'north europe')** | **Select your region**  | Select from the drop-down |


### Regional Restriction best practies

[Microsoft Tagging best practices](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/naming-and-tagging)


