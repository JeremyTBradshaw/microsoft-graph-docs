---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let privilegedApproval = await client.api('/privilegedApproval/{id}')
	.version('beta')
	.get();

```