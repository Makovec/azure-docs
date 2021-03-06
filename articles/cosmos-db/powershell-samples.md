---
title: Azure PowerShell Samples for Azure Cosmos DB | Microsoft Docs
description: Azure PowerShell Samples - Scripts to help you create and manage Azure Cosmos DB accounts. 
services: cosmos-db
author: mimig1
manager: jhubbard
editor: ''
tags: azure-service-management

ms.assetid:
ms.service: cosmos-db
ms.custom: sample
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: database
ms.date: 05/10/2017
ms.author: mimig
---

# Azure PowerShell samples for Azure Cosmos DB

The following table includes links to sample Azure PowerShell scripts for Azure Cosmos DB.

| |  |
|---|---|
|**Create an Azure Cosmos DB account**||
|[Create a DocumentDB API account](scripts/create-database-account-powershell.md)| Creates a single Azure Cosmos DB account to use with the DocumentDB API. |
|**Scale Azure Cosmos DB**||
|[Replicate Azure Cosmos DB account in multiple regions and configure failover priorities](scripts/scale-multiregion-powershell.md)|Globally replicates account data into multiple regions with a specified failover priority.|
|**Secure Azure Cosmos DB**||
| [Get account keys](scripts/secure-get-account-key-powershell.md) | Gets the primary and secondary master write keys and primary and secondary read-only keys for the account.|
| [Get MongoDB connection string](scripts/secure-mongo-connection-string-powershell.md) | Gets the connection string to connect your MongoDB app to your Azure Cosmos DB account.|
|[Regenerate account keys](scripts/secure-regenerate-key-powershell.md)|Regenerates the master or read-only key for the account.|
|[Create a firewall](scripts/create-firewall-powershell.md)| Creates an inbound IP access control policy to limit access to the account from an approved set of machines and/or cloud services.|
|**High availability, disaster recovery, backup and restore**||
|[Configure failover policy](scripts/ha-failover-policy-powershell.md)|Sets the failover priority of each region in which the account is replicated.|
|||