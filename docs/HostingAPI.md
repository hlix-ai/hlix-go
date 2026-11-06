# \HostingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetWorkspaceHosting**](HostingAPI.md#GetWorkspaceHosting) | **Get** /v1/api/settings/hosting | Read the workspace&#39;s immutable hosting region
[**ListHostingRegions**](HostingAPI.md#ListHostingRegions) | **Get** /v1/api/hosting-regions | List configured regional entry points



## GetWorkspaceHosting

> WorkspaceHosting GetWorkspaceHosting(ctx).XOrganizationId(xOrganizationId).Execute()

Read the workspace's immutable hosting region

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HostingAPI.GetWorkspaceHosting(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetWorkspaceHostingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceHosting**](WorkspaceHosting.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HostingAPI.ListHostingRegions(context.Background()).Execute()
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

Other parameters are passed through a pointer to a apiListHostingRegionsRequest struct via the builder pattern


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

