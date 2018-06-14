---
Description: The Invoke method of the CIM\_MemoryCheck class evaluates a particular check. Details of how the method evaluates a particular check in a CIM context is described by the non-abstract CIM\_Check subclasses. This method is inherited from CIM\_Check.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 264a7690-b066-4024-8cb1-d988b829dc72
ms.prod: windows-server-dev
ms.technology:
- cimwin32
- windows-management-instrumentation
ms.tgt_platform: multiple
title: Invoke method of the CIM\_MemoryCheck class
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Invoke method of the CIM\_MemoryCheck class

The **Invoke** method of the [**CIM\_MemoryCheck**](cim-memorycheck.md) class evaluates a particular check. Details of how the method evaluates a particular check in a CIM context is described by the non-abstract [**CIM\_Check**](cim-check.md) subclasses. This method is inherited from **CIM\_Check**.

> \[!Important\]  
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](Http://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

 

This topic uses Managed Object Format (MOF) syntax. For more information about using this method, see [Calling a Method](https://msdn.microsoft.com/library/aa384832).

## Syntax


```mof
uint32 Invoke();
```



## Parameters

This method has no parameters.

## Return value

Returns a value of 0 (zero) on success, and any other number to indicate an error.

## Remarks

This method is currently not implemented by WMI. To use this method, you must implement it in your own provider.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



## See also

<dl> <dt>

[CIM\_MemoryCheck](invoke-method-in-class-cim-memorycheck.md)
</dt> <dt>

[**CIM\_MemoryCheck**](cim-memorycheck.md)
</dt> </dl>

 

 



