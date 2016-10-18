---
title: "STACKSIZE"
ms.custom: na
ms.date: 10/03/2016
ms.devlang: 
  - C++
ms.prod: visual-studio-dev14
ms.reviewer: na
ms.suite: na
ms.technology: 
  - devlang-cpp
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 4d8c79bd-1cb4-4e4d-90f2-b5a7a4d20e7a
caps.latest.revision: 7
manager: ghogen
translation.priority.ht: 
  - cs-cz
  - de-de
  - es-es
  - fr-fr
  - it-it
  - ja-jp
  - ko-kr
  - pl-pl
  - pt-br
  - ru-ru
  - tr-tr
  - zh-cn
  - zh-tw
---
# STACKSIZE
Sets the size of the stack in bytes.  
  
```  
STACKSIZE reserve[,commit]  
```  
  
## Remarks  
 An equivalent way to set the stack is with the [Stack Allocations](../VS_visualcpp/-STACK--Stack-Allocations-.md) (/STACK) option. See the documentation on that option for details about the *reserve* and `commit` arguments.  
  
 This option has no effect on DLLs.  
  
## See Also  
 [Rules for Module-Definition Statements](../VS_visualcpp/Rules-for-Module-Definition-Statements.md)