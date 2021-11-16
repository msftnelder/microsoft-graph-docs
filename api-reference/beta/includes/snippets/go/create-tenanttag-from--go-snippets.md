---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestBody := msgraphsdk.NewTenantTag()
displayName := "Support"
requestBody.SetDisplayName(&displayName)
description := "Tenants that have purchased extended support"
requestBody.SetDescription(&description)
options := &msgraphsdk.TenantTagsRequestBuilderPostOptions{
	Body: requestBody,
}
result, err := graphClient.TenantRelationships().ManagedTenants().TenantTags().Post(options)


```