# \BillingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClaimBonusCredit**](BillingAPI.md#ClaimBonusCredit) | **Post** /v1/api/bonus-credits/{action}/claim | Claim the bonus credit for one action
[**CreateOrgBillingCheckout**](BillingAPI.md#CreateOrgBillingCheckout) | **Post** /v1/api/billing/checkout | Open a hlix billing checkout billed to the workspace
[**CreateOrgBillingPortal**](BillingAPI.md#CreateOrgBillingPortal) | **Post** /v1/api/billing/portal | Open the billing portal for the workspace
[**GetMonthlySpendLimits**](BillingAPI.md#GetMonthlySpendLimits) | **Get** /v1/api/usage/monthly-limits | Read Growth and Delivery limits and spending this UTC month
[**GetOrgBilling**](BillingAPI.md#GetOrgBilling) | **Get** /v1/api/billing | Read the workspace&#39;s plan, meters, orders and entitlement
[**GetOrgCredits**](BillingAPI.md#GetOrgCredits) | **Get** /v1/api/billing/credits | Read the per-task credit prices and the credits the workspace has left
[**GetOrgExtraUsage**](BillingAPI.md#GetOrgExtraUsage) | **Get** /v1/api/billing/extra-usage | Read whether work may continue past the included usage
[**GetProjectExtraUsage**](BillingAPI.md#GetProjectExtraUsage) | **Get** /v1/api/projects/{projectId}/extra-usage | Read a project&#39;s extra usage override and what it resolves to
[**GetProjectTaskCharges**](BillingAPI.md#GetProjectTaskCharges) | **Get** /v1/api/projects/{projectId}/task-charges | Read a project&#39;s accepted tasks, task price and review rounds
[**GetWorkspaceUsage**](BillingAPI.md#GetWorkspaceUsage) | **Get** /v1/api/usage | Read workspace usage and entitlement
[**ListBonusCredits**](BillingAPI.md#ListBonusCredits) | **Get** /v1/api/bonus-credits | List the bonus credit actions and which are claimed
[**ListOrgTaskCharges**](BillingAPI.md#ListOrgTaskCharges) | **Get** /v1/api/billing/task-charges | List the workspace&#39;s accepted tasks and their credits
[**RemoveWorkspaceUsageLimit**](BillingAPI.md#RemoveWorkspaceUsageLimit) | **Delete** /v1/api/usage/limit | Clear the workspace usage limit
[**SetDeliveryMonthlyLimit**](BillingAPI.md#SetDeliveryMonthlyLimit) | **Patch** /v1/api/usage/delivery-limit | Set or clear the monthly Delivery spending limit
[**SetOrgExtraUsage**](BillingAPI.md#SetOrgExtraUsage) | **Put** /v1/api/billing/extra-usage | Allow or stop usage past the included credit for the workspace
[**SetProjectExtraUsage**](BillingAPI.md#SetProjectExtraUsage) | **Put** /v1/api/projects/{projectId}/extra-usage | Set a project&#39;s extra usage override
[**SetWorkspaceUsageLimit**](BillingAPI.md#SetWorkspaceUsageLimit) | **Put** /v1/api/usage/limit | Set the workspace usage limit



## ClaimBonusCredit

> BonusClaim ClaimBonusCredit(ctx, action).XOrganizationId(xOrganizationId).Execute()

Claim the bonus credit for one action

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
	action := "action_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ClaimBonusCredit(context.Background(), action).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ClaimBonusCredit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClaimBonusCredit`: BonusClaim
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ClaimBonusCredit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**action** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClaimBonusCreditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**BonusClaim**](BonusClaim.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrgBillingCheckout

> BillingCheckoutSession CreateOrgBillingCheckout(ctx).BillingCheckout(billingCheckout).XOrganizationId(xOrganizationId).Execute()

Open a hlix billing checkout billed to the workspace

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
	billingCheckout := *openapiclient.NewBillingCheckout("Plan_example") // BillingCheckout | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CreateOrgBillingCheckout(context.Background()).BillingCheckout(billingCheckout).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CreateOrgBillingCheckout``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrgBillingCheckout`: BillingCheckoutSession
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CreateOrgBillingCheckout`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrgBillingCheckoutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **billingCheckout** | [**BillingCheckout**](BillingCheckout.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**BillingCheckoutSession**](BillingCheckoutSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrgBillingPortal

> BillingPortalSession CreateOrgBillingPortal(ctx).XOrganizationId(xOrganizationId).Execute()

Open the billing portal for the workspace

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
	resp, r, err := apiClient.BillingAPI.CreateOrgBillingPortal(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.CreateOrgBillingPortal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrgBillingPortal`: BillingPortalSession
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.CreateOrgBillingPortal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrgBillingPortalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**BillingPortalSession**](BillingPortalSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMonthlySpendLimits

> MonthlySpendLimits GetMonthlySpendLimits(ctx).XOrganizationId(xOrganizationId).Execute()

Read Growth and Delivery limits and spending this UTC month

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
	resp, r, err := apiClient.BillingAPI.GetMonthlySpendLimits(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetMonthlySpendLimits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMonthlySpendLimits`: MonthlySpendLimits
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetMonthlySpendLimits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMonthlySpendLimitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MonthlySpendLimits**](MonthlySpendLimits.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgBilling

> OrgBillingState GetOrgBilling(ctx).XOrganizationId(xOrganizationId).Execute()

Read the workspace's plan, meters, orders and entitlement

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
	resp, r, err := apiClient.BillingAPI.GetOrgBilling(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetOrgBilling``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgBilling`: OrgBillingState
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetOrgBilling`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgBillingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**OrgBillingState**](OrgBillingState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgCredits

> CreditsState GetOrgCredits(ctx).XOrganizationId(xOrganizationId).Execute()

Read the per-task credit prices and the credits the workspace has left

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
	resp, r, err := apiClient.BillingAPI.GetOrgCredits(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetOrgCredits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgCredits`: CreditsState
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetOrgCredits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgCreditsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CreditsState**](CreditsState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgExtraUsage

> WorkspaceExtraUsage GetOrgExtraUsage(ctx).XOrganizationId(xOrganizationId).Execute()

Read whether work may continue past the included usage

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
	resp, r, err := apiClient.BillingAPI.GetOrgExtraUsage(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetOrgExtraUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgExtraUsage`: WorkspaceExtraUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetOrgExtraUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgExtraUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceExtraUsage**](WorkspaceExtraUsage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectExtraUsage

> ProjectExtraUsage GetProjectExtraUsage(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Read a project's extra usage override and what it resolves to

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
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetProjectExtraUsage(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetProjectExtraUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectExtraUsage`: ProjectExtraUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetProjectExtraUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectExtraUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectExtraUsage**](ProjectExtraUsage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectTaskCharges

> ProjectTaskCharges GetProjectTaskCharges(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Read a project's accepted tasks, task price and review rounds

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
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetProjectTaskCharges(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetProjectTaskCharges``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectTaskCharges`: ProjectTaskCharges
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetProjectTaskCharges`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectTaskChargesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectTaskCharges**](ProjectTaskCharges.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspaceUsage

> WorkspaceUsage GetWorkspaceUsage(ctx).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()

Read workspace usage and entitlement

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
	sinceDays := "sinceDays_example" // string | Usage window in days; defaults to 30. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetWorkspaceUsage(context.Background()).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetWorkspaceUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceUsage`: WorkspaceUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetWorkspaceUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sinceDays** | **string** | Usage window in days; defaults to 30. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceUsage**](WorkspaceUsage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListBonusCredits

> BonusActions ListBonusCredits(ctx).XOrganizationId(xOrganizationId).Execute()

List the bonus credit actions and which are claimed

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
	resp, r, err := apiClient.BillingAPI.ListBonusCredits(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ListBonusCredits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListBonusCredits`: BonusActions
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ListBonusCredits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListBonusCreditsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**BonusActions**](BonusActions.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListOrgTaskCharges

> WorkspaceTaskCharges ListOrgTaskCharges(ctx).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()

List the workspace's accepted tasks and their credits

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
	sinceDays := "sinceDays_example" // string | Window in days, default 30. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ListOrgTaskCharges(context.Background()).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ListOrgTaskCharges``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListOrgTaskCharges`: WorkspaceTaskCharges
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ListOrgTaskCharges`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListOrgTaskChargesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sinceDays** | **string** | Window in days, default 30. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceTaskCharges**](WorkspaceTaskCharges.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveWorkspaceUsageLimit

> UsageLimitResponse RemoveWorkspaceUsageLimit(ctx).XOrganizationId(xOrganizationId).Execute()

Clear the workspace usage limit

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
	resp, r, err := apiClient.BillingAPI.RemoveWorkspaceUsageLimit(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.RemoveWorkspaceUsageLimit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveWorkspaceUsageLimit`: UsageLimitResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.RemoveWorkspaceUsageLimit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRemoveWorkspaceUsageLimitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**UsageLimitResponse**](UsageLimitResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetDeliveryMonthlyLimit

> DeliveryMonthlyLimit SetDeliveryMonthlyLimit(ctx).DeliveryMonthlyLimit(deliveryMonthlyLimit).XOrganizationId(xOrganizationId).Execute()

Set or clear the monthly Delivery spending limit

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
	deliveryMonthlyLimit := *openapiclient.NewDeliveryMonthlyLimit(NullableInt64(123)) // DeliveryMonthlyLimit | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetDeliveryMonthlyLimit(context.Background()).DeliveryMonthlyLimit(deliveryMonthlyLimit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.SetDeliveryMonthlyLimit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetDeliveryMonthlyLimit`: DeliveryMonthlyLimit
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.SetDeliveryMonthlyLimit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetDeliveryMonthlyLimitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliveryMonthlyLimit** | [**DeliveryMonthlyLimit**](DeliveryMonthlyLimit.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliveryMonthlyLimit**](DeliveryMonthlyLimit.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetOrgExtraUsage

> WorkspaceExtraUsage SetOrgExtraUsage(ctx).SetExtraUsage(setExtraUsage).XOrganizationId(xOrganizationId).Execute()

Allow or stop usage past the included credit for the workspace

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
	setExtraUsage := *openapiclient.NewSetExtraUsage(false) // SetExtraUsage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetOrgExtraUsage(context.Background()).SetExtraUsage(setExtraUsage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.SetOrgExtraUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetOrgExtraUsage`: WorkspaceExtraUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.SetOrgExtraUsage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetOrgExtraUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setExtraUsage** | [**SetExtraUsage**](SetExtraUsage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceExtraUsage**](WorkspaceExtraUsage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetProjectExtraUsage

> ProjectExtraUsage SetProjectExtraUsage(ctx, projectId).SetProjectExtraUsage(setProjectExtraUsage).XOrganizationId(xOrganizationId).Execute()

Set a project's extra usage override

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
	projectId := "projectId_example" // string | 
	setProjectExtraUsage := *openapiclient.NewSetProjectExtraUsage("Mode_example") // SetProjectExtraUsage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetProjectExtraUsage(context.Background(), projectId).SetProjectExtraUsage(setProjectExtraUsage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.SetProjectExtraUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetProjectExtraUsage`: ProjectExtraUsage
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.SetProjectExtraUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetProjectExtraUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setProjectExtraUsage** | [**SetProjectExtraUsage**](SetProjectExtraUsage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectExtraUsage**](ProjectExtraUsage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetWorkspaceUsageLimit

> UsageLimitResponse SetWorkspaceUsageLimit(ctx).UsageLimit(usageLimit).XOrganizationId(xOrganizationId).Execute()

Set the workspace usage limit

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
	usageLimit := *openapiclient.NewUsageLimit(int32(123)) // UsageLimit | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetWorkspaceUsageLimit(context.Background()).UsageLimit(usageLimit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.SetWorkspaceUsageLimit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetWorkspaceUsageLimit`: UsageLimitResponse
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.SetWorkspaceUsageLimit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetWorkspaceUsageLimitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **usageLimit** | [**UsageLimit**](UsageLimit.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**UsageLimitResponse**](UsageLimitResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

