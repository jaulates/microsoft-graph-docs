---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

$params = @{
	DisplayName = "displayName-value"
	IsHidden = $true
}

New-MgUserMailFolderChildFolder -UserId $userId -MailFolderId $mailFolderId -BodyParameter $params

```