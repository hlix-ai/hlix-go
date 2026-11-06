# \WebProvidersAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetHlixCrawlStatus**](WebProvidersAPI.md#GetHlixCrawlStatus) | **Get** /v1/api/web-providers/crawl | Show hlix-crawl usage against the plan allowance
[**ListWebProviders**](WebProvidersAPI.md#ListWebProviders) | **Get** /v1/api/web-providers | List web-provider credential state
[**RemoveWebProviderKey**](WebProvidersAPI.md#RemoveWebProviderKey) | **Delete** /v1/api/web-providers/{provider}/key | Remove a stored web-provider key
[**SaveWebProviderKey**](WebProvidersAPI.md#SaveWebProviderKey) | **Put** /v1/api/web-providers/{provider}/key | Add or replace a web-provider key
[**ToggleHlixCrawl**](WebProvidersAPI.md#ToggleHlixCrawl) | **Patch** /v1/api/web-providers/crawl | Opt the workspace in or out of hlix-crawl
[**ToggleWebProvider**](WebProvidersAPI.md#ToggleWebProvider) | **Patch** /v1/api/web-providers/{provider} | Enable or disable a stored web-provider key



## GetHlixCrawlStatus

> HlixCrawlStatus GetHlixCrawlStatus(ctx).XOrganizationId(xOrganizationId).Execute()

Show hlix-crawl usage against the plan allowance

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
	resp, r, err := apiClient.WebProvidersAPI.GetHlixCrawlStatus(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.GetHlixCrawlStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHlixCrawlStatus`: HlixCrawlStatus
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.GetHlixCrawlStatus`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetHlixCrawlStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**HlixCrawlStatus**](HlixCrawlStatus.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWebProviders

> []WebProviderState ListWebProviders(ctx).XOrganizationId(xOrganizationId).Execute()

List web-provider credential state

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
	resp, r, err := apiClient.WebProvidersAPI.ListWebProviders(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.ListWebProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWebProviders`: []WebProviderState
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.ListWebProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListWebProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]WebProviderState**](WebProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveWebProviderKey

> WebProviderState RemoveWebProviderKey(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Remove a stored web-provider key

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
	provider := "provider_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebProvidersAPI.RemoveWebProviderKey(context.Background(), provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.RemoveWebProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveWebProviderKey`: WebProviderState
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.RemoveWebProviderKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveWebProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WebProviderState**](WebProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveWebProviderKey

> WebProviderState SaveWebProviderKey(ctx, provider).SaveWebProviderKey(saveWebProviderKey).XOrganizationId(xOrganizationId).Execute()

Add or replace a web-provider key

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
	provider := "provider_example" // string | 
	saveWebProviderKey := *openapiclient.NewSaveWebProviderKey("ApiKey_example") // SaveWebProviderKey | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebProvidersAPI.SaveWebProviderKey(context.Background(), provider).SaveWebProviderKey(saveWebProviderKey).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.SaveWebProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveWebProviderKey`: WebProviderState
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.SaveWebProviderKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaveWebProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **saveWebProviderKey** | [**SaveWebProviderKey**](SaveWebProviderKey.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WebProviderState**](WebProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ToggleHlixCrawl

> HlixCrawlStatus ToggleHlixCrawl(ctx).ToggleWebProvider(toggleWebProvider).XOrganizationId(xOrganizationId).Execute()

Opt the workspace in or out of hlix-crawl

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
	toggleWebProvider := *openapiclient.NewToggleWebProvider(false) // ToggleWebProvider | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebProvidersAPI.ToggleHlixCrawl(context.Background()).ToggleWebProvider(toggleWebProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.ToggleHlixCrawl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ToggleHlixCrawl`: HlixCrawlStatus
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.ToggleHlixCrawl`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiToggleHlixCrawlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **toggleWebProvider** | [**ToggleWebProvider**](ToggleWebProvider.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**HlixCrawlStatus**](HlixCrawlStatus.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ToggleWebProvider

> WebProviderState ToggleWebProvider(ctx, provider).ToggleWebProvider(toggleWebProvider).XOrganizationId(xOrganizationId).Execute()

Enable or disable a stored web-provider key

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
	provider := "provider_example" // string | 
	toggleWebProvider := *openapiclient.NewToggleWebProvider(false) // ToggleWebProvider | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebProvidersAPI.ToggleWebProvider(context.Background(), provider).ToggleWebProvider(toggleWebProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebProvidersAPI.ToggleWebProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ToggleWebProvider`: WebProviderState
	fmt.Fprintf(os.Stdout, "Response from `WebProvidersAPI.ToggleWebProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiToggleWebProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **toggleWebProvider** | [**ToggleWebProvider**](ToggleWebProvider.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WebProviderState**](WebProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

