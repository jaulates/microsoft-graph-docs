---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Security

$params = @{
	Value = @(
		@{
			Id = "c6fb948b-89c5-3bba-a2cd-a9d9a1e430e4"
			AdditionalInformation = "mytest"
		}
		@{
			Id = "e58c072b-c9bb-a5c4-34ce-eb69af44fb1e"
			AdditionalInformation = "test again"
		}
	)
}

Update-MgSecurityTiIndicatorMultiple -BodyParameter $params

```