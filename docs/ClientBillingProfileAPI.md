# ClientBillingProfileAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteAgencyBillingProfile**](ClientBillingProfileAPI.md#deleteagencybillingprofile) | **Delete** /v1/api/client-billing/profile | Remove the workspace&#39;s billing identity
[**GetAgencyBillingProfile**](ClientBillingProfileAPI.md#getagencybillingprofile) | **Get** /v1/api/client-billing/profile | Get the workspace&#39;s billing identity
[**GetAgencyBillingProfileLogo**](ClientBillingProfileAPI.md#getagencybillingprofilelogo) | **Get** /v1/api/client-billing/profile/logo | Download the workspace&#39;s logo
[**UpsertAgencyBillingProfile**](ClientBillingProfileAPI.md#upsertagencybillingprofile) | **Put** /v1/api/client-billing/profile | Replace the workspace&#39;s billing identity



## DeleteAgencyBillingProfile

> AgencyBillingProfileCleared DeleteAgencyBillingProfile(ctx).XOrganizationId(xOrganizationId).Execute()

Remove the workspace's billing identity

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
	resp, r, err := apiClient.ClientBillingProfileAPI.DeleteAgencyBillingProfile(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingProfileAPI.DeleteAgencyBillingProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteAgencyBillingProfile`: AgencyBillingProfileCleared
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingProfileAPI.DeleteAgencyBillingProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiDeleteAgencyBillingProfileRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgencyBillingProfileCleared**](AgencyBillingProfileCleared.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgencyBillingProfile

> AgencyBillingProfileState GetAgencyBillingProfile(ctx).XOrganizationId(xOrganizationId).Execute()

Get the workspace's billing identity

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
	resp, r, err := apiClient.ClientBillingProfileAPI.GetAgencyBillingProfile(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingProfileAPI.GetAgencyBillingProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgencyBillingProfile`: AgencyBillingProfileState
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingProfileAPI.GetAgencyBillingProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetAgencyBillingProfileRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgencyBillingProfileState**](AgencyBillingProfileState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgencyBillingProfileLogo

> *os.File GetAgencyBillingProfileLogo(ctx).XOrganizationId(xOrganizationId).Execute()

Download the workspace's logo

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
	resp, r, err := apiClient.ClientBillingProfileAPI.GetAgencyBillingProfileLogo(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingProfileAPI.GetAgencyBillingProfileLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgencyBillingProfileLogo`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingProfileAPI.GetAgencyBillingProfileLogo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetAgencyBillingProfileLogoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: image/png, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertAgencyBillingProfile

> AgencyBillingProfileState UpsertAgencyBillingProfile(ctx).UpsertBillingProfile(upsertBillingProfile).XOrganizationId(xOrganizationId).Execute()

Replace the workspace's billing identity

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
	var upsertBillingProfile openapiclient.UpsertBillingProfile
	if err := json.Unmarshal([]byte("{\"address\":\"text\",\"legalName\":\"text\"}"), &upsertBillingProfile); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingProfileAPI.UpsertAgencyBillingProfile(ctx).UpsertBillingProfile(upsertBillingProfile).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingProfileAPI.UpsertAgencyBillingProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertAgencyBillingProfile`: AgencyBillingProfileState
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingProfileAPI.UpsertAgencyBillingProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiUpsertAgencyBillingProfileRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **upsertBillingProfile** | [**UpsertBillingProfile**](UpsertBillingProfile.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgencyBillingProfileState**](AgencyBillingProfileState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

