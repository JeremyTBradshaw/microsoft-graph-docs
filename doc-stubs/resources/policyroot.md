---
title: "policyRoot resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# policyRoot resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List policyRoots](../api/policyroot-list.md)|[policyRoot](../resources/policyroot.md) collection|Get a list of the [policyRoot](../resources/policyroot.md) objects and their properties.|
|[Create policyRoot](../api/policyroot-create.md)|[policyRoot](../resources/policyroot.md)|Create a new [policyRoot](../resources/policyroot.md) object.|
|[Get policyRoot](../api/policyroot-get.md)|[policyRoot](../resources/policyroot.md)|Read the properties and relationships of a [policyRoot](../resources/policyroot.md) object.|
|[Update policyRoot](../api/policyroot-update.md)|[policyRoot](../resources/policyroot.md)|Update the properties of a [policyRoot](../resources/policyroot.md) object.|
|[Delete policyRoot](../api/policyroot-delete.md)|None|Deletes a [policyRoot](../resources/policyroot.md) object.|
|[List activityBasedTimeoutPolicies](../api/policyroot-list-activitybasedtimeoutpolicies.md)|[activityBasedTimeoutPolicy](../resources/activitybasedtimeoutpolicy.md) collection|Get the activityBasedTimeoutPolicy resources from the activityBasedTimeoutPolicies navigation property.|
|[Create activityBasedTimeoutPolicy](../api/policyroot-post-activitybasedtimeoutpolicies.md)|[activityBasedTimeoutPolicy](../resources/activitybasedtimeoutpolicy.md)|Create a new activityBasedTimeoutPolicy object.|
|[List authorizationPolicy](../api/policyroot-list-authorizationpolicy.md)|[authorizationPolicy](../resources/authorizationpolicy.md) collection|Get the authorizationPolicy resources from the authorizationPolicy navigation property.|
|[Create authorizationPolicy](../api/policyroot-post-authorizationpolicy.md)|[authorizationPolicy](../resources/authorizationpolicy.md)|Create a new authorizationPolicy object.|
|[List claimsMappingPolicies](../api/policyroot-list-claimsmappingpolicies.md)|[claimsMappingPolicy](../resources/claimsmappingpolicy.md) collection|Get the claimsMappingPolicy resources from the claimsMappingPolicies navigation property.|
|[Create claimsMappingPolicy](../api/policyroot-post-claimsmappingpolicies.md)|[claimsMappingPolicy](../resources/claimsmappingpolicy.md)|Create a new claimsMappingPolicy object.|
|[List homeRealmDiscoveryPolicies](../api/policyroot-list-homerealmdiscoverypolicies.md)|[homeRealmDiscoveryPolicy](../resources/homerealmdiscoverypolicy.md) collection|Get the homeRealmDiscoveryPolicy resources from the homeRealmDiscoveryPolicies navigation property.|
|[Create homeRealmDiscoveryPolicy](../api/policyroot-post-homerealmdiscoverypolicies.md)|[homeRealmDiscoveryPolicy](../resources/homerealmdiscoverypolicy.md)|Create a new homeRealmDiscoveryPolicy object.|
|[List permissionGrantPolicies](../api/policyroot-list-permissiongrantpolicies.md)|[permissionGrantPolicy](../resources/permissiongrantpolicy.md) collection|Get the permissionGrantPolicy resources from the permissionGrantPolicies navigation property.|
|[Create permissionGrantPolicy](../api/policyroot-post-permissiongrantpolicies.md)|[permissionGrantPolicy](../resources/permissiongrantpolicy.md)|Create a new permissionGrantPolicy object.|
|[List privateLinkResourcePolicies](../api/policyroot-list-privatelinkresourcepolicies.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) collection|Get the privateLinkResourcePolicy resources from the privateLinkResourcePolicies navigation property.|
|[Create privateLinkResourcePolicy](../api/policyroot-post-privatelinkresourcepolicies.md)|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md)|Create a new privateLinkResourcePolicy object.|
|[List tokenIssuancePolicies](../api/policyroot-list-tokenissuancepolicies.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md) collection|Get the tokenIssuancePolicy resources from the tokenIssuancePolicies navigation property.|
|[Create tokenIssuancePolicy](../api/policyroot-post-tokenissuancepolicies.md)|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md)|Create a new tokenIssuancePolicy object.|
|[List tokenLifetimePolicies](../api/policyroot-list-tokenlifetimepolicies.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) collection|Get the tokenLifetimePolicy resources from the tokenLifetimePolicies navigation property.|
|[Create tokenLifetimePolicy](../api/policyroot-post-tokenlifetimepolicies.md)|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md)|Create a new tokenLifetimePolicy object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|activityBasedTimeoutPolicies|[activityBasedTimeoutPolicy](../resources/activitybasedtimeoutpolicy.md) collection|**TODO: Add Description**|
|authorizationPolicy|[authorizationPolicy](../resources/authorizationpolicy.md) collection|**TODO: Add Description**|
|claimsMappingPolicies|[claimsMappingPolicy](../resources/claimsmappingpolicy.md) collection|**TODO: Add Description**|
|homeRealmDiscoveryPolicies|[homeRealmDiscoveryPolicy](../resources/homerealmdiscoverypolicy.md) collection|**TODO: Add Description**|
|permissionGrantPolicies|[permissionGrantPolicy](../resources/permissiongrantpolicy.md) collection|**TODO: Add Description**|
|privateLinkResourcePolicies|[privateLinkResourcePolicy](../resources/privatelinkresourcepolicy.md) collection|**TODO: Add Description**|
|tokenIssuancePolicies|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md) collection|**TODO: Add Description**|
|tokenLifetimePolicies|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.policyRoot",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.policyRoot"
}
```
