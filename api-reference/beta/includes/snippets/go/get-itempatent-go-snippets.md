---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

itemPatentId := "itemPatent-id"
result, err := graphClient.Me().Profile().PatentsById(&itemPatentId).Get(options)


```