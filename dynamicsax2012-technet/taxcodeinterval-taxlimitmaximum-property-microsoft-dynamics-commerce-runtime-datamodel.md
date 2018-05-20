﻿---
title: TaxCodeInterval.TaxLimitMaximum Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxLimitMaximum Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitMaximum
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxlimitmaximum(v=AX.60)
ms:contentKeyID: 62204360
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitMaximum
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMaximum Property

Gets the tax limit maximum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXLIMITMAX")> _
Public Property TaxLimitMaximum As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Decimal

value = instance.TaxLimitMaximum
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXLIMITMAX")]
public decimal TaxLimitMaximum { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXLIMITMAX")]
public:
property Decimal TaxLimitMaximum {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
