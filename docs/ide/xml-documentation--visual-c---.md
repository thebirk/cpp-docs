---
title: "XML Documentation (Visual C++)"
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
  - "XML documentation"
  - "XML, documentation comments in source code"
  - "comments, C++ source code files"
  - "/// delimiter for C++ documentation"
ms.assetid: a1aec1c5-b2d1-4c74-83ae-1dbbbb76b506
caps.latest.revision: 18
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
# XML Documentation (Visual C++)
In Visual C++, you can add comments to your source code that will be processed to an .xml file. This file can then be the input to a process that creates documentation for the classes in your code.  
  
 In a Visual C++ code file, XML documentation comments must be located directly prior to a method or type definition. The comments can be used to populate the Intellisense QuickInfo data tip in the following scenarios:  
  
1.  when the code is compiled as a Windows Runtime component with an accompanying .winmd file  
  
2.  when the source code is included in the current project  
  
3.  in a library whose type declarations and implementations are located in the same header file  
  
> [!NOTE]
>  In the current release, code comments are not processed on templates or anything containing a template type (for example, a function taking a parameter as a template). Adding such comments will result in undefined behavior.  
  
 For details on creating an .xml file with documentation comments, see the following topics.  
  
|For information about|See|  
|---------------------------|---------|  
|The compiler options to use|[/doc](../buildref/-doc--process-documentation-comments---c-c---.md)|  
|Tags you can use to provide commonly used functionality in documentation|[Recommended Tags for Documentation Comments](../ide/recommended-tags-for-documentation-comments--visual-c---.md)|  
|The ID strings that the compiler produces to identify the constructs in your code|[Processing the .xml File](../ide/.xml-file-processing.md)|  
|How to delimit documentation tags|[Delimiters for Visual C++ Documentation Tags](../ide/delimiters-for-visual-c---documentation-tags.md)|  
|Generating an .xml file from one or more .xdc files.|[XDCMake Reference](../ide/xdcmake-reference.md)|  
|Links to information about XML as it relates to Visual Studio feature areas|[XML in Visual Studio](../Topic/XML%20Tools%20in%20Visual%20Studio.md)|  
  
 If you need to put XML special characters in the text of a documentation comment, you must use XML entities or a CDATA section.  
  
## See Also  
 [Component Extensions for Runtime Platforms](../windows/component-extensions-for-runtime-platforms.md)