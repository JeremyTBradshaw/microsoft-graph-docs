---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Users["{user-id}"].Authentication.EmailMethods["{emailAuthenticationMethod-id}"]
	.Request()
	.DeleteAsync();

```