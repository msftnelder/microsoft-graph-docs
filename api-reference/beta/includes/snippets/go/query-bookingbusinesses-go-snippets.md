---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestParameters := &msgraphsdk.BookingBusinessesRequestBuilderGetQueryParameters{
	Query: "Adventure",
}
options := &msgraphsdk.BookingBusinessesRequestBuilderGetOptions{
	Q: requestParameters,
}
result, err := graphClient.BookingBusinesses().Get(options)


```