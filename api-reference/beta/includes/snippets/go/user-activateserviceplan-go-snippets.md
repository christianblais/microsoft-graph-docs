---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestBody := msgraphsdk.New()
servicePlanId := "28f42d6f-8034-4a0f-9d8a-a218a63b3299"
requestBody.SetServicePlanId(&servicePlanId)
skuId := "465a2a90-5e59-456d-a7b8-127b9fb2e484"
requestBody.SetSkuId(&skuId)
options := &msgraphsdk.ActivateServicePlanRequestBuilderPostOptions{
	Body: requestBody,
}
graphClient.Me().ActivateServicePlan().Post(options)


```