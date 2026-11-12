# EnvironmentsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProjectEnvironment**](EnvironmentsAPI.md#createprojectenvironment) | **Post** /v1/api/environments/project/{projectId} | Create an environment
[**DeleteProjectEnvironment**](EnvironmentsAPI.md#deleteprojectenvironment) | **Delete** /v1/api/environments/project/{projectId}/{id} | Delete an environment
[**ListProjectEnvironments**](EnvironmentsAPI.md#listprojectenvironments) | **Get** /v1/api/environments/project/{projectId} | List a project&#39;s environments
[**UpdateProjectEnvironment**](EnvironmentsAPI.md#updateprojectenvironment) | **Patch** /v1/api/environments/project/{projectId}/{id} | Update an environment



## CreateProjectEnvironment

> Environment CreateProjectEnvironment(ctx, projectId).CreateEnvironment(createEnvironment).XOrganizationId(xOrganizationId).Execute()

Create an environment

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
	var createEnvironment openapiclient.CreateEnvironment
	if err := json.Unmarshal([]byte("{\"config\":{},\"label\":\"text\"}"), &createEnvironment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnvironmentsAPI.CreateProjectEnvironment(ctx, projectId).CreateEnvironment(createEnvironment).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsAPI.CreateProjectEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProjectEnvironment`: Environment
	fmt.Fprintf(os.Stdout, "Response from `EnvironmentsAPI.CreateProjectEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCreateProjectEnvironmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createEnvironment** | [**CreateEnvironment**](CreateEnvironment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Environment**](Environment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProjectEnvironment

> DeletedAck DeleteProjectEnvironment(ctx, projectId, id).XOrganizationId(xOrganizationId).Execute()

Delete an environment

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
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnvironmentsAPI.DeleteProjectEnvironment(ctx, projectId, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsAPI.DeleteProjectEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProjectEnvironment`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `EnvironmentsAPI.DeleteProjectEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteProjectEnvironmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectEnvironments

> []Environment ListProjectEnvironments(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

List a project's environments

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
	resp, r, err := apiClient.EnvironmentsAPI.ListProjectEnvironments(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsAPI.ListProjectEnvironments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectEnvironments`: []Environment
	fmt.Fprintf(os.Stdout, "Response from `EnvironmentsAPI.ListProjectEnvironments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectEnvironmentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Environment**](Environment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProjectEnvironment

> Environment UpdateProjectEnvironment(ctx, projectId, id).UpdateEnvironment(updateEnvironment).XOrganizationId(xOrganizationId).Execute()

Update an environment

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
	id := "id_example" // string |
	var updateEnvironment openapiclient.UpdateEnvironment
	if err := json.Unmarshal([]byte("{}"), &updateEnvironment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EnvironmentsAPI.UpdateProjectEnvironment(ctx, projectId, id).UpdateEnvironment(updateEnvironment).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EnvironmentsAPI.UpdateProjectEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProjectEnvironment`: Environment
	fmt.Fprintf(os.Stdout, "Response from `EnvironmentsAPI.UpdateProjectEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateProjectEnvironmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateEnvironment** | [**UpdateEnvironment**](UpdateEnvironment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Environment**](Environment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

