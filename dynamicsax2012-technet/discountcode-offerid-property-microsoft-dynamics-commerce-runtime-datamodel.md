﻿---
title: DiscountCode.OfferId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.OfferId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountcode.offerid(v=AX.60)
ms:contentKeyID: 49843490
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode.OfferId
dev_langs:
- CSharp
- C++
- VB
---

# OfferId Property

Gets or sets the identifier of the discount offer that is activated by the discount code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISCOUNTOFFERID")> _
Public Property OfferId As String
    Get
    Set
'Usage
Dim instance As DiscountCode
Dim value As String

value = instance.OfferId

instance.OfferId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISCOUNTOFFERID")]
public string OfferId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISCOUNTOFFERID")]
public:
property String^ OfferId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DiscountCode Class](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
