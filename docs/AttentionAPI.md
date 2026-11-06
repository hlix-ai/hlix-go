# \AttentionAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAttentionInbox**](AttentionAPI.md#GetAttentionInbox) | **Get** /v1/api/attention | Get the operator attention inbox



## GetAttentionInbox

> AttentionSummary GetAttentionInbox(ctx).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

Get the operator attention inbox

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	limit := "limit_example" // string | Page size, clamped to 1–500; 100 when omitted or not an integer. (optional)
	offset := "offset_example" // string | Items to skip, most urgent kind first and newest first within a kind. `total` and `countsByKind` count every item, so they say how many pages there are. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AttentionAPI.GetAttentionInbox(context.Background()).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AttentionAPI.GetAttentionInbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAttentionInbox`: AttentionSummary
	fmt.Fprintf(os.Stdout, "Response from `AttentionAPI.GetAttentionInbox`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAttentionInboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | Page size, clamped to 1–500; 100 when omitted or not an integer. | 
 **offset** | **string** | Items to skip, most urgent kind first and newest first within a kind. &#x60;total&#x60; and &#x60;countsByKind&#x60; count every item, so they say how many pages there are. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AttentionSummary**](AttentionSummary.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

