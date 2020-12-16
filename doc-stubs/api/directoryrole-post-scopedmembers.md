---
title: "Create scopedRoleMembership"
description: "Create a new scopedRoleMembership object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create scopedRoleMembership
Namespace: microsoft.graph

Create a new scopedRoleMembership object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
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
POST /directoryRoles/{directoryRolesId}/scopedMembers
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [scopedRoleMembership](../resources/scopedrolemembership.md) object.

The following table shows the properties that are required when you create the [scopedRoleMembership](../resources/scopedrolemembership.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|roleId|String|**TODO: Add Description**|
|administrativeUnitId|String|**TODO: Add Description**|
|roleMemberInfo|[identity](../resources/identity.md)|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [scopedRoleMembership](../resources/scopedrolemembership.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_scopedrolemembership_from_scopedrolememberships"
}
-->
``` http
POST https://graph.microsoft.com/beta/directoryRoles/{directoryRolesId}/scopedMembers
Content-Type: application/json
Content-length: 210

{
  "@odata.type": "#Microsoft.DirectoryServices.scopedRoleMembership",
  "roleId": "String",
  "administrativeUnitId": "String",
  "roleMemberInfo": {
    "@odata.type": "microsoft.graph.identity"
  }
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.DirectoryServices.scopedRoleMembership"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.DirectoryServices.scopedRoleMembership",
  "id": "1c254686-4686-1c25-8646-251c8646251c",
  "roleId": "String",
  "administrativeUnitId": "String",
  "roleMemberInfo": {
    "@odata.type": "microsoft.graph.identity"
  }
}
```
