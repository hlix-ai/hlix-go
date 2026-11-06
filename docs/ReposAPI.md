# \ReposAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateRepoAccess**](ReposAPI.md#CreateRepoAccess) | **Post** /v1/api/projects/{id}/repos/{repoId}/access | Get short-lived Git access to a repository in HLIX Repos
[**GetProjectProtectedFiles**](ReposAPI.md#GetProjectProtectedFiles) | **Get** /v1/api/projects/{id}/protected-files | Read encrypted project files with manage access
[**GetRepoHead**](ReposAPI.md#GetRepoHead) | **Get** /v1/api/projects/{id}/repos/{repoId}/head | Read a repository head without waking its workspace



## CreateRepoAccess

> RepoAccessResponse CreateRepoAccess(ctx, id, repoId).RepoAccess(repoAccess).XOrganizationId(xOrganizationId).Execute()

Get short-lived Git access to a repository in HLIX Repos

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
	repoId := "repoId_example" // string | 
	repoAccess := *openapiclient.NewRepoAccess("Scope_example") // RepoAccess | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReposAPI.CreateRepoAccess(context.Background(), id, repoId).RepoAccess(repoAccess).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCreateRepoAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **repoAccess** | [**RepoAccess**](RepoAccess.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**RepoAccessResponse**](RepoAccessResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReposAPI.GetProjectProtectedFiles(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetProjectProtectedFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectProtectedFiles**](ProjectProtectedFiles.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRepoHead

> RepoHeadResponse GetRepoHead(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()

Read a repository head without waking its workspace

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
	repoId := "repoId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReposAPI.GetRepoHead(context.Background(), id, repoId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetRepoHeadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**RepoHeadResponse**](RepoHeadResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

