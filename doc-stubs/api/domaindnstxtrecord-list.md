---
title: "List domainDnsTxtRecords"
description: "Get a list of the domainDnsTxtRecord objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List domainDnsTxtRecords
Namespace: microsoft.graph

Get a list of the [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) objects and their properties.

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
GET ** Collection URI for Microsoft.DirectoryServices.domainDnsTxtRecord not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [domainDnsTxtRecord](../resources/domaindnstxtrecord.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_domaindnstxtrecord"
}
-->
``` http
GET https://graph.microsoft.com/beta** Collection URI for Microsoft.DirectoryServices.domainDnsTxtRecord not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.DirectoryServices.domainDnsTxtRecord)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.DirectoryServices.domainDnsTxtRecord",
      "id": "a3a7d774-d774-a3a7-74d7-a7a374d7a7a3",
      "isOptional": "Boolean",
      "label": "String",
      "recordType": "String",
      "supportedService": "String",
      "ttl": "Integer",
      "text": "String"
    }
  ]
}
```
