---
UID: NC:d3d12umddi.PFND3D12DDI_CREATE_COMMAND_LIST_0001
title: PFND3D12DDI_CREATE_COMMAND_LIST_0001
author: windows-driver-content
description: 
ms.assetid: ff7999b0-ba8c-4302-b1b8-a65d6ccb2822
ms.author: windowsdriverdev
ms.date: 
ms.topic: callback
ms.prod: windows-hardware
ms.technology: windows-devices
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
-	apiref
api_type: 
-	UserDefined
api_location: 
-	d3d12umddi.h
api_name: 
-	PFND3D12DDI_CREATE_COMMAND_LIST_0001
product: 
- Windows
targetos: Windows
tech.root: display
---

# PFND3D12DDI_CREATE_COMMAND_LIST_0001 callback function

## -description

Implemented by the client driver to ... 

## -prototype

```
//Declaration

PFND3D12DDI_CREATE_COMMAND_LIST_0001 Pfnd3d12ddiCreateCommandList0001; 

// Definition

HRESULT Pfnd3d12ddiCreateCommandList0001 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATE_COMMAND_LIST_0001 *
)
{...}

PFND3D12DDI_CREATE_COMMAND_LIST_0001 


```

## -parameters

### -param D3D12DDI_HDEVICE: 
### -param *: 



## -returns

Returns HRESULT that ...

## -remarks

Register your implementation of this callback function by setting the appropriate member of <!-- REPLACE ME --> and then calling <!-- REPLACE ME -->.


## -see-also