---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

itemPhoneId := "itemPhone-id"
result, err := graphClient.Me().Profile().PhonesById(&itemPhoneId).Get(options)


```