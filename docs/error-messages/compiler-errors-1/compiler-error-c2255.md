---
title: "Compiler Error C2255 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C2255"]
dev_langs: ["C++"]
helpviewer_keywords: ["C2255"]
ms.assetid: 67dc4cb0-de6b-4405-bd64-d47736367a93
caps.latest.revision: 8
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
---
# Compiler Error C2255
'element' : not allowed outside of a class definition  
  
 For example, a nonmember function is declared a `friend`.  
  
 The following sample generates C2255:  
  
```  
// C2255.cpp  
// compile with: /c  
class A {  
private:  
   void func1();  
   friend void func2();  
};  
  
friend void func1() {}   // C2255  
void func2(){}  
```