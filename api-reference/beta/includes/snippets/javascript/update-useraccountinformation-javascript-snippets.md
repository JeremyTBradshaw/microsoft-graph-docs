---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const userAccountInformation = {
  countryCode: 'NO'
};

await client.api('/me/profile/account/{id}')
	.version('beta')
	.update(userAccountInformation);

```