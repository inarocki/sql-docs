---
title: "storesMixedCaseIdentifiers Method (SQLServerDatabaseMetaData)"
description: "storesMixedCaseIdentifiers Method (SQLServerDatabaseMetaData)"
author: David-Engel
ms.author: v-davidengel
ms.date: "01/19/2017"
ms.prod: sql
ms.technology: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerDatabaseMetaData.storesMixedCaseIdentifiers"
apitype: "Assembly"
---
# storesMixedCaseIdentifiers Method (SQLServerDatabaseMetaData)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves whether this database treats mixed-case SQL identifiers that are not enclosed in quotation marks as case-insensitive and stores them in mixed case.  
  
## Syntax  
  
```  
  
public boolean storesMixedCaseIdentifiers()  
```  
  
## Return Value  
 **true** if the identifiers are stored in mixed case. Otherwise, **false**.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This storesMixedCaseIdentifiers method is specified by the storesMixedCaseIdentifiers method in the java.sql.DatabaseMetaData interface.  
  
## See Also  
 [SQLServerDatabaseMetaData Methods](../../../connect/jdbc/reference/sqlserverdatabasemetadata-methods.md)   
 [SQLServerDatabaseMetaData Members](../../../connect/jdbc/reference/sqlserverdatabasemetadata-members.md)   
 [SQLServerDatabaseMetaData Class](../../../connect/jdbc/reference/sqlserverdatabasemetadata-class.md)  
  
  
