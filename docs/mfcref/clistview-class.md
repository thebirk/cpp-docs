---
title: "CListView Class"
ms.custom: na
ms.date: "10/14/2016"
ms.prod: "visual-studio-dev14"
ms.reviewer: na
ms.suite: na
ms.technology: 
  - "devlang-cpp"
ms.tgt_pltfrm: na
ms.topic: "reference"
f1_keywords: 
  - "CListView"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "views, and common controls"
  - "CListView class"
ms.assetid: 7626bdb2-a1b8-4eab-b631-6743710a8432
caps.latest.revision: 20
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
# CListView Class
Simplifies use of the list control and of [CListCtrl](../mfcref/clistctrl-class.md), the class that encapsulates list-control functionality, with MFC's document-view architecture.  
  
## Syntax  
  
```  
class CListView : public CCtrlView  
```  
  
## Members  
  
### Public Constructors  
  
|Name|Description|  
|----------|-----------------|  
|[CListView::CListView](#clistview__clistview)|Constructs a `CListView` object.|  
  
### Public Methods  
  
|Name|Description|  
|----------|-----------------|  
|[CListView::GetListCtrl](#clistview__getlistctrl)|Returns the list control associated with the view.|  
  
### Protected Methods  
  
|Name|Description|  
|----------|-----------------|  
|[CListView::RemoveImageList](#clistview__removeimagelist)|Removes the specified image list from the list view.|  
  
## Remarks  
 For more information on this architecture, see the overview for the [CView](../mfcref/cview-class.md) class and the cross-references cited there.  
  
## Inheritance Hierarchy  
 [CObject](../mfcref/cobject-class.md)  
  
 [CCmdTarget](../mfcref/ccmdtarget-class.md)  
  
 [CWnd](../mfcref/cwnd-class.md)  
  
 [CView](../mfcref/cview-class.md)  
  
 [CCtrlView](../mfcref/cctrlview-class.md)  
  
 `CListView`  
  
## Requirements  
 **Header:** afxcview.h  
  
##  <a name="clistview__clistview"></a>  CListView::CListView  
 Constructs a `CListView` object.  
  
```  
CListView();  
```  
  
##  <a name="clistview__getlistctrl"></a>  CListView::GetListCtrl  
 Call this member function to get a reference to the list control associated with the view.  
  
```  
CListCtrl& GetListCtrl() const;  
```  
  
### Return Value  
 A reference to the list control associated with the view.  
  
### Example  
 [!code[NVC_MFCListView#7](../atl/codesnippet/CPP/clistview-class_1.cpp)]  
  
##  <a name="clistview__removeimagelist"></a>  CListView::RemoveImageList  
 Removes the specified image list from the list view.  
  
```  
void RemoveImageList( int nImageList );  
```  
  
### Parameters  
 `nImageList`  
 The zero-based index of the image to remove.  
  
## See Also  
 [MFC Sample ROWLIST](../top/visual-c---samples.md)   
 [CCtrlView Class](../mfcref/cctrlview-class.md)   
 [Hierarchy Chart](../mfc/hierarchy-chart.md)   
 [CCtrlView Class](../mfcref/cctrlview-class.md)