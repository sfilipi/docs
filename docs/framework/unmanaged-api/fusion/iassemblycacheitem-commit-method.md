---
title: "IAssemblyCacheItem::Commit Method"
ms.date: "03/30/2017"
api_name: 
  - "IAssemblyCacheItem.Commit"
api_location: 
  - "fusion.dll"
api_type: 
  - "COM"
f1_keywords: 
  - "IAssemblyCacheItem::Commit"
helpviewer_keywords: 
  - "IAssemblyCacheItem::Commit method [.NET Framework fusion]"
  - "Commit method, IAssemblyCacheItem interface [.NET Framework fusion]"
ms.assetid: c2321f17-f46f-4815-ae41-b28678753613
topic_type: 
  - "apiref"
author: "rpetrusha"
ms.author: "ronpet"
---
# IAssemblyCacheItem::Commit Method
Commits the cached assembly reference to memory.  
  
## Syntax  
  
```  
HRESULT Commit (  
    [in] DWORD dwFlags,   
    [out, optional] ULONG *pulDisposition  
);  
```  
  
## Parameters  
 `dwFlags`  
 [in] Flags defined in Fusion.idl.  
  
 `pulDisposition`  
 [out, optional] A value that indicates the result of the operation.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** Fusion.h  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]  
  
## See also
- [IAssemblyCacheItem Interface](../../../../docs/framework/unmanaged-api/fusion/iassemblycacheitem-interface.md)
