# ReposAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateRepoAccess**](ReposAPI.md#createrepoaccess) | **Post** /v1/api/projects/{id}/repos/{repoId}/access | Get short-lived Git access to a repository in HLIX Repos
[**GetProjectProtectedFiles**](ReposAPI.md#getprojectprotectedfiles) | **Get** /v1/api/projects/{id}/protected-files | Read encrypted project files with manage access
[**GetRepoHead**](ReposAPI.md#getrepohead) | **Get** /v1/api/projects/{id}/repos/{repoId}/head | Read a repository head without starting a Cloud Machine



## CreateRepoAccess

> RepoAccessResponse CreateRepoAccess(ctx, id, repoId).RepoAccess(repoAccess).XOrganizationId(xOrganizationId).Execute()

Get short-lived Git access to a repository in HLIX Repos

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
	repoId := "repoId_example" // string |
	var repoAccess openapiclient.RepoAccess
	if err := json.Unmarshal([]byte("{\"scope\":\"read\"}"), &repoAccess); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReposAPI.CreateRepoAccess(ctx, id, repoId).RepoAccess(repoAccess).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReposAPI.CreateRepoAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRepoAccess`: RepoAccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ReposAPI.CreateRepoAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**repoId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCreateRepoAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **repoAccess** | [**RepoAccess**](RepoAccess.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**RepoAccessResponse**](RepoAccessResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectProtectedFiles

> ProjectProtectedFiles GetProjectProtectedFiles(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read encrypted project files with manage access

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
	resp, r, err := apiClient.ReposAPI.GetProjectProtectedFiles(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReposAPI.GetProjectProtectedFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectProtectedFiles`: ProjectProtectedFiles
	fmt.Fprintf(os.Stdout, "Response from `ReposAPI.GetProjectProtectedFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectProtectedFilesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectProtectedFiles**](ProjectProtectedFiles.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRepoHead

> RepoHeadResponse GetRepoHead(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()

Read a repository head without starting a Cloud Machine

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
	repoId := "repoId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReposAPI.GetRepoHead(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReposAPI.GetRepoHead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRepoHead`: RepoHeadResponse
	fmt.Fprintf(os.Stdout, "Response from `ReposAPI.GetRepoHead`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**repoId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetRepoHeadRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**RepoHeadResponse**](RepoHeadResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

