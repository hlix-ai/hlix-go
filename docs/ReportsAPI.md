# ReportsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBillingReport**](ReportsAPI.md#getbillingreport) | **Get** /v1/api/reports/billing | Get billing health
[**GetOverviewReport**](ReportsAPI.md#getoverviewreport) | **Get** /v1/api/reports | Get the current portfolio overview
[**GetUsageReport**](ReportsAPI.md#getusagereport) | **Get** /v1/api/reports/usage | Get agent usage and cost
[**ListCustomerReports**](ReportsAPI.md#listcustomerreports) | **Get** /v1/api/reports/customers | List customer portfolio reports
[**ListProjectReports**](ReportsAPI.md#listprojectreports) | **Get** /v1/api/reports/projects | List project health reports



## GetBillingReport

> GetBillingReport200Response GetBillingReport(ctx).Period(period).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get billing health

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
	period := "period_example" // string | Rolling reporting window such as `30d`; clamped to 1–365 days. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.GetBillingReport(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.GetBillingReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBillingReport`: GetBillingReport200Response
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.GetBillingReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetBillingReportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **period** | **string** | Rolling reporting window such as &#x60;30d&#x60;; clamped to 1–365 days. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**GetBillingReport200Response**](GetBillingReport200Response.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOverviewReport

> GetOverviewReport200Response GetOverviewReport(ctx).Period(period).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the current portfolio overview

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
	period := "period_example" // string | Rolling reporting window such as `30d`; clamped to 1–365 days. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.GetOverviewReport(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.GetOverviewReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOverviewReport`: GetOverviewReport200Response
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.GetOverviewReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetOverviewReportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **period** | **string** | Rolling reporting window such as &#x60;30d&#x60;; clamped to 1–365 days. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**GetOverviewReport200Response**](GetOverviewReport200Response.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsageReport

> UsageReport GetUsageReport(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()

Get agent usage and cost

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
	period := "period_example" // string | Rolling reporting window such as `30d`; clamped to 1–365 days. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.GetUsageReport(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.GetUsageReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsageReport`: UsageReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.GetUsageReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetUsageReportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **period** | **string** | Rolling reporting window such as &#x60;30d&#x60;; clamped to 1–365 days. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**UsageReport**](UsageReport.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCustomerReports

> CustomersReport ListCustomerReports(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()

List customer portfolio reports

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
	period := "period_example" // string | Rolling reporting window such as `30d`; clamped to 1–365 days. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.ListCustomerReports(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.ListCustomerReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCustomerReports`: CustomersReport
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.ListCustomerReports`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListCustomerReportsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **period** | **string** | Rolling reporting window such as &#x60;30d&#x60;; clamped to 1–365 days. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomersReport**](CustomersReport.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectReports

> ListProjectReports200Response ListProjectReports(ctx).Period(period).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List project health reports

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
	period := "period_example" // string | Rolling reporting window such as `30d`; clamped to 1–365 days. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReportsAPI.ListProjectReports(ctx).Period(period).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReportsAPI.ListProjectReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectReports`: ListProjectReports200Response
	fmt.Fprintf(os.Stdout, "Response from `ReportsAPI.ListProjectReports`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListProjectReportsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **period** | **string** | Rolling reporting window such as &#x60;30d&#x60;; clamped to 1–365 days. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ListProjectReports200Response**](ListProjectReports200Response.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

