---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let delta = await client.api('/users/delta')
	.version('beta')
	.header('Prefer','return=minimal')
	.select('displayName,jobTitle,mobilePhone')
	.get();

```