# ClientPortalAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApproveClientRequest**](ClientPortalAPI.md#approveclientrequest) | **Post** /v1/api/client-portal/requests/{id}/approve | Approve the exact saved plan once and enter operator sources
[**CreateClientRequest**](ClientPortalAPI.md#createclientrequest) | **Post** /v1/api/client-portal/requests | Start a personal request conversation visible to the agency
[**DownloadClientRequestAttachment**](ClientPortalAPI.md#downloadclientrequestattachment) | **Get** /v1/api/client-portal/requests/{id}/attachments/{attachmentId} | Read a request-owned attachment
[**GetClientPortalOverview**](ClientPortalAPI.md#getclientportaloverview) | **Get** /v1/api/client-portal/overview | Get the portal landing view
[**GetClientRequest**](ClientPortalAPI.md#getclientrequest) | **Get** /v1/api/client-portal/requests/{id} | Read an authorized request and its canonical conversation
[**ListClientPortalActivity**](ClientPortalAPI.md#listclientportalactivity) | **Get** /v1/api/client-portal/activity | List client-visible activity
[**ListClientRequests**](ClientPortalAPI.md#listclientrequests) | **Get** /v1/api/client-portal/requests | List your personal requests or the agency&#39;s client requests
[**UploadClientRequestAttachment**](ClientPortalAPI.md#uploadclientrequestattachment) | **Post** /v1/api/client-portal/requests/{id}/attachments | Upload a request-owned file or voice recording



## ApproveClientRequest

> ClientRequestDetail ApproveClientRequest(ctx, id).ApproveClientRequest(approveClientRequest).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Approve the exact saved plan once and enter operator sources

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
	var approveClientRequest openapiclient.ApproveClientRequest
	if err := json.Unmarshal([]byte("{\"hash\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"revision\":2}"), &approveClientRequest); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.ApproveClientRequest(ctx, id).ApproveClientRequest(approveClientRequest).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.ApproveClientRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveClientRequest`: ClientRequestDetail
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.ApproveClientRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiApproveClientRequestRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **approveClientRequest** | [**ApproveClientRequest**](ApproveClientRequest.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientRequestDetail**](ClientRequestDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateClientRequest

> ClientRequestDetail CreateClientRequest(ctx).CreateClientRequest(createClientRequest).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Start a personal request conversation visible to the agency

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
	var createClientRequest openapiclient.CreateClientRequest
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\"}"), &createClientRequest); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.CreateClientRequest(ctx).CreateClientRequest(createClientRequest).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.CreateClientRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateClientRequest`: ClientRequestDetail
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.CreateClientRequest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateClientRequestRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createClientRequest** | [**CreateClientRequest**](CreateClientRequest.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientRequestDetail**](ClientRequestDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadClientRequestAttachment

> *os.File DownloadClientRequestAttachment(ctx, id, attachmentId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a request-owned attachment

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
	attachmentId := "attachmentId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.DownloadClientRequestAttachment(ctx, id, attachmentId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.DownloadClientRequestAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadClientRequestAttachment`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.DownloadClientRequestAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**attachmentId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDownloadClientRequestAttachmentRequest` request builder.


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
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientPortalOverview

> ClientPortalOverview GetClientPortalOverview(ctx).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the portal landing view

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
	resp, r, err := apiClient.ClientPortalAPI.GetClientPortalOverview(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.GetClientPortalOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientPortalOverview`: ClientPortalOverview
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.GetClientPortalOverview`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetClientPortalOverviewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientPortalOverview**](ClientPortalOverview.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientRequest

> ClientRequestDetail GetClientRequest(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read an authorized request and its canonical conversation

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
	resp, r, err := apiClient.ClientPortalAPI.GetClientRequest(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.GetClientRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientRequest`: ClientRequestDetail
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.GetClientRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientRequestRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientRequestDetail**](ClientRequestDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListClientPortalActivity

> []ClientActivityItem ListClientPortalActivity(ctx).Type_(type_).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List client-visible activity

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
	type_ := "type__example" // string | One `ClientActivityType`, applied on the server before the twenty-item overview limit. An unrecognized type returns an empty list. (optional)
	limit := "limit_example" // string | Page size, clamped to 1–500; 100 when omitted or not an integer. (optional)
	offset := "offset_example" // string | Items to skip, newest first. Ask for the next page with `offset` + `limit` until a page comes back shorter than `limit`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.ListClientPortalActivity(ctx).Type_(type_).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.ListClientPortalActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListClientPortalActivity`: []ClientActivityItem
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.ListClientPortalActivity`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListClientPortalActivityRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type_** | **string** | One &#x60;ClientActivityType&#x60;, applied on the server before the twenty-item overview limit. An unrecognized type returns an empty list. |
 **limit** | **string** | Page size, clamped to 1–500; 100 when omitted or not an integer. |
 **offset** | **string** | Items to skip, newest first. Ask for the next page with &#x60;offset&#x60; + &#x60;limit&#x60; until a page comes back shorter than &#x60;limit&#x60;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]ClientActivityItem**](ClientActivityItem.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListClientRequests

> ClientRequestList ListClientRequests(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List your personal requests or the agency's client requests

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
	projectId := "projectId_example" // string | Limit to this accessible project (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.ListClientRequests(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.ListClientRequests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListClientRequests`: ClientRequestList
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.ListClientRequests`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListClientRequestsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Limit to this accessible project |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ClientRequestList**](ClientRequestList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadClientRequestAttachment

> ChatAttachment UploadClientRequestAttachment(ctx, id).File(file).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Upload a request-owned file or voice recording

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
	file := os.NewFile(1234, "some_file") // *os.File |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalAPI.UploadClientRequestAttachment(ctx, id).File(file).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalAPI.UploadClientRequestAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadClientRequestAttachment`: ChatAttachment
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalAPI.UploadClientRequestAttachment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUploadClientRequestAttachmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **file** | ***os.File** |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ChatAttachment**](ChatAttachment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

