﻿---
title: TraceInfo.Message Property  (Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TraceInfo.Message
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflowfoundation.activities.traceinfo.message(v=AX.60)
ms:contentKeyID: 65323056
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.TraceInfo.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property

Gets or sets message to trace argument.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities (in Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities.dll)

## Syntax

``` vb
'Declaration
Public Property Message As InArgument(Of String)
    Get
    Set
'Usage
Dim instance As TraceInfo
Dim value As InArgument(Of String)

value = instance.Message

instance.Message = value
```

``` csharp
public InArgument<string> Message { get; set; }
```

``` c++
public:
property InArgument<String^>^ Message {
    InArgument<String^>^ get ();
    void set (InArgument<String^>^ value);
}
```

#### Property Value

Type: InArgument\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns InArgument.  

## See Also

#### Reference

[TraceInfo Class](traceinfo-class-microsoft-dynamics-commerce-runtime-workflowfoundation-activities.md)

[Microsoft.Dynamics.Commerce.Runtime.WorkflowFoundation.Activities Namespace](microsoft-dynamics-commerce-runtime-workflowfoundation-activities-namespace.md)

