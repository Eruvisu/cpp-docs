---
title: "fill_n (STL/CLR) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["cliext::fill_n"]
dev_langs: ["C++"]
helpviewer_keywords: ["fill_n function"]
ms.assetid: bb9f2f71-ba1d-44ec-8b47-6ece149dd6b8
caps.latest.revision: 4
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
---
# fill_n (STL/CLR)
Assigns a new value to a specified number of elements in a range beginning with a particular element.  
  
## Syntax  
  
```  
template<class _OutIt, class _Diff, class _Ty> inline  
    void fill_n(_OutIt _First, _Diff _Count, const _Ty% _Val);  
```  
  
## Remarks  
 This function behaves the same as the C++ Standard Library function `fill_n`. For more information, see [fill_n](../standard-library/algorithm-functions.md#fill_n).  
  
## Requirements  
 **Header:** \<cliext/algorithm>  
  
 **Namespace:** cliext  
  
## See Also  
 [algorithm (STL/CLR)](../dotnet/algorithm-stl-clr.md)