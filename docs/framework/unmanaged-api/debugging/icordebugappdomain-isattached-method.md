---
title: "ICorDebugAppDomain::IsAttached Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugAppDomain.IsAttached"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugAppDomain::IsAttached"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "IsAttached method [.NET Framework debugging]"
  - "ICorDebugAppDomain::IsAttached method [.NET Framework debugging]"
ms.assetid: af0c67c7-f53e-47c9-b84b-be50bd04903e
caps.latest.revision: 12
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugAppDomain::IsAttached Method
Gets a value that indicates whether the debugger is attached to the application domain.  
  
## Syntax  
  
```  
HRESULT IsAttached (  
    [out] BOOL  *pbAttached  
);  
```  
  
#### Parameters  
 `pbAttached`  
 [out] `true` if the debugger is attached to the application domain; otherwise, `false`.  
  
## Remarks  
 The ICorDebugController methods cannot be used until the debugger attaches to the application domain.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]