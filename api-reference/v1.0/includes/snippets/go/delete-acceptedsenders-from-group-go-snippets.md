---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestParameters := &msgraphsdk.RefRequestBuilderDeleteQueryParameters{
	Id: "https://graph.microsoft.com/v1.0/users/%7Buser-id%7D",
}
options := &msgraphsdk.RefRequestBuilderDeleteOptions{
	Q: requestParameters,
}
groupId := "group-id"
graphClient.GroupsById(&groupId).AcceptedSenders().$ref().Delete(options)


```