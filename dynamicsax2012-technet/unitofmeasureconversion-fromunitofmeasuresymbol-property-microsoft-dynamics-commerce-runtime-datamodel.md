﻿---
title: UnitOfMeasureConversion.FromUnitOfMeasureSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromUnitOfMeasureSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.FromUnitOfMeasureSymbol
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.fromunitofmeasuresymbol(v=AX.60)
ms:contentKeyID: 62213779
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.FromUnitOfMeasureSymbol
dev_langs:
- CSharp
- C++
- VB
---

# FromUnitOfMeasureSymbol Property

Gets or sets the unit of measure symbol to convert from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FROMUOMSYMBOL")> _
<ReadOnlyAttribute("FROMUOMSYMBOL")> _
Public Property FromUnitOfMeasureSymbol As String
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As String

value = instance.FromUnitOfMeasureSymbol

instance.FromUnitOfMeasureSymbol = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FROMUOMSYMBOL")]
[ReadOnlyAttribute("FROMUOMSYMBOL")]
public string FromUnitOfMeasureSymbol { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FROMUOMSYMBOL")]
[ReadOnlyAttribute(L"FROMUOMSYMBOL")]
public:
property String^ FromUnitOfMeasureSymbol {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
