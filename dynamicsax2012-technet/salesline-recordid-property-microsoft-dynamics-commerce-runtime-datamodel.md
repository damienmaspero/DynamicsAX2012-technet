﻿---
title: SalesLine.RecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.RecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.recordid(v=AX.60)
ms:contentKeyID: 62205576
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.RecordId
dev_langs:
- CSharp
- C++
- VB
---

# RecordId Property

Gets or sets the record identfier used by AX to reference the sales order line (used for customer orders).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ORDERLINERECID")> _
<DataMemberAttribute> _
Public Property RecordId As Long
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Long

value = instance.RecordId

instance.RecordId = value
```

``` csharp
[ColumnAttribute("ORDERLINERECID")]
[DataMemberAttribute]
public long RecordId { get; set; }
```

``` c++
[ColumnAttribute(L"ORDERLINERECID")]
[DataMemberAttribute]
public:
property long long RecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
