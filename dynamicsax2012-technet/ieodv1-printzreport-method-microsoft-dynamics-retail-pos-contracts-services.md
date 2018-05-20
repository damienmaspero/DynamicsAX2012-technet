﻿---
title: IEODV1.PrintZReport Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PrintZReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.PrintZReport(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ieodv1.printzreport(v=AX.60)
ms:contentKeyID: 47344115
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.PrintZReport
dev_langs:
- CSharp
- C++
- VB
---

# PrintZReport Method

Prints a 'Z-Report'.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PrintZReport ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IEODV1
Dim transaction As IPosTransaction

instance.PrintZReport(transaction)
```

``` csharp
void PrintZReport(
    IPosTransaction transaction
)
```

``` c++
void PrintZReport(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEODV1 Interface](ieodv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)
