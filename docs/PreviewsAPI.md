# PreviewsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPreviewSharing**](PreviewsAPI.md#getpreviewsharing) | **Get** /v1/api/previews/sharing | Get public preview sharing for a project
[**RebuildPreview**](PreviewsAPI.md#rebuildpreview) | **Post** /v1/api/previews | Rebuild a project&#39;s preview
[**SetPreviewSharing**](PreviewsAPI.md#setpreviewsharing) | **Put** /v1/api/previews/sharing | Enable or revoke public preview sharing



## GetPreviewSharing

> PreviewSharingSaved GetPreviewSharing(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()

Get public preview sharing for a project

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	projectId := "projectId_example" // string | The project whose preview sharing to read.
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PreviewsAPI.GetPreviewSharing(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PreviewsAPI.GetPreviewSharing``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPreviewSharing`: PreviewSharingSaved
	fmt.Fprintf(os.Stdout, "Response from `PreviewsAPI.GetPreviewSharing`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetPreviewSharingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | The project whose preview sharing to read. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PreviewSharingSaved**](PreviewSharingSaved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RebuildPreview

> DeploymentAccepted RebuildPreview(ctx).RebuildPreview(rebuildPreview).XOrganizationId(xOrganizationId).Execute()

Rebuild a project's preview

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	var rebuildPreview openapiclient.RebuildPreview
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\"}"), &rebuildPreview); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PreviewsAPI.RebuildPreview(ctx).RebuildPreview(rebuildPreview).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PreviewsAPI.RebuildPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RebuildPreview`: DeploymentAccepted
	fmt.Fprintf(os.Stdout, "Response from `PreviewsAPI.RebuildPreview`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiRebuildPreviewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **rebuildPreview** | [**RebuildPreview**](RebuildPreview.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeploymentAccepted**](DeploymentAccepted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPreviewSharing

> PreviewSharingSaved SetPreviewSharing(ctx).PreviewSharing(previewSharing).XOrganizationId(xOrganizationId).Execute()

Enable or revoke public preview sharing

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	var previewSharing openapiclient.PreviewSharing
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\",\"public\":true}"), &previewSharing); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PreviewsAPI.SetPreviewSharing(ctx).PreviewSharing(previewSharing).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PreviewsAPI.SetPreviewSharing``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPreviewSharing`: PreviewSharingSaved
	fmt.Fprintf(os.Stdout, "Response from `PreviewsAPI.SetPreviewSharing`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSetPreviewSharingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **previewSharing** | [**PreviewSharing**](PreviewSharing.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PreviewSharingSaved**](PreviewSharingSaved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

