---
title: "IRowsetChangeImpl::DeleteRows | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["ATL.IRowsetChangeImpl.DeleteRows", "ATL::IRowsetChangeImpl::DeleteRows", "IRowsetChangeImpl.DeleteRows", "DeleteRows", "IRowsetChangeImpl::DeleteRows"]
dev_langs: ["C++"]
helpviewer_keywords: ["DeleteRows method"]
ms.assetid: 462ad4f1-3b2a-4134-9733-be65708aa1d9
caps.latest.revision: 9
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# IRowsetChangeImpl::DeleteRows
Deletes rows from the rowset.  
  
## Syntax  
  
```  
  
      STDMETHOD ( DeleteRows )(  
   HCHAPTER /* hReserved */,  
   DBCOUNTITEM cRows,  
   const HROW rghRows[],  
   DBROWSTATUS rgRowStatus[]   
);  
```  
  
#### Parameters  
 See [IRowsetChange::DeleteRows](https://msdn.microsoft.com/en-us/library/ms724362.aspx) in the *OLE DB Programmer's Reference*.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetChangeImpl Class](../../data/oledb/irowsetchangeimpl-class.md)