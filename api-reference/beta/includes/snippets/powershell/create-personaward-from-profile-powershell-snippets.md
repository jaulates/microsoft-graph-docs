---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.People

$params = @{
	Description = "Lifetime Achievement award from the International Association of Branding Managers"
	DisplayName = "Lifetime Achievement Award For Excellence in Branding"
	IssuedDate = "Date"
	IssuingAuthority = "International Association of Branding Management"
	ThumbnailUrl = "https://iabm.io/sdhdfhsdhshsd.jpg"
	WebUrl = "https://www.iabm.io"
}

# A UPN can also be used as -UserId.
New-MgUserProfileAward -UserId $userId -BodyParameter $params

```