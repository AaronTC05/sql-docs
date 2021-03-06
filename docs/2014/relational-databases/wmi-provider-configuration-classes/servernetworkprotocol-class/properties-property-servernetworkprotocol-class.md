---
title: "Properties Property (ServerNetworkProtocol Class) | Microsoft Docs"
ms.custom: ""
ms.date: "06/13/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
api_name: 
  - "Properties Property (ServerNetworkProtocol Class)"
api_location: 
  - "sqlmgmproviderxpsp2up.mof"
topic_type: 
  - "apiref"
helpviewer_keywords: 
  - "Properties property"
ms.assetid: 6c971bfc-c277-4c1e-a06e-146dcc34e759
caps.latest.revision: 29
author: "JennieHubbard"
ms.author: "jhubbard"
manager: craigg
---
# Properties Property (ServerNetworkProtocol Class)
  Gets the properties associated with the server network protocol.  
  
## Syntax  
  
```  
  
object  
.Properties [= value]  
```  
  
## Parts  
 *object*  
 A [ServerNetworkProtocol Class](servernetworkprotocol-class.md) object that represents the network protocol used by the instance of [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)].  
  
## Property Value/Return Value  
 An array of [ServerNetworkProtocolProperty Class](../servernetworkprotocolproperty-class/servernetworkprotocolproperty-class.md) objects that represent the properties supported by the server network protocol.  
  
## Remarks  
  