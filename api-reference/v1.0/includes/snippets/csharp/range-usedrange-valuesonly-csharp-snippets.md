---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var workbookRange = await graphClient.Me.Drive.Items["{driveItem-id}"].Workbook.Names["{workbookNamedItem-id}"]
	.Range()
	.UsedRange(true)
	.Request()
	.GetAsync();

```