---
Description: The get\_Invert method retrieves a Boolean value indicating whether the key operation is inverted. This property applies to all key types except DXTKEY\_ALPHA.
ms.assetid: 2ccf2066-3d9c-493b-bc54-a03e7d075531
title: IDxtKey::get_Invert method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtKey.get_Invert
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IDxtKey::get\_Invert method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `get_Invert` method retrieves a Boolean value indicating whether the key operation is inverted. This property applies to all key types except DXTKEY\_ALPHA.

## Syntax


```C++
HRESULT get_Invert(
  [out, retval] BOOL *pVal
);
```



## Parameters

<dl> <dt>

*pVal* \[out, retval\]
</dt> <dd>

Receives one of the following values.



| Value     | Description                                                                       |
|-----------|-----------------------------------------------------------------------------------|
| **TRUE**  | Pixels in the overlying image are inverted with respect to the default operation. |
| **FALSE** | Pixels in the overlying image are made transparent in the default manner.         |



 

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://msdn.microsoft.com/windowsvista/bb980924.aspx). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IDxtKey Interface**](idxtkey.md)
</dt> <dt>

[**IDxtKey::get\_KeyType**](idxtkey-get-keytype.md)
</dt> </dl>

 

 




