---
title: "Update urlFilteringPolicy"
description: "Update the properties of an urlFilteringPolicy object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update urlFilteringPolicy
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Update the properties of an [urlFilteringPolicy](../resources/urlfilteringpolicy.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
[!INCLUDE [table-intro](../../includes/update-property-table-intro.md)]


|Property|Type|Description|
|:---|:---|:---|
|name|String|**TODO: Add Description** Inherited from [configurationBase](../resources/configurationbase.md). Optional.|
|description|String|**TODO: Add Description** Inherited from [configurationBase](../resources/configurationbase.md). Optional.|
|priority|Int64|**TODO: Add Description** Inherited from [childFilteringPolicyBase](../resources/childfilteringpolicybase.md). Required.|
|action|filteringPolicyAction|**TODO: Add Description** Inherited from [childFilteringPolicyBase](../resources/childfilteringpolicybase.md). The possible values are: `block`, `allow`, `alert`, `redirect`. Required.|
|state|enablementState|**TODO: Add Description** Inherited from [childFilteringPolicyBase](../resources/childfilteringpolicybase.md). The possible values are: `enabled`, `disabled`. Required.|
|loggingState|enablementState|**TODO: Add Description** Inherited from [childFilteringPolicyBase](../resources/childfilteringpolicybase.md). The possible values are: `enabled`, `disabled`. Required.|



## Response

If successful, this method returns a `200 OK` response code and an updated [urlFilteringPolicy](../resources/urlfilteringpolicy.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_urlfilteringpolicy"
}
-->
``` http

```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.urlFilteringPolicy",
  "id": "33bc6f86-6f86-33bc-866f-bc33866fbc33",
  "name": "String",
  "description": "String",
  "priority": "Integer",
  "action": "String",
  "state": "String",
  "loggingState": "String"
}
```
