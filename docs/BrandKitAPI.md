# \BrandKitAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ExtractWorkspaceBrandKit**](BrandKitAPI.md#ExtractWorkspaceBrandKit) | **Post** /v1/api/brand-kit/extract | Extract a draft brand from one website URL
[**GetWorkspaceBrandKit**](BrandKitAPI.md#GetWorkspaceBrandKit) | **Get** /v1/api/brand-kit | Read workspace brand settings
[**PublishWorkspaceBrandKit**](BrandKitAPI.md#PublishWorkspaceBrandKit) | **Post** /v1/api/brand-kit/publish | Publish a reviewed brand and portal
[**SaveWorkspaceBrandKit**](BrandKitAPI.md#SaveWorkspaceBrandKit) | **Put** /v1/api/brand-kit | Save a brand draft



## ExtractWorkspaceBrandKit

> WorkspaceBrandKitState ExtractWorkspaceBrandKit(ctx).ExtractBrandKit(extractBrandKit).XOrganizationId(xOrganizationId).Execute()

Extract a draft brand from one website URL

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
	extractBrandKit := *openapiclient.NewExtractBrandKit("Url_example") // ExtractBrandKit | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.ExtractWorkspaceBrandKit(context.Background()).ExtractBrandKit(extractBrandKit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.ExtractWorkspaceBrandKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExtractWorkspaceBrandKit`: WorkspaceBrandKitState
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.ExtractWorkspaceBrandKit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiExtractWorkspaceBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **extractBrandKit** | [**ExtractBrandKit**](ExtractBrandKit.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspaceBrandKit

> WorkspaceBrandKitState GetWorkspaceBrandKit(ctx).XOrganizationId(xOrganizationId).Execute()

Read workspace brand settings

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
	resp, r, err := apiClient.BrandKitAPI.GetWorkspaceBrandKit(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.GetWorkspaceBrandKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceBrandKit`: WorkspaceBrandKitState
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.GetWorkspaceBrandKit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishWorkspaceBrandKit

> WorkspaceBrandKitState PublishWorkspaceBrandKit(ctx).PublishBrandKit(publishBrandKit).XOrganizationId(xOrganizationId).Execute()

Publish a reviewed brand and portal

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	publishBrandKit := *openapiclient.NewPublishBrandKit(*openapiclient.NewPublishBrandKitDraft(*openapiclient.NewInitialProposalDetailResponseRevisionContentBrandKitColors("Accent_example", "Background_example", "Primary_example", "Text_example"), "Description_example", time.Now(), "LogoUrl_example", "Name_example", "SourceUrl_example", "Tagline_example", *openapiclient.NewInitialProposalDetailResponseRevisionContentBrandKitTypography("Body_example", "Heading_example"), "Voice_example", []string{"Warnings_example"}), false) // PublishBrandKit | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PublishWorkspaceBrandKit(context.Background()).PublishBrandKit(publishBrandKit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PublishWorkspaceBrandKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishWorkspaceBrandKit`: WorkspaceBrandKitState
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PublishWorkspaceBrandKit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPublishWorkspaceBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publishBrandKit** | [**PublishBrandKit**](PublishBrandKit.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveWorkspaceBrandKit

> WorkspaceBrandKitState SaveWorkspaceBrandKit(ctx).SaveBrandKit(saveBrandKit).XOrganizationId(xOrganizationId).Execute()

Save a brand draft

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	saveBrandKit := *openapiclient.NewSaveBrandKit(*openapiclient.NewPublishBrandKitDraft(*openapiclient.NewInitialProposalDetailResponseRevisionContentBrandKitColors("Accent_example", "Background_example", "Primary_example", "Text_example"), "Description_example", time.Now(), "LogoUrl_example", "Name_example", "SourceUrl_example", "Tagline_example", *openapiclient.NewInitialProposalDetailResponseRevisionContentBrandKitTypography("Body_example", "Heading_example"), "Voice_example", []string{"Warnings_example"})) // SaveBrandKit | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.SaveWorkspaceBrandKit(context.Background()).SaveBrandKit(saveBrandKit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.SaveWorkspaceBrandKit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveWorkspaceBrandKit`: WorkspaceBrandKitState
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.SaveWorkspaceBrandKit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaveWorkspaceBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveBrandKit** | [**SaveBrandKit**](SaveBrandKit.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

