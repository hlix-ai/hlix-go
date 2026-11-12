# CrmAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddCrmNote**](CrmAPI.md#addcrmnote) | **Post** /v1/api/crm/notes | Add a note to a deal, contact or client timeline
[**CreateCrmContact**](CrmAPI.md#createcrmcontact) | **Post** /v1/api/crm/contacts | Create a contact
[**CreateCrmDeal**](CrmAPI.md#createcrmdeal) | **Post** /v1/api/crm/deals | Create a deal
[**GetCrmClientRecord**](CrmAPI.md#getcrmclientrecord) | **Get** /v1/api/crm/clients/{clientAccountId} | Show a client&#39;s record: deals, contacts, timeline, projects and invoices
[**GetCrmPipeline**](CrmAPI.md#getcrmpipeline) | **Get** /v1/api/crm/pipeline | Show the pipeline board and the last 30 days of outbound
[**ListCrmContacts**](CrmAPI.md#listcrmcontacts) | **Get** /v1/api/crm/contacts | List contacts
[**RegenerateCrmDealSuggestion**](CrmAPI.md#regeneratecrmdealsuggestion) | **Post** /v1/api/crm/deals/{dealId}/suggestion/regenerate | Have the agent write a new suggested next step and draft
[**SetCrmDealSuggestion**](CrmAPI.md#setcrmdealsuggestion) | **Put** /v1/api/crm/deals/{dealId}/suggestion | Replace a deal&#39;s suggested next step and draft with your own
[**SetCrmStageProbability**](CrmAPI.md#setcrmstageprobability) | **Put** /v1/api/crm/pipeline/stages/{stage}/probability | Set the forecast odds of an open pipeline stage
[**UpdateCrmDeal**](CrmAPI.md#updatecrmdeal) | **Patch** /v1/api/crm/deals/{dealId} | Move a deal or edit its value, owner and next step



## AddCrmNote

> CrmActivity AddCrmNote(ctx).CreateNote(createNote).XOrganizationId(xOrganizationId).Execute()

Add a note to a deal, contact or client timeline

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
	var createNote openapiclient.CreateNote
	if err := json.Unmarshal([]byte("{\"summary\":\"text\"}"), &createNote); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.AddCrmNote(ctx).CreateNote(createNote).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.AddCrmNote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddCrmNote`: CrmActivity
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.AddCrmNote`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiAddCrmNoteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createNote** | [**CreateNote**](CreateNote.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmActivity**](CrmActivity.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCrmContact

> CrmContact CreateCrmContact(ctx).CreateContact(createContact).XOrganizationId(xOrganizationId).Execute()

Create a contact

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
	var createContact openapiclient.CreateContact
	if err := json.Unmarshal([]byte("{\"clientAccountId\":\"text\",\"name\":\"text\"}"), &createContact); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.CreateCrmContact(ctx).CreateContact(createContact).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.CreateCrmContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCrmContact`: CrmContact
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.CreateCrmContact`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateCrmContactRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createContact** | [**CreateContact**](CreateContact.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmContact**](CrmContact.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCrmDeal

> CrmDeal CreateCrmDeal(ctx).CreateDeal(createDeal).XOrganizationId(xOrganizationId).Execute()

Create a deal

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
	var createDeal openapiclient.CreateDeal
	if err := json.Unmarshal([]byte("{\"clientAccountId\":\"text\",\"sourceKind\":\"play\"}"), &createDeal); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.CreateCrmDeal(ctx).CreateDeal(createDeal).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.CreateCrmDeal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCrmDeal`: CrmDeal
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.CreateCrmDeal`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateCrmDealRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDeal** | [**CreateDeal**](CreateDeal.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmDeal**](CrmDeal.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCrmClientRecord

> CrmClientRecord GetCrmClientRecord(ctx, clientAccountId).XOrganizationId(xOrganizationId).Execute()

Show a client's record: deals, contacts, timeline, projects and invoices

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
	clientAccountId := "clientAccountId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.GetCrmClientRecord(ctx, clientAccountId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.GetCrmClientRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCrmClientRecord`: CrmClientRecord
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.GetCrmClientRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**clientAccountId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCrmClientRecordRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmClientRecord**](CrmClientRecord.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCrmPipeline

> CrmBoard GetCrmPipeline(ctx).XOrganizationId(xOrganizationId).Execute()

Show the pipeline board and the last 30 days of outbound

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
	resp, r, err := apiClient.CrmAPI.GetCrmPipeline(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.GetCrmPipeline``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCrmPipeline`: CrmBoard
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.GetCrmPipeline`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetCrmPipelineRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmBoard**](CrmBoard.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCrmContacts

> []CrmContact ListCrmContacts(ctx).ClientAccountId(clientAccountId).XOrganizationId(xOrganizationId).Execute()

List contacts

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
	clientAccountId := "clientAccountId_example" // string | Only this client account's contacts. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.ListCrmContacts(ctx).ClientAccountId(clientAccountId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.ListCrmContacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCrmContacts`: []CrmContact
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.ListCrmContacts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListCrmContactsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **clientAccountId** | **string** | Only this client account&#39;s contacts. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]CrmContact**](CrmContact.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegenerateCrmDealSuggestion

> CrmRegeneratedSuggestion RegenerateCrmDealSuggestion(ctx, dealId).XOrganizationId(xOrganizationId).Execute()

Have the agent write a new suggested next step and draft

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
	dealId := "dealId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.RegenerateCrmDealSuggestion(ctx, dealId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.RegenerateCrmDealSuggestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegenerateCrmDealSuggestion`: CrmRegeneratedSuggestion
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.RegenerateCrmDealSuggestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dealId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRegenerateCrmDealSuggestionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmRegeneratedSuggestion**](CrmRegeneratedSuggestion.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetCrmDealSuggestion

> CrmDealSuggestion SetCrmDealSuggestion(ctx, dealId).DealSuggestion(dealSuggestion).XOrganizationId(xOrganizationId).Execute()

Replace a deal's suggested next step and draft with your own

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
	dealId := "dealId_example" // string |
	var dealSuggestion openapiclient.DealSuggestion
	if err := json.Unmarshal([]byte("{\"draftBody\":\"text\",\"draftSubject\":\"text\",\"step\":\"text\"}"), &dealSuggestion); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.SetCrmDealSuggestion(ctx, dealId).DealSuggestion(dealSuggestion).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.SetCrmDealSuggestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetCrmDealSuggestion`: CrmDealSuggestion
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.SetCrmDealSuggestion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dealId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSetCrmDealSuggestionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **dealSuggestion** | [**DealSuggestion**](DealSuggestion.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmDealSuggestion**](CrmDealSuggestion.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetCrmStageProbability

> CrmPipeline SetCrmStageProbability(ctx, stage).StageProbability(stageProbability).XOrganizationId(xOrganizationId).Execute()

Set the forecast odds of an open pipeline stage

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
	stage := "stage_example" // string |
	var stageProbability openapiclient.StageProbability
	if err := json.Unmarshal([]byte("{\"percent\":1}"), &stageProbability); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.SetCrmStageProbability(ctx, stage).StageProbability(stageProbability).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.SetCrmStageProbability``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetCrmStageProbability`: CrmPipeline
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.SetCrmStageProbability`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**stage** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSetCrmStageProbabilityRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **stageProbability** | [**StageProbability**](StageProbability.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmPipeline**](CrmPipeline.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCrmDeal

> CrmDeal UpdateCrmDeal(ctx, dealId).UpdateDeal(updateDeal).XOrganizationId(xOrganizationId).Execute()

Move a deal or edit its value, owner and next step

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
	dealId := "dealId_example" // string |
	var updateDeal openapiclient.UpdateDeal
	if err := json.Unmarshal([]byte("{}"), &updateDeal); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CrmAPI.UpdateCrmDeal(ctx, dealId).UpdateDeal(updateDeal).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CrmAPI.UpdateCrmDeal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCrmDeal`: CrmDeal
	fmt.Fprintf(os.Stdout, "Response from `CrmAPI.UpdateCrmDeal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**dealId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCrmDealRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDeal** | [**UpdateDeal**](UpdateDeal.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CrmDeal**](CrmDeal.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

