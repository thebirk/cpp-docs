---
title: "Linkage in Names with Class Scope"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "language-reference"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "scope [C++], linkage rules"
  - "linkage [C++], scope linkage rules"
  - "names [C++], scope linkage rules"
  - "classes [C++], scope"
  - "external linkage, scope linkage rules"
  - "class names [C++], linkage"
  - "classes [C++], names"
  - "scope [C++], class names"
  - "class scope [C++], linkage in names with"
ms.assetid: 45275ff3-6e94-4967-82c8-ba540ef4da28
caps.latest.revision: 8
ms.author: "mblome"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Linkage in Names with Class Scope
The following linkage rules apply to names with class scope:  
  
-   Static class members have external linkage.  
  
-   Class member functions have external linkage.  
  
-   Enumerators and `typedef` names have no linkage.  
  
 **Microsoft Specific**  
  
-   Functions declared as `friend` functions must have external linkage. Declaring a static function as a `friend` generates an error.  
  
 **END Microsoft Specific**  
  
## See Also  
 [Program and Linkage](../cpp/program-and-linkage---c---.md)