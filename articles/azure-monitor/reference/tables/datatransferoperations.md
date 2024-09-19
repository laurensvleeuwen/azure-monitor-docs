---
title: Azure Monitor Logs reference - DataTransferOperations
description: Reference for DataTransferOperations table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: orens
author: osalzberg
ms.date: 09/16/2024
---

# DataTransferOperations

Logs generated by Azure Data Transfer as objects are transferred. These logs can be used to determine if an object has successfully transferred, failed to transfer, or is in the process of transferring. A typical use case would be an objects latest status of 'InTransit' indicating that the object is still transferring and no action needs to be taken.


## Table attributes

|Attribute|Value|
|---|---|
|**Resource types**|microsoft.azuredatatransfer/connections|
|**Categories**|Azure Resources|
|**Solutions**| LogManagement|
|**Basic log**|Yes|
|**Ingestion-time transformation**|No|
|**Sample Queries**|[Yes](/azure/azure-monitor/reference/queries/datatransferoperations)|



## Columns
  
[!INCLUDE [datatransferoperations](~/reusable-content/ce-skilling/azure/includes/azure-monitor/reference/tables/datatransferoperations-include.md)]