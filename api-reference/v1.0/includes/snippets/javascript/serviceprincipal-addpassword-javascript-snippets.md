---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const passwordCredential = {
  passwordCredential: {
    displayName: 'Password friendly name'
  }
};

await client.api('/servicePrincipals/{id}/addPassword')
	.post(passwordCredential);

```