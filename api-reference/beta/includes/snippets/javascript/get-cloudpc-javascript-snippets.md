---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let cloudPC = await client.api('/deviceManagement/virtualEndpoint/cloudPCs/{id}')
	.version('beta')
	.get();

```