---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

await client.api('/sites/{sitesId}/permissions/{permissionId}')
	.version('beta')
	.delete();

```