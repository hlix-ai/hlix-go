# ClientInvoicesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateClientInvoiceDraft**](ClientInvoicesAPI.md#createclientinvoicedraft) | **Post** /v1/api/client-billing/invoices | Assemble a draft invoice from billables
[**CreateClientInvoicePaymentLink**](ClientInvoicesAPI.md#createclientinvoicepaymentlink) | **Post** /v1/api/client-billing/invoices/{id}/payment-link | Open a provider-hosted checkout for an issued invoice
[**GetClientInvoice**](ClientInvoicesAPI.md#getclientinvoice) | **Get** /v1/api/client-billing/invoices/{id} | Get one invoice with its lines
[**GetClientInvoiceLogo**](ClientInvoicesAPI.md#getclientinvoicelogo) | **Get** /v1/api/client-billing/invoices/{id}/logo | Download the logo frozen onto this invoice
[**GetClientInvoicePdf**](ClientInvoicesAPI.md#getclientinvoicepdf) | **Get** /v1/api/client-billing/invoices/{id}/pdf | Download the invoice as a PDF
[**IssueClientInvoice**](ClientInvoicesAPI.md#issueclientinvoice) | **Post** /v1/api/client-billing/invoices/{id}/issue | Issue a draft, assigning its number
[**ListClientInvoices**](ClientInvoicesAPI.md#listclientinvoices) | **Get** /v1/api/client-billing/invoices | List invoices
[**PayClientInvoice**](ClientInvoicesAPI.md#payclientinvoice) | **Post** /v1/api/client-billing/invoices/{id}/pay | Record an out-of-band settlement (bank transfer, cheque)
[**VoidClientInvoice**](ClientInvoicesAPI.md#voidclientinvoice) | **Post** /v1/api/client-billing/invoices/{id}/void | Withdraw an invoice, or discard a draft



## CreateClientInvoiceDraft

> ClientInvoice CreateClientInvoiceDraft(ctx).CreateInvoiceDraft(createInvoiceDraft).XOrganizationId(xOrganizationId).Execute()

Assemble a draft invoice from billables

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
	var createInvoiceDraft openapiclient.CreateInvoiceDraft
	if err := json.Unmarshal([]byte("{\"billableIds\":[\"text\"],\"buyerAddress\":\"text\",\"dueAt\":\"2026-01-31T09:30:00Z\"}"), &createInvoiceDraft); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.CreateClientInvoiceDraft(ctx).CreateInvoiceDraft(createInvoiceDraft).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.CreateClientInvoiceDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateClientInvoiceDraft`: ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.CreateClientInvoiceDraft`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateClientInvoiceDraftRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInvoiceDraft** | [**CreateInvoiceDraft**](CreateInvoiceDraft.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateClientInvoicePaymentLink

> ClientPaymentLink CreateClientInvoicePaymentLink(ctx, id).PaymentLink(paymentLink).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Open a provider-hosted checkout for an issued invoice

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
	id := "id_example" // string |
	var paymentLink openapiclient.PaymentLink
	if err := json.Unmarshal([]byte("{}"), &paymentLink); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.CreateClientInvoicePaymentLink(ctx, id).PaymentLink(paymentLink).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.CreateClientInvoicePaymentLink``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateClientInvoicePaymentLink`: ClientPaymentLink
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.CreateClientInvoicePaymentLink`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCreateClientInvoicePaymentLinkRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **paymentLink** | [**PaymentLink**](PaymentLink.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientPaymentLink**](ClientPaymentLink.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientInvoice

> ClientInvoice GetClientInvoice(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one invoice with its lines

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
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoice(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.GetClientInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientInvoice`: ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.GetClientInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientInvoiceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientInvoiceLogo

> *os.File GetClientInvoiceLogo(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Download the logo frozen onto this invoice

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
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoiceLogo(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.GetClientInvoiceLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientInvoiceLogo`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.GetClientInvoiceLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientInvoiceLogoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

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


## GetClientInvoicePdf

> *os.File GetClientInvoicePdf(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Download the invoice as a PDF

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
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoicePdf(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.GetClientInvoicePdf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientInvoicePdf`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.GetClientInvoicePdf`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientInvoicePdfRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## IssueClientInvoice

> ClientInvoice IssueClientInvoice(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()

Issue a draft, assigning its number

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
	id := "id_example" // string |
	body := map[string]interface{}{ ... } // map[string]interface{} |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.IssueClientInvoice(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.IssueClientInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IssueClientInvoice`: ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.IssueClientInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiIssueClientInvoiceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListClientInvoices

> []ClientInvoice ListClientInvoices(ctx).ClientAccountId(clientAccountId).Status(status).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List invoices

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
	clientAccountId := "clientAccountId_example" // string | Only this customer's invoices. (optional)
	status := "status_example" // string | One of `draft`, `final`, `void`, `paid`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.ListClientInvoices(ctx).ClientAccountId(clientAccountId).Status(status).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.ListClientInvoices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListClientInvoices`: []ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.ListClientInvoices`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListClientInvoicesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **clientAccountId** | **string** | Only this customer&#39;s invoices. |
 **status** | **string** | One of &#x60;draft&#x60;, &#x60;final&#x60;, &#x60;void&#x60;, &#x60;paid&#x60;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayClientInvoice

> ClientInvoice PayClientInvoice(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()

Record an out-of-band settlement (bank transfer, cheque)

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
	id := "id_example" // string |
	body := map[string]interface{}{ ... } // map[string]interface{} |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.PayClientInvoice(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.PayClientInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayClientInvoice`: ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.PayClientInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiPayClientInvoiceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VoidClientInvoice

> ClientInvoice VoidClientInvoice(ctx, id).VoidInvoice(voidInvoice).XOrganizationId(xOrganizationId).Execute()

Withdraw an invoice, or discard a draft

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
	id := "id_example" // string |
	var voidInvoice openapiclient.VoidInvoice
	if err := json.Unmarshal([]byte("{\"reason\":\"text\"}"), &voidInvoice); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.VoidClientInvoice(ctx, id).VoidInvoice(voidInvoice).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientInvoicesAPI.VoidClientInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VoidClientInvoice`: ClientInvoice
	fmt.Fprintf(os.Stdout, "Response from `ClientInvoicesAPI.VoidClientInvoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiVoidClientInvoiceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **voidInvoice** | [**VoidInvoice**](VoidInvoice.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

