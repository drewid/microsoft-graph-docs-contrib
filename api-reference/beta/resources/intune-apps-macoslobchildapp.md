---
title: "macOSLobChildApp resource type"
description: "Contains properties the MacOS LOB App in a bundle package"
author: "tfitzmac"
localization_priority: Normal
ms.prod: "intune"
---

# macOSLobChildApp resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Contains properties the MacOS LOB App in a bundle package
## Properties
|Property|Type|Description|
|:---|:---|:---|
|bundleId|String|The Identity Name.|
|buildNumber|String|The build number of MacOS Line of Business (LoB) app.|
|versionNumber|String|The version number of MacOS Line of Business (LoB) app.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.macOSLobChildApp"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSLobChildApp",
  "bundleId": "String",
  "buildNumber": "String",
  "versionNumber": "String"
}
```




