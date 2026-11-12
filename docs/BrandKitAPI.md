# BrandKitAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ExtractWorkspaceBrandKit**](BrandKitAPI.md#extractworkspacebrandkit) | **Post** /v1/api/brand-kit/extract | Extract a draft brand from one website URL
[**GetWorkspaceBrandKit**](BrandKitAPI.md#getworkspacebrandkit) | **Get** /v1/api/brand-kit | Read workspace brand settings
[**PublishWorkspaceBrandKit**](BrandKitAPI.md#publishworkspacebrandkit) | **Post** /v1/api/brand-kit/publish | Publish a reviewed brand and portal
[**SaveWorkspaceBrandKit**](BrandKitAPI.md#saveworkspacebrandkit) | **Put** /v1/api/brand-kit | Save a brand draft



## ExtractWorkspaceBrandKit

> WorkspaceBrandKitState ExtractWorkspaceBrandKit(ctx).ExtractBrandKit(extractBrandKit).XOrganizationId(xOrganizationId).Execute()

Extract a draft brand from one website URL

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
	var extractBrandKit openapiclient.ExtractBrandKit
	if err := json.Unmarshal([]byte("{\"url\":\"https://example.com\"}"), &extractBrandKit); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.ExtractWorkspaceBrandKit(ctx).ExtractBrandKit(extractBrandKit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiExtractWorkspaceBrandKitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **extractBrandKit** | [**ExtractBrandKit**](ExtractBrandKit.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BrandKitAPI.GetWorkspaceBrandKit(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetWorkspaceBrandKitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	var publishBrandKit openapiclient.PublishBrandKit
	if err := json.Unmarshal([]byte("{\"draft\":{\"colors\":{\"accent\":\"#1f2937\",\"background\":\"#1f2937\",\"primary\":\"#1f2937\",\"text\":\"#1f2937\"},\"description\":\"text\",\"extractedAt\":\"2026-01-31T09:30:00Z\",\"logoUrl\":\"https://example.com\",\"name\":\"text\",\"sourceUrl\":\"https://example.com\",\"tagline\":\"text\",\"typography\":{\"body\":\"text\",\"heading\":\"text\"},\"voice\":\"text\",\"warnings\":[\"text\"]},\"portalEnabled\":true}"), &publishBrandKit); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PublishWorkspaceBrandKit(ctx).PublishBrandKit(publishBrandKit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPublishWorkspaceBrandKitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **publishBrandKit** | [**PublishBrandKit**](PublishBrandKit.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	var saveBrandKit openapiclient.SaveBrandKit
	if err := json.Unmarshal([]byte("{\"draft\":{\"colors\":{\"accent\":\"#1f2937\",\"background\":\"#1f2937\",\"primary\":\"#1f2937\",\"text\":\"#1f2937\"},\"description\":\"text\",\"extractedAt\":\"2026-01-31T09:30:00Z\",\"logoUrl\":\"https://example.com\",\"name\":\"text\",\"sourceUrl\":\"https://example.com\",\"tagline\":\"text\",\"typography\":{\"body\":\"text\",\"heading\":\"text\"},\"voice\":\"text\",\"warnings\":[\"text\"]}}"), &saveBrandKit); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.SaveWorkspaceBrandKit(ctx).SaveBrandKit(saveBrandKit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSaveWorkspaceBrandKitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveBrandKit** | [**SaveBrandKit**](SaveBrandKit.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceBrandKitState**](WorkspaceBrandKitState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

