---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const transfer = {
  transferTarget: {
    '@odata.type': '#microsoft.graph.invitationParticipantInfo',
    endpointType: 'default',
    identity: {
      '@odata.type': '#microsoft.graph.identitySet',
      user: {
        '@odata.type': '#microsoft.graph.identity',
        id: '550fae72-d251-43ec-868c-373732c2704f',
        displayName: 'Heidi Steen'
      }
    },
    replacesCallId: 'e5d39592-99bd-4db8-bca8-30fb894ec51d'
  }
};

await client.api('/communications/calls/341a0500-d4bf-4224-8b19-1581168d328b/transfer')
	.post(transfer);

```