---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let contactFolders = await client.api('/me/contactFolders')
	.version('beta')
	.get();

```