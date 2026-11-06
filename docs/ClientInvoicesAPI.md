# \ClientInvoicesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateClientInvoiceDraft**](ClientInvoicesAPI.md#CreateClientInvoiceDraft) | **Post** /v1/api/client-billing/invoices | Assemble a draft invoice from billables
[**CreateClientInvoicePaymentLink**](ClientInvoicesAPI.md#CreateClientInvoicePaymentLink) | **Post** /v1/api/client-billing/invoices/{id}/payment-link | Open a provider-hosted checkout for an issued invoice
[**GetClientInvoice**](ClientInvoicesAPI.md#GetClientInvoice) | **Get** /v1/api/client-billing/invoices/{id} | Get one invoice with its lines
[**GetClientInvoiceLogo**](ClientInvoicesAPI.md#GetClientInvoiceLogo) | **Get** /v1/api/client-billing/invoices/{id}/logo | Download the logo frozen onto this invoice
[**GetClientInvoicePdf**](ClientInvoicesAPI.md#GetClientInvoicePdf) | **Get** /v1/api/client-billing/invoices/{id}/pdf | Download the invoice as a PDF
[**IssueClientInvoice**](ClientInvoicesAPI.md#IssueClientInvoice) | **Post** /v1/api/client-billing/invoices/{id}/issue | Issue a draft, assigning its number
[**ListClientInvoices**](ClientInvoicesAPI.md#ListClientInvoices) | **Get** /v1/api/client-billing/invoices | List invoices
[**PayClientInvoice**](ClientInvoicesAPI.md#PayClientInvoice) | **Post** /v1/api/client-billing/invoices/{id}/pay | Record an out-of-band settlement (bank transfer, cheque)
[**VoidClientInvoice**](ClientInvoicesAPI.md#VoidClientInvoice) | **Post** /v1/api/client-billing/invoices/{id}/void | Withdraw an invoice, or discard a draft



## CreateClientInvoiceDraft

> ClientInvoice CreateClientInvoiceDraft(ctx).CreateInvoiceDraft(createInvoiceDraft).XOrganizationId(xOrganizationId).Execute()

Assemble a draft invoice from billables

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
	createInvoiceDraft := *openapiclient.NewCreateInvoiceDraft([]string{"BillableIds_example"}, "BuyerAddress_example", time.Now()) // CreateInvoiceDraft | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.CreateClientInvoiceDraft(context.Background()).CreateInvoiceDraft(createInvoiceDraft).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCreateClientInvoiceDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createInvoiceDraft** | [**CreateInvoiceDraft**](CreateInvoiceDraft.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	paymentLink := *openapiclient.NewPaymentLink() // PaymentLink | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.CreateClientInvoicePaymentLink(context.Background(), id).PaymentLink(paymentLink).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiCreateClientInvoicePaymentLinkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **paymentLink** | [**PaymentLink**](PaymentLink.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ClientPaymentLink**](ClientPaymentLink.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoice(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiGetClientInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoiceLogo(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiGetClientInvoiceLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.GetClientInvoicePdf(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiGetClientInvoicePdfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	body := map[string]interface{}{ ... } // map[string]interface{} | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.IssueClientInvoice(context.Background(), id).Body(body).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiIssueClientInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	clientAccountId := "clientAccountId_example" // string | Only this customer's invoices. (optional)
	status := "status_example" // string | One of `draft`, `final`, `void`, `paid`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.ListClientInvoices(context.Background()).ClientAccountId(clientAccountId).Status(status).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiListClientInvoicesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **clientAccountId** | **string** | Only this customer&#39;s invoices. | 
 **status** | **string** | One of &#x60;draft&#x60;, &#x60;final&#x60;, &#x60;void&#x60;, &#x60;paid&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	body := map[string]interface{}{ ... } // map[string]interface{} | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.PayClientInvoice(context.Background(), id).Body(body).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiPayClientInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	voidInvoice := *openapiclient.NewVoidInvoice("Reason_example") // VoidInvoice | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientInvoicesAPI.VoidClientInvoice(context.Background(), id).VoidInvoice(voidInvoice).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiVoidClientInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **voidInvoice** | [**VoidInvoice**](VoidInvoice.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientInvoice**](ClientInvoice.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

