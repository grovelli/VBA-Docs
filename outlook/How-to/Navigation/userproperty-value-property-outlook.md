---
title: UserProperty.Value Property (Outlook)
keywords: vbaol11.chm222
f1_keywords:
- vbaol11.chm222
ms.prod: outlook
api_name:
- Outlook.UserProperty.Value
ms.assetid: 9f313262-ffd4-3245-f516-bc2d62d6f33a
ms.date: 06/08/2017
---


# UserProperty.Value Property (Outlook)

Returns or sets a  **Variant** indicating the value for the specified custom property. Read/write.


## Syntax

 _expression_ . **Value**

 _expression_ A variable that represents a **UserProperty** object.


## Remarks

To set for the first time a property created by the  **[UserProperties.Add](userproperties-add-method-outlook.md)** method, use the **UserProperty.Value** property instead of the **[SetProperties](propertyaccessor-setproperties-method-outlook.md)** or **[SetProperty](../../../api/Outlook.PropertyAccessor.SetProperty.md)** method of the **[PropertyAccessor](../../../api/Outlook.PropertyAccessor.md)** object.

For more information on accessing properties in Outlook, see [Properties Overview](./properties-overview.md).


## See also


#### Concepts


[UserProperty Object](../../../api/Outlook.UserProperty.md)
