﻿---
title: ValidationPeriod.ValidTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ValidTo
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.validto(v=AX.60)
ms:contentKeyID: 49838235
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property

Gets the ending date for this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDTO")> _
<DataMemberAttribute> _
Public Property ValidTo As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As DateTimeOffset

value = instance.ValidTo
```

``` csharp
[ColumnAttribute("VALIDTO")]
[DataMemberAttribute]
public DateTimeOffset ValidTo { get; internal set; }
```

``` c++
[ColumnAttribute(L"VALIDTO")]
[DataMemberAttribute]
public:
property DateTimeOffset ValidTo {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

