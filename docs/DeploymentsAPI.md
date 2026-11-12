# DeploymentsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeployProduction**](DeploymentsAPI.md#deployproduction) | **Post** /v1/api/deployments | Deploy a project to production
[**GetDeployment**](DeploymentsAPI.md#getdeployment) | **Get** /v1/api/deployments/{id} | Get one deployment
[**GetProductionCustomDomain**](DeploymentsAPI.md#getproductioncustomdomain) | **Get** /v1/api/deployments/custom-domain | Check the production deployment&#39;s custom domain
[**ListDeployments**](DeploymentsAPI.md#listdeployments) | **Get** /v1/api/deployments | List deployments
[**SetProductionCustomDomain**](DeploymentsAPI.md#setproductioncustomdomain) | **Put** /v1/api/deployments/custom-domain | Connect or remove the production deployment&#39;s custom domain
[**TouchDeployment**](DeploymentsAPI.md#touchdeployment) | **Post** /v1/api/deployments/{id}/touch | Extend a preview&#39;s time to live



## DeployProduction

> DeploymentAccepted DeployProduction(ctx).DeployProduction(deployProduction).XOrganizationId(xOrganizationId).Execute()

Deploy a project to production

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
	var deployProduction openapiclient.DeployProduction
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\"}"), &deployProduction); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeploymentsAPI.DeployProduction(ctx).DeployProduction(deployProduction).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.DeployProduction``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeployProduction`: DeploymentAccepted
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.DeployProduction`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiDeployProductionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deployProduction** | [**DeployProduction**](DeployProduction.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeploymentAccepted**](DeploymentAccepted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeployment

> Deployment GetDeployment(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one deployment

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
	resp, r, err := apiClient.DeploymentsAPI.GetDeployment(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.GetDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeployment`: Deployment
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.GetDeployment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetDeploymentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**Deployment**](Deployment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProductionCustomDomain

> CustomDomainStatus GetProductionCustomDomain(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Check the production deployment's custom domain

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
	projectId := "projectId_example" // string | The project whose custom domain to check.
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeploymentsAPI.GetProductionCustomDomain(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.GetProductionCustomDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProductionCustomDomain`: CustomDomainStatus
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.GetProductionCustomDomain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetProductionCustomDomainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | The project whose custom domain to check. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CustomDomainStatus**](CustomDomainStatus.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeployments

> []Deployment ListDeployments(ctx).ProjectId(projectId).Kind(kind).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List deployments

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
	projectId := "projectId_example" // string | Only this project's deployments. (optional)
	kind := "kind_example" // string | `project` (canonical preview), `cycle-preview` or `production`. Unrecognized values are ignored and leave the list unfiltered. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeploymentsAPI.ListDeployments(ctx).ProjectId(projectId).Kind(kind).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.ListDeployments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeployments`: []Deployment
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.ListDeployments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListDeploymentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Only this project&#39;s deployments. |
 **kind** | **string** | &#x60;project&#x60; (canonical preview), &#x60;cycle-preview&#x60; or &#x60;production&#x60;. Unrecognized values are ignored and leave the list unfiltered. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]Deployment**](Deployment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetProductionCustomDomain

> CustomDomainStatus SetProductionCustomDomain(ctx).CustomDomain(customDomain).XOrganizationId(xOrganizationId).Execute()

Connect or remove the production deployment's custom domain

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
	var customDomain openapiclient.CustomDomain
	if err := json.Unmarshal([]byte("{\"domain\":\"app.example.com\",\"projectId\":\"text\"}"), &customDomain); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeploymentsAPI.SetProductionCustomDomain(ctx).CustomDomain(customDomain).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.SetProductionCustomDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetProductionCustomDomain`: CustomDomainStatus
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.SetProductionCustomDomain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSetProductionCustomDomainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **customDomain** | [**CustomDomain**](CustomDomain.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomDomainStatus**](CustomDomainStatus.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TouchDeployment

> DeploymentTouched TouchDeployment(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Extend a preview's time to live

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
	resp, r, err := apiClient.DeploymentsAPI.TouchDeployment(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeploymentsAPI.TouchDeployment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TouchDeployment`: DeploymentTouched
	fmt.Fprintf(os.Stdout, "Response from `DeploymentsAPI.TouchDeployment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiTouchDeploymentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeploymentTouched**](DeploymentTouched.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

