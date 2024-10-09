# Microsoft Azure Resource Migration

> source by tfitzmac \
> [https://github.com/tfitzmac/resource-capabilities]()

# Azure Portal Configuration
For this to excel file to work, You need to add the following collumns to the resource overview.

> Name, \
> Type,  \
> Resource Group, \
> Subscription, \
> Location, \
> Resource Type

![image](https://github.com/smoonlee/azure-migration-template/assets/22956963/5f3bda61-2df1-4404-bcb5-efd81d33035c)

## Download Resource Data
From the Azure Portal, click `Export to CSV`

![image](https://github.com/smoonlee/azure-migration-template/assets/22956963/b19ff54d-26de-4fde-aef2-02df96e70c6f)

## Download GitHub Repository

``` bash
git clone https://github.com/smoonlee/azure-migration-template.git
```
Open the `azure-resource-migration-tempalte.xlsx` copy the data from the .csv file and you should get a report like

![image](https://github.com/smoonlee/azure-migration-template/assets/22956963/a74386b3-e22b-4daa-a7ca-d00db03d3908)

## Summary
This providers you with a report of resource which you can move from one subscription to another. If you cannot move `[0]` then you need to scrape the ARM Template and rebuild! 
