---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestParameters := &msgraphsdk.ServiceHealthRequestBuilderGetQueryParameters{
	Expand: "issues",
}
options := &msgraphsdk.ServiceHealthRequestBuilderGetOptions{
	Q: requestParameters,
}
serviceHealthId := "serviceHealth-id"
result, err := graphClient.Admin().ServiceAnnouncement().HealthOverviewsById(&serviceHealthId).Get(options)


```