---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestBody := msgraphsdk.NewPlannerBucket()
name := "Advertising"
requestBody.SetName(&name)
planId := "xqQg5FS2LkCp935s-FIFm2QAFkHM"
requestBody.SetPlanId(&planId)
orderHint := " !"
requestBody.SetOrderHint(&orderHint)
options := &msgraphsdk.BucketsRequestBuilderPostOptions{
	Body: requestBody,
}
result, err := graphClient.Planner().Buckets().Post(options)


```