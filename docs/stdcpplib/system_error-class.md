---
title: "system_error Class"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "article"
f1_keywords: 
  - "system_error/std::system_error"
  - "std.system_error"
  - "std::system_error"
  - "system_error"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "system_error class"
ms.assetid: 2eeaacbb-8a4a-4ad7-943a-997901a77f32
caps.latest.revision: 15
ms.author: "corob"
manager: "ghogen"
translation.priority.mt: 
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
# system_error Class
Represents the base class for all exceptions thrown to report a low-level system error.  
  
## Syntax  
  
```  
class system_error : public runtime_error {  
public:  
    explicit system_error(error_code _Errcode, const string& _Message = "");  
    system_error(error_code _Errcode, const char *_Message);  
    system_error(error_code::value_type _Errval,  
        const error_category& _Errcat, const string& _Message);  
    system_error(error_code::value_type _Errval,  
        const error_category& _Errcat, const char *_Message);  
    const error_code& code() const throw();  
    const error_code& code() const throw();  
    };  
```  
  
## Remarks  
 The value returned by `what` in the class exception is constructed from `_Message` and the stored object of type [error_code](../stdcpplib/error_code-class.md) (either `code` or `error_code(_Errval, _Errcat)`).  
  
 The member function `code` returns the stored [error_code](../stdcpplib/error_code-class.md) object.  
  
## Requirements  
 **Header:** <system_error>  
  
 **Namespace:** std  
  
## See Also  
 [<system_error>](../stdcpplib/-system_error-.md)