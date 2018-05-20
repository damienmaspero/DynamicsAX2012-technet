﻿---
title: StoreProductAvailabilityItem.InventoryLocationId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: InventoryLocationId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityItem.InventoryLocationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeproductavailabilityitem.inventorylocationid(v=AX.60)
ms:contentKeyID: 62206672
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailabilityItem.InventoryLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLocationId Property

Gets or sets the inventory location ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryLocationId As String
    Get
    Set
'Usage
Dim instance As StoreProductAvailabilityItem
Dim value As String

value = instance.InventoryLocationId

instance.InventoryLocationId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryLocationId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The inventory location ID.  

## See Also

#### Reference

[StoreProductAvailabilityItem Class](storeproductavailabilityitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)
