---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

GraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

InputStream stream = graphClient.appCatalogs().teamsApps("5a31d4f7-a11d-4052-96eb-1b40786a2a78").appDefinitions("NWEzMWQ0ZjctYTExZC00MDUyLTk2ZWItMWI0MDc4NmEyYTc4IyM2LjAuNSMjUHVibGlzaGVk").outlineIcon().hostedContent().content()
	.buildRequest()
	.get();

```