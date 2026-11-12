# BillingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClaimBonusCredit**](BillingAPI.md#claimbonuscredit) | **Post** /v1/api/bonus-credits/{action}/claim | Claim the bonus credit for one action
[**ClaimPromotionOffer**](BillingAPI.md#claimpromotionoffer) | **Post** /v1/api/promotions/claim | Claim an offer for the workspace
[**CreateOrgBillingCheckout**](BillingAPI.md#createorgbillingcheckout) | **Post** /v1/api/billing/checkout | Open a hlix billing checkout billed to the workspace
[**CreateOrgBillingPortal**](BillingAPI.md#createorgbillingportal) | **Post** /v1/api/billing/portal | Open the billing portal for the workspace
[**GetCurrentPromotion**](BillingAPI.md#getcurrentpromotion) | **Get** /v1/api/promotions/current | Read the workspace&#39;s current promotion
[**GetMonthlySpendLimits**](BillingAPI.md#getmonthlyspendlimits) | **Get** /v1/api/usage/monthly-limits | Read Growth and Delivery limits and spending this UTC month
[**GetOrgBilling**](BillingAPI.md#getorgbilling) | **Get** /v1/api/billing | Read the workspace&#39;s plan, meters, orders and entitlement
[**GetOrgCredits**](BillingAPI.md#getorgcredits) | **Get** /v1/api/billing/credits | Read per-task prices and the remaining Hlix Dollars
[**GetOrgExtraUsage**](BillingAPI.md#getorgextrausage) | **Get** /v1/api/billing/extra-usage | Read whether work may continue past the included usage
[**GetOwnPartnerPromotion**](BillingAPI.md#getownpartnerpromotion) | **Get** /v1/api/promotions/partner | Read this partner&#39;s referral counts and reward history
[**GetPartnerPromotionOffer**](BillingAPI.md#getpartnerpromotionoffer) | **Get** /v1/api/promotions/partners/{slug} | Preview a public partner offer
[**GetProjectExtraUsage**](BillingAPI.md#getprojectextrausage) | **Get** /v1/api/projects/{projectId}/extra-usage | Read a project&#39;s extra usage override and what it resolves to
[**GetProjectTaskCharges**](BillingAPI.md#getprojecttaskcharges) | **Get** /v1/api/projects/{projectId}/task-charges | Read a project&#39;s accepted tasks, task price and review rounds
[**GetWorkspaceUsage**](BillingAPI.md#getworkspaceusage) | **Get** /v1/api/usage | Read workspace usage and entitlement
[**ListBonusCredits**](BillingAPI.md#listbonuscredits) | **Get** /v1/api/bonus-credits | List the bonus credit actions and which are claimed
[**ListOrgTaskCharges**](BillingAPI.md#listorgtaskcharges) | **Get** /v1/api/billing/task-charges | List the workspace&#39;s accepted tasks and their credits
[**RemoveWorkspaceUsageLimit**](BillingAPI.md#removeworkspaceusagelimit) | **Delete** /v1/api/usage/limit | Clear the workspace usage limit
[**ResolvePromotionOffer**](BillingAPI.md#resolvepromotionoffer) | **Post** /v1/api/promotions/resolve | Preview a private invitation or public partner offer
[**RevokePromotionAnalyticsConsent**](BillingAPI.md#revokepromotionanalyticsconsent) | **Post** /v1/api/promotions/analytics-consent | Withdraw stored promotion analytics permission
[**SetDeliveryMonthlyLimit**](BillingAPI.md#setdeliverymonthlylimit) | **Patch** /v1/api/usage/delivery-limit | Set or clear the monthly Delivery spending limit
[**SetOrgExtraUsage**](BillingAPI.md#setorgextrausage) | **Put** /v1/api/billing/extra-usage | Allow or stop usage past the included credit for the workspace
[**SetProjectExtraUsage**](BillingAPI.md#setprojectextrausage) | **Put** /v1/api/projects/{projectId}/extra-usage | Set a project&#39;s extra usage override
[**SetWorkspaceUsageLimit**](BillingAPI.md#setworkspaceusagelimit) | **Put** /v1/api/usage/limit | Set the workspace usage limit



## ClaimBonusCredit

> BonusClaim ClaimBonusCredit(ctx, action).XOrganizationId(xOrganizationId).Execute()

Claim the bonus credit for one action

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
	action := "action_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ClaimBonusCredit(ctx, action).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiClaimBonusCreditRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BonusClaim**](BonusClaim.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClaimPromotionOffer

> PromotionCurrent ClaimPromotionOffer(ctx).PromotionResolveInput(promotionResolveInput).XOrganizationId(xOrganizationId).Execute()

Claim an offer for the workspace

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
	var promotionResolveInput openapiclient.PromotionResolveInput
	if err := json.Unmarshal([]byte("{}"), &promotionResolveInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ClaimPromotionOffer(ctx).PromotionResolveInput(promotionResolveInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ClaimPromotionOffer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClaimPromotionOffer`: PromotionCurrent
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ClaimPromotionOffer`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiClaimPromotionOfferRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **promotionResolveInput** | [**PromotionResolveInput**](PromotionResolveInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PromotionCurrent**](PromotionCurrent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrgBillingCheckout

> BillingCheckoutSession CreateOrgBillingCheckout(ctx).BillingCheckout(billingCheckout).XOrganizationId(xOrganizationId).Execute()

Open a hlix billing checkout billed to the workspace

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
	var billingCheckout openapiclient.BillingCheckout
	if err := json.Unmarshal([]byte("{\"plan\":\"free\"}"), &billingCheckout); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.CreateOrgBillingCheckout(ctx).BillingCheckout(billingCheckout).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateOrgBillingCheckoutRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **billingCheckout** | [**BillingCheckout**](BillingCheckout.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BillingCheckoutSession**](BillingCheckoutSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.CreateOrgBillingPortal(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateOrgBillingPortalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BillingPortalSession**](BillingPortalSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCurrentPromotion

> PromotionCurrent GetCurrentPromotion(ctx).XOrganizationId(xOrganizationId).Execute()

Read the workspace's current promotion

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
	resp, r, err := apiClient.BillingAPI.GetCurrentPromotion(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetCurrentPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentPromotion`: PromotionCurrent
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetCurrentPromotion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetCurrentPromotionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PromotionCurrent**](PromotionCurrent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.GetMonthlySpendLimits(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetMonthlySpendLimitsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MonthlySpendLimits**](MonthlySpendLimits.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.GetOrgBilling(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetOrgBillingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**OrgBillingState**](OrgBillingState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgCredits

> CreditsState GetOrgCredits(ctx).XOrganizationId(xOrganizationId).Execute()

Read per-task prices and the remaining Hlix Dollars

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
	resp, r, err := apiClient.BillingAPI.GetOrgCredits(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetOrgCreditsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CreditsState**](CreditsState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.GetOrgExtraUsage(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetOrgExtraUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceExtraUsage**](WorkspaceExtraUsage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOwnPartnerPromotion

> PromotionPartnerSummary GetOwnPartnerPromotion(ctx).XOrganizationId(xOrganizationId).Execute()

Read this partner's referral counts and reward history

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
	resp, r, err := apiClient.BillingAPI.GetOwnPartnerPromotion(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetOwnPartnerPromotion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOwnPartnerPromotion`: PromotionPartnerSummary
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetOwnPartnerPromotion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetOwnPartnerPromotionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PromotionPartnerSummary**](PromotionPartnerSummary.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerPromotionOffer

> PromotionOffer GetPartnerPromotionOffer(ctx, slug).Execute()

Preview a public partner offer

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
	slug := "slug_example" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetPartnerPromotionOffer(ctx, slug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetPartnerPromotionOffer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerPromotionOffer`: PromotionOffer
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetPartnerPromotionOffer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetPartnerPromotionOfferRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PromotionOffer**](PromotionOffer.md)

### Authorization

No authorization required

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
	projectId := "projectId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetProjectExtraUsage(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectExtraUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectExtraUsage**](ProjectExtraUsage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetProjectTaskCharges(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectTaskChargesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectTaskCharges**](ProjectTaskCharges.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sinceDays := "sinceDays_example" // string | Usage window in days; defaults to 30. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.GetWorkspaceUsage(ctx).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetWorkspaceUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sinceDays** | **string** | Usage window in days; defaults to 30. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceUsage**](WorkspaceUsage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.ListBonusCredits(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListBonusCreditsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BonusActions**](BonusActions.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sinceDays := "sinceDays_example" // string | Window in days, default 30. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ListOrgTaskCharges(ctx).SinceDays(sinceDays).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListOrgTaskChargesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sinceDays** | **string** | Window in days, default 30. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceTaskCharges**](WorkspaceTaskCharges.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.BillingAPI.RemoveWorkspaceUsageLimit(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRemoveWorkspaceUsageLimitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**UsageLimitResponse**](UsageLimitResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolvePromotionOffer

> PromotionOffer ResolvePromotionOffer(ctx).PromotionResolveInput(promotionResolveInput).Execute()

Preview a private invitation or public partner offer

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
	var promotionResolveInput openapiclient.PromotionResolveInput
	if err := json.Unmarshal([]byte("{}"), &promotionResolveInput); err != nil {
		panic(err)
	}

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.ResolvePromotionOffer(ctx).PromotionResolveInput(promotionResolveInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.ResolvePromotionOffer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolvePromotionOffer`: PromotionOffer
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.ResolvePromotionOffer`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiResolvePromotionOfferRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **promotionResolveInput** | [**PromotionResolveInput**](PromotionResolveInput.md) |  |

### Return type

[**PromotionOffer**](PromotionOffer.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokePromotionAnalyticsConsent

> PromotionConsentRevoked RevokePromotionAnalyticsConsent(ctx).PromotionAnalyticsConsent(promotionAnalyticsConsent).XOrganizationId(xOrganizationId).Execute()

Withdraw stored promotion analytics permission

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
	ctx := context.Background()
	var promotionAnalyticsConsent openapiclient.PromotionAnalyticsConsent
	if err := json.Unmarshal([]byte("{\"granted\":false}"), &promotionAnalyticsConsent); err != nil {
		panic(err)
	}

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.RevokePromotionAnalyticsConsent(ctx).PromotionAnalyticsConsent(promotionAnalyticsConsent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.RevokePromotionAnalyticsConsent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokePromotionAnalyticsConsent`: PromotionConsentRevoked
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.RevokePromotionAnalyticsConsent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiRevokePromotionAnalyticsConsentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **promotionAnalyticsConsent** | [**PromotionAnalyticsConsent**](PromotionAnalyticsConsent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PromotionConsentRevoked**](PromotionConsentRevoked.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetDeliveryMonthlyLimit

> DeliveryMonthlyLimit SetDeliveryMonthlyLimit(ctx).DeliveryMonthlyLimit(deliveryMonthlyLimit).XOrganizationId(xOrganizationId).Execute()

Set or clear the monthly Delivery spending limit

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
	var deliveryMonthlyLimit openapiclient.DeliveryMonthlyLimit
	if err := json.Unmarshal([]byte("{\"deliveryMonthlyCapMicros\":1}"), &deliveryMonthlyLimit); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetDeliveryMonthlyLimit(ctx).DeliveryMonthlyLimit(deliveryMonthlyLimit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetDeliveryMonthlyLimitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliveryMonthlyLimit** | [**DeliveryMonthlyLimit**](DeliveryMonthlyLimit.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliveryMonthlyLimit**](DeliveryMonthlyLimit.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var setExtraUsage openapiclient.SetExtraUsage
	if err := json.Unmarshal([]byte("{\"allow\":true}"), &setExtraUsage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetOrgExtraUsage(ctx).SetExtraUsage(setExtraUsage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetOrgExtraUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setExtraUsage** | [**SetExtraUsage**](SetExtraUsage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceExtraUsage**](WorkspaceExtraUsage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var setProjectExtraUsage openapiclient.SetProjectExtraUsage
	if err := json.Unmarshal([]byte("{\"mode\":\"inherit\"}"), &setProjectExtraUsage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetProjectExtraUsage(ctx, projectId).SetProjectExtraUsage(setProjectExtraUsage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetProjectExtraUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setProjectExtraUsage** | [**SetProjectExtraUsage**](SetProjectExtraUsage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectExtraUsage**](ProjectExtraUsage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var usageLimit openapiclient.UsageLimit
	if err := json.Unmarshal([]byte("{\"capMillicents\":2}"), &usageLimit); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BillingAPI.SetWorkspaceUsageLimit(ctx).UsageLimit(usageLimit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetWorkspaceUsageLimitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **usageLimit** | [**UsageLimit**](UsageLimit.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**UsageLimitResponse**](UsageLimitResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

