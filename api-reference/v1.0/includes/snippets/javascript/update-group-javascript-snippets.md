---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const group = {
  description: 'description-value',
  displayName: 'displayName-value',
  groupTypes: [
    'groupTypes-value'
  ],
  mail: 'mail-value',
  mailEnabled: true,
  mailNickname: 'mailNickname-value'
};

await client.api('/groups/{id}')
	.update(group);

```