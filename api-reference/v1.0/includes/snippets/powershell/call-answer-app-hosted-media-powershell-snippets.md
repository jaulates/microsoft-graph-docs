---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.CloudCommunications

$params = @{
	CallbackUri = "https://bot.contoso.com/api/calls"
	AcceptedModalities = @(
		"audio"
	)
	MediaConfig = @{
		"@odata.type" = "#microsoft.graph.appHostedMediaConfig"
		Blob = "<Media Session Configuration Blob>"
	}
}

Invoke-MgAnswerCommunicationCall -CallId $callId -BodyParameter $params

```