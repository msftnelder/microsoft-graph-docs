---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

teamId := "team-id"
timeOffId := "timeOff-id"
result, err := graphClient.TeamsById(&teamId).Schedule().TimesOffById(&timeOffId).Get(options)


```