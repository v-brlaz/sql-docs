---
title: "ProcessId Class (SqlService Class) | Microsoft Docs"
ms.custom: ""
ms.date: "03/04/2017"
ms.prod: "sql"
ms.prod_service: "database-engine"
ms.service: ""
ms.component: "wmi"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ProcessId Class (SqlService Class)"
apilocation: 
  - "sqlmgmproviderxpsp2up.mof"
apitype: "MOFDef"
helpviewer_keywords: 
  - "ProcessId property"
ms.assetid: 99b5a2e9-b44a-48a0-993e-04bd15c7fef4
caps.latest.revision: 35
author: "CarlRabeler"
ms.author: "carlrab"
manager: "craigg"
ms.workload: "Inactive"
---
# ProcessId Class (SqlService Class)
[!INCLUDE[tsql-appliesto-ss2008-xxxx-xxxx-xxx-md](../../../includes/tsql-appliesto-ss2008-xxxx-xxxx-xxx-md.md)]
  Gets the system process ID that uniquely identifies a service.  
  
## Syntax  
  
```  
  
object.ProcessId [= value]  
```  
  
## Parts  
 *object*  
 A [SqlService Class](../../../relational-databases/wmi-provider-configuration-classes/sqlservice-class/sqlservice-class.md) object that represents the service.  
  
## Property Value/Return Value  
 A **uint32** value that specifies the ID that uniquely identifies the process.  
  
## Remarks  
  
## Example  
  
```  
mysqlservice.ProcessId = 324  
```  
  
## See Also  
 [Starting and Stopping Services](http://technet.microsoft.com/library/ms174886\(v=sql.105\).aspx)  
  
  
