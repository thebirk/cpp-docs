---
title: "Character Comparison"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "comparing characters"
  - "MBCS [C++], character comparison"
  - "characters [C++], comparing"
ms.assetid: 18846e44-3e6e-40c4-9b42-3153fb15db20
caps.latest.revision: 8
ms.author: "ghogen"
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
# Character Comparison
Use the following tips:  
  
-   Comparing a known lead byte with an ASCII character works correctly:  
  
    ```  
    if( *sz1 == 'A' )  
    ```  
  
-   Comparing two unknown characters requires the use of one of the macros defined in Mbstring.h:  
  
    ```  
    if( !_mbccmp( sz1, sz2) )  
    ```  
  
     This ensures that both bytes of a double-byte character are compared for equality.  
  
## See Also  
 [MBCS Programming Tips](../text/mbcs-programming-tips.md)   
 [Buffer Overflow](../text/buffer-overflow.md)