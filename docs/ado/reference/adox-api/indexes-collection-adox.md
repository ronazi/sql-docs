---
description: "Indexes Collection (ADOX)"
title: "Indexes Collection (ADOX) | Microsoft Docs"
ms.prod: sql
ms.prod_service: connectivity
ms.technology: connectivity
ms.custom: ""
ms.date: "01/19/2017"
ms.reviewer: ""
ms.topic: conceptual
apitype: "COM"
f1_keywords: 
  - "Table::Indexes"
  - "Indexes"
helpviewer_keywords: 
  - "Indexes collection [ADOX]"
ms.assetid: 184cf536-455c-42be-bf1c-a5c25bade961
author: rothja
ms.author: jroth
---
# Indexes Collection (ADOX)
Contains all [Index](./index-object-adox.md) objects of a table.  
  
## Remarks  
 The [Append](./append-method-adox-indexes.md) method for an **Indexes** collection is unique for ADOX. You can:  
  
-   Add a new index to the collection with the **Append** method.  
  
 The remaining properties and methods are standard to ADO collections. You can:  
  
-   Access an index in the collection with the [Item](../ado-api/item-property-ado.md) property.  
  
-   Return the number of indexes contained in the collection with the [Count](../ado-api/count-property-ado.md) property.  
  
-   Remove an index from the collection with the [Delete](./delete-method-adox-collections.md) method.  
  
-   Update the objects in the collection to reflect the current database schema with the [Refresh](../ado-api/refresh-method-ado.md) method.  
  
 This section contains the following topic.  
  
-   [Indexes Collection Properties, Methods, and Events](./indexes-collection-properties-methods-and-events.md)  
  
## See Also  
 [Indexes Append Method Example (VB)](./indexes-append-method-example-vb.md)   
 [Index Object (ADOX)](./index-object-adox.md)