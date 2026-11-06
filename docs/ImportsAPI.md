# \ImportsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ImportProjectAgent**](ImportsAPI.md#ImportProjectAgent) | **Post** /v1/api/projects/{id}/resources/agent | Create a project-scoped agent from local instructions
[**ImportProjectMcp**](ImportsAPI.md#ImportProjectMcp) | **Post** /v1/api/projects/{id}/resources/mcp | Explicitly activate a validated MCP server for one project
[**ImportProjectSkill**](ImportsAPI.md#ImportProjectSkill) | **Post** /v1/api/projects/{id}/resources/skill | Explicitly activate a quarantined skill for one project



## ImportProjectAgent

> ImportedAgent ImportProjectAgent(ctx, id).ImportAgent(importAgent).XOrganizationId(xOrganizationId).Execute()

Create a project-scoped agent from local instructions

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
	importAgent := *openapiclient.NewImportAgent("Instructions_example", "Name_example") // ImportAgent | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectAgent(context.Background(), id).ImportAgent(importAgent).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportsAPI.ImportProjectAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportProjectAgent`: ImportedAgent
	fmt.Fprintf(os.Stdout, "Response from `ImportsAPI.ImportProjectAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiImportProjectAgentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importAgent** | [**ImportAgent**](ImportAgent.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ImportedAgent**](ImportedAgent.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportProjectMcp

> ImportedMcp ImportProjectMcp(ctx, id).ImportMcp(importMcp).XOrganizationId(xOrganizationId).Execute()

Explicitly activate a validated MCP server for one project

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
	importMcp := *openapiclient.NewImportMcp("Name_example", "Transport_example") // ImportMcp | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectMcp(context.Background(), id).ImportMcp(importMcp).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportsAPI.ImportProjectMcp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportProjectMcp`: ImportedMcp
	fmt.Fprintf(os.Stdout, "Response from `ImportsAPI.ImportProjectMcp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiImportProjectMcpRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importMcp** | [**ImportMcp**](ImportMcp.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ImportedMcp**](ImportedMcp.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportProjectSkill

> ImportedSkill ImportProjectSkill(ctx, id).ImportSkill(importSkill).XOrganizationId(xOrganizationId).Execute()

Explicitly activate a quarantined skill for one project

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
	importSkill := *openapiclient.NewImportSkill("Content_example", "Slug_example") // ImportSkill | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectSkill(context.Background(), id).ImportSkill(importSkill).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ImportsAPI.ImportProjectSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportProjectSkill`: ImportedSkill
	fmt.Fprintf(os.Stdout, "Response from `ImportsAPI.ImportProjectSkill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiImportProjectSkillRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importSkill** | [**ImportSkill**](ImportSkill.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ImportedSkill**](ImportedSkill.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

