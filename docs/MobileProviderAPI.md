# \MobileProviderAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMobileProvider**](MobileProviderAPI.md#GetMobileProvider) | **Get** /v1/api/mobile-provider | Read mobile emulators and devices billing configuration
[**RemoveMobileProviderKey**](MobileProviderAPI.md#RemoveMobileProviderKey) | **Delete** /v1/api/mobile-provider/key | Remove the key for new builds; existing resources retain their cleanup credentials
[**SaveMobileProviderKey**](MobileProviderAPI.md#SaveMobileProviderKey) | **Put** /v1/api/mobile-provider/key | Verify and save a workspace Limrun key for new builds
[**TestMobileProviderKey**](MobileProviderAPI.md#TestMobileProviderKey) | **Post** /v1/api/mobile-provider/test | Check a supplied or saved Limrun key without allocating a device
[**ToggleMobileProvider**](MobileProviderAPI.md#ToggleMobileProvider) | **Patch** /v1/api/mobile-provider | Choose workspace or Hlix funding for new mobile builds



## GetMobileProvider

> MobileProviderState GetMobileProvider(ctx).XOrganizationId(xOrganizationId).Execute()

Read mobile emulators and devices billing configuration

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
	resp, r, err := apiClient.MobileProviderAPI.GetMobileProvider(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MobileProviderAPI.GetMobileProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMobileProvider`: MobileProviderState
	fmt.Fprintf(os.Stdout, "Response from `MobileProviderAPI.GetMobileProvider`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMobileProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileProviderState**](MobileProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveMobileProviderKey

> MobileProviderState RemoveMobileProviderKey(ctx).XOrganizationId(xOrganizationId).Execute()

Remove the key for new builds; existing resources retain their cleanup credentials

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
	resp, r, err := apiClient.MobileProviderAPI.RemoveMobileProviderKey(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MobileProviderAPI.RemoveMobileProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveMobileProviderKey`: MobileProviderState
	fmt.Fprintf(os.Stdout, "Response from `MobileProviderAPI.RemoveMobileProviderKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRemoveMobileProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileProviderState**](MobileProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveMobileProviderKey

> MobileProviderState SaveMobileProviderKey(ctx).SaveMobileProviderKey(saveMobileProviderKey).XOrganizationId(xOrganizationId).Execute()

Verify and save a workspace Limrun key for new builds

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
	saveMobileProviderKey := *openapiclient.NewSaveMobileProviderKey("ApiKey_example") // SaveMobileProviderKey | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MobileProviderAPI.SaveMobileProviderKey(context.Background()).SaveMobileProviderKey(saveMobileProviderKey).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MobileProviderAPI.SaveMobileProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveMobileProviderKey`: MobileProviderState
	fmt.Fprintf(os.Stdout, "Response from `MobileProviderAPI.SaveMobileProviderKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaveMobileProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveMobileProviderKey** | [**SaveMobileProviderKey**](SaveMobileProviderKey.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileProviderState**](MobileProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestMobileProviderKey

> MobileProviderTest TestMobileProviderKey(ctx).TestMobileProviderKey(testMobileProviderKey).XOrganizationId(xOrganizationId).Execute()

Check a supplied or saved Limrun key without allocating a device

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
	testMobileProviderKey := *openapiclient.NewTestMobileProviderKey() // TestMobileProviderKey | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MobileProviderAPI.TestMobileProviderKey(context.Background()).TestMobileProviderKey(testMobileProviderKey).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MobileProviderAPI.TestMobileProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestMobileProviderKey`: MobileProviderTest
	fmt.Fprintf(os.Stdout, "Response from `MobileProviderAPI.TestMobileProviderKey`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTestMobileProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **testMobileProviderKey** | [**TestMobileProviderKey**](TestMobileProviderKey.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileProviderTest**](MobileProviderTest.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ToggleMobileProvider

> MobileProviderState ToggleMobileProvider(ctx).ToggleMobileProvider(toggleMobileProvider).XOrganizationId(xOrganizationId).Execute()

Choose workspace or Hlix funding for new mobile builds

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
	toggleMobileProvider := *openapiclient.NewToggleMobileProvider(false) // ToggleMobileProvider | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MobileProviderAPI.ToggleMobileProvider(context.Background()).ToggleMobileProvider(toggleMobileProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MobileProviderAPI.ToggleMobileProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ToggleMobileProvider`: MobileProviderState
	fmt.Fprintf(os.Stdout, "Response from `MobileProviderAPI.ToggleMobileProvider`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiToggleMobileProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **toggleMobileProvider** | [**ToggleMobileProvider**](ToggleMobileProvider.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileProviderState**](MobileProviderState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

