---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var educationAssignmentResource = await graphClient.Education.Classes["{educationClass-id}"].Assignments["{educationAssignment-id}"].Resources["{educationAssignmentResource-id}"]
	.Request()
	.GetAsync();

```