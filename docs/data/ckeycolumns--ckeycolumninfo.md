---
title: "CKeyColumns, CKeyColumnInfo"
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
  - "m_szTableSchema"
  - "m_szConstraintCatalog"
  - "m_nColumnPropID"
  - "ORDINAL_POSITION"
  - "m_nOrdinalPosition"
  - "COLUMN_GUID"
  - "CKeyColumnInfo"
  - "CONSTRAINT_NAME"
  - "m_szColumnName"
  - "m_szTableCatalog"
  - "m_szConstraintSchema"
  - "COLUMN_PROPID"
  - "m_guidColumn"
  - "CKeyColumns"
  - "m_szTableName"
  - "CONSTRAINT_CATALOG"
  - "CONSTRAINT_SCHEMA"
  - "m_szConstraintName"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "COLUMN_PROPID"
  - "ORDINAL_POSITION"
  - "m_szConstraintCatalog"
  - "CONSTRAINT_CATALOG"
  - "m_szTableSchema"
  - "TABLE_CATALOG"
  - "CKeyColumnInfo parameter class"
  - "TABLE_NAME"
  - "CONSTRAINT_NAME"
  - "m_nOrdinalPosition"
  - "m_nColumnPropID"
  - "CONSTRAINT_SCHEMA"
  - "TABLE_SCHEMA"
  - "m_szColumnName"
  - "COLUMN_NAME"
  - "m_szTableCatalog"
  - "m_szConstraintName"
  - "CKeyColumns typedef class"
  - "m_szTableName"
  - "m_szConstraintSchema"
  - "COLUMN_GUID"
  - "m_guidColumn"
ms.assetid: 40525a4f-a9cf-4e9f-886d-8a6ddd18a3d6
caps.latest.revision: 6
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
# CKeyColumns, CKeyColumnInfo
Call the typedef class **CKeyColumns** to implement its parameter class **CKeyColumnInfo**.  
  
## Remarks  
 See [Schema Rowset Classes and Typedef Classes](../data/schema-rowset-classes-and-typedef-classes.md) for more information on using typedef classes.  
  
 This class identifies the columns, defined in the catalog, that are constrained as keys by a given user.  
  
 The following table lists the class data members and their corresponding OLE DB Columns. See [KEY_COLUMN_USAGE Rowset](https://msdn.microsoft.com/en-us/library/ms712990.aspx) in the *OLE DB Programmer's Reference* for more information about the schema and columns.  
  
|Data members|OLE DB columns|  
|------------------|--------------------|  
|m_szConstraintCatalog|CONSTRAINT_CATALOG|  
|m_szConstraintSchema|CONSTRAINT_SCHEMA|  
|m_szConstraintName|CONSTRAINT_NAME|  
|m_szTableCatalog|TABLE_CATALOG|  
|m_szTableSchema|TABLE_SCHEMA|  
|m_szTableName|TABLE_NAME|  
|m_szColumnName|COLUMN_NAME|  
|m_guidColumn|COLUMN_GUID|  
|m_nColumnPropID|COLUMN_PROPID|  
|m_nOrdinalPosition|ORDINAL_POSITION|  
  
## Requirements  
 **Header:** atldbsch.h  
  
## See Also  
 [CRestrictions Class](../data/crestrictions-class.md)