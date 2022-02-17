---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Identity.Governance

$params = @{
	CatalogId = "de9315c1-272b-4905-924b-cc112ca180c7"
	AccessPackageResource = @{
		DisplayName = "Community Outreach"
		Description = "https://contoso.sharepoint.com/sites/CSR"
		ResourceType = "SharePoint Online Site"
		OriginId = "https://contoso.sharepoint.com/sites/CSR"
		OriginSystem = "SharePointOnline"
		"AccessPackageResourceEnvironment@odata.bind" = "accessPackageResourceEnvironments/615f2218-678f-471f-a60a-02c2f4f80c57"
	}
	RequestType = "AdminAdd"
}

New-MgEntitlementManagementAccessPackageResourceRequest -BodyParameter $params

```