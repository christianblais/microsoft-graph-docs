---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter);

requestBody := msgraphsdk.New()
memberId := "319b41e8-d9e4-42f8-bdc9-741113f48b33"
requestBody.SetMemberId(&memberId)
membershipRule := "(user.displayName -startsWith "EndTestUser")"
requestBody.SetMembershipRule(&membershipRule)
options := &msgraphsdk.EvaluateDynamicMembershipRequestBuilderPostOptions{
	Body: requestBody,
}
result, err := graphClient.Groups().EvaluateDynamicMembership().Post(options)


```