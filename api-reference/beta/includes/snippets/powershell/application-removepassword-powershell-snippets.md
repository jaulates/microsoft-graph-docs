---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Applications

$params = @{
	KeyId = "f0b0b335-1d71-4883-8f98-567911bfdca6"
}

Remove-MgApplicationPassword -ApplicationId $applicationId -BodyParameter $params

```