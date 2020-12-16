---
title: "user: reprocessLicenseAssignment"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# user: reprocessLicenseAssignment
Namespace: microsoft.graph

**TODO: Add Description**

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
POST /me/reprocessLicenseAssignment
POST /users/{usersId}/reprocessLicenseAssignment
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this action returns a `200 OK` response code and a [user](../resources/user.md) in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "user_reprocesslicenseassignment"
}
-->
``` http
POST https://graph.microsoft.com/beta/me/reprocessLicenseAssignment
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.DirectoryServices.user"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#Microsoft.DirectoryServices.user",
    "id": "String (identifier)",
    "deletedDateTime": "String (timestamp)",
    "accountEnabled": "Boolean",
    "ageGroup": "String",
    "assignedLicenses": [
      {
        "@odata.type": "microsoft.graph.assignedLicense"
      }
    ],
    "assignedPlans": [
      {
        "@odata.type": "microsoft.graph.assignedPlan"
      }
    ],
    "businessPhones": [
      "String"
    ],
    "city": "String",
    "companyName": "String",
    "consentProvidedForMinor": "String",
    "country": "String",
    "createdDateTime": "String (timestamp)",
    "creationType": "String",
    "department": "String",
    "deviceKeys": [
      {
        "@odata.type": "microsoft.graph.deviceKey"
      }
    ],
    "displayName": "String",
    "employeeHireDate": "String (timestamp)",
    "employeeId": "String",
    "employeeOrgData": {
      "@odata.type": "microsoft.graph.employeeOrgData"
    },
    "employeeType": "String",
    "faxNumber": "String",
    "givenName": "String",
    "identities": [
      {
        "@odata.type": "microsoft.graph.objectIdentity"
      }
    ],
    "imAddresses": [
      "String"
    ],
    "infoCatalogs": [
      "String"
    ],
    "isResourceAccount": "Boolean",
    "jobTitle": "String",
    "lastPasswordChangeDateTime": "String (timestamp)",
    "legalAgeGroupClassification": "String",
    "licenseAssignmentStates": [
      {
        "@odata.type": "microsoft.graph.licenseAssignmentState"
      }
    ],
    "mail": "String",
    "mailNickname": "String",
    "mobilePhone": "String",
    "onPremisesDistinguishedName": "String",
    "onPremisesExtensionAttributes": {
      "@odata.type": "microsoft.graph.onPremisesExtensionAttributes"
    },
    "onPremisesImmutableId": "String",
    "onPremisesLastSyncDateTime": "String (timestamp)",
    "onPremisesProvisioningErrors": [
      {
        "@odata.type": "microsoft.graph.onPremisesProvisioningError"
      }
    ],
    "onPremisesSecurityIdentifier": "String",
    "onPremisesSyncEnabled": "Boolean",
    "onPremisesDomainName": "String",
    "onPremisesSamAccountName": "String",
    "onPremisesUserPrincipalName": "String",
    "otherMails": [
      "String"
    ],
    "passwordPolicies": "String",
    "passwordProfile": {
      "@odata.type": "microsoft.graph.passwordProfile"
    },
    "officeLocation": "String",
    "postalCode": "String",
    "preferredDataLocation": "String",
    "preferredLanguage": "String",
    "provisionedPlans": [
      {
        "@odata.type": "microsoft.graph.provisionedPlan"
      }
    ],
    "proxyAddresses": [
      "String"
    ],
    "refreshTokensValidFromDateTime": "String (timestamp)",
    "showInAddressList": "Boolean",
    "signInSessionsValidFromDateTime": "String (timestamp)",
    "state": "String",
    "streetAddress": "String",
    "surname": "String",
    "usageLocation": "String",
    "userPrincipalName": "String",
    "externalUserState": "String",
    "externalUserStateChangeDateTime": "String",
    "userType": "String"
  }
}
```
