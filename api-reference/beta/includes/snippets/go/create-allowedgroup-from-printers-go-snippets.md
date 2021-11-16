---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestBody := msgraphsdk.New()
requestBody.SetAdditionalData(map[string]interface{}{
	"@odata.id": "https://graph.microsoft.com/beta/groups/{id}",
}
options := &msgraphsdk.RefRequestBuilderPostOptions{
	Body: requestBody,
}
printerShareId := "printerShare-id"
result, err := graphClient.Print().SharesById(&printerShareId).AllowedGroups().$ref().Post(options)


```