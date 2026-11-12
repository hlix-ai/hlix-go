# HostingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetWorkspaceHosting**](HostingAPI.md#getworkspacehosting) | **Get** /v1/api/settings/hosting | Read the workspace&#39;s immutable hosting region
[**ListHostingRegions**](HostingAPI.md#listhostingregions) | **Get** /v1/api/hosting-regions | List configured regional entry points



## GetWorkspaceHosting

> WorkspaceHosting GetWorkspaceHosting(ctx).XOrganizationId(xOrganizationId).Execute()

Read the workspace's immutable hosting region

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
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HostingAPI.GetWorkspaceHosting(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HostingAPI.GetWorkspaceHosting``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceHosting`: WorkspaceHosting
	fmt.Fprintf(os.Stdout, "Response from `HostingAPI.GetWorkspaceHosting`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetWorkspaceHostingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceHosting**](WorkspaceHosting.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHostingRegions

> HostingCatalog ListHostingRegions(ctx).Execute()

List configured regional entry points

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HostingAPI.ListHostingRegions(ctx).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HostingAPI.ListHostingRegions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHostingRegions`: HostingCatalog
	fmt.Fprintf(os.Stdout, "Response from `HostingAPI.ListHostingRegions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Pass optional parameters through the `apiListHostingRegionsRequest` request builder.


### Return type

[**HostingCatalog**](HostingCatalog.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

