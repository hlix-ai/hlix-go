# ImportsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ImportProjectAgent**](ImportsAPI.md#importprojectagent) | **Post** /v1/api/projects/{id}/resources/agent | Create a project-scoped agent from local instructions
[**ImportProjectMcp**](ImportsAPI.md#importprojectmcp) | **Post** /v1/api/projects/{id}/resources/mcp | Explicitly activate a validated MCP server for one project
[**ImportProjectSkill**](ImportsAPI.md#importprojectskill) | **Post** /v1/api/projects/{id}/resources/skill | Activate a skill for one project



## ImportProjectAgent

> ImportedAgent ImportProjectAgent(ctx, id).ImportAgent(importAgent).XOrganizationId(xOrganizationId).Execute()

Create a project-scoped agent from local instructions

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
	var importAgent openapiclient.ImportAgent
	if err := json.Unmarshal([]byte("{\"instructions\":\"text\",\"name\":\"text\"}"), &importAgent); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectAgent(ctx, id).ImportAgent(importAgent).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiImportProjectAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importAgent** | [**ImportAgent**](ImportAgent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ImportedAgent**](ImportedAgent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var importMcp openapiclient.ImportMcp
	if err := json.Unmarshal([]byte("{\"name\":\"text\",\"transport\":\"stdio\"}"), &importMcp); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectMcp(ctx, id).ImportMcp(importMcp).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiImportProjectMcpRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importMcp** | [**ImportMcp**](ImportMcp.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ImportedMcp**](ImportedMcp.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportProjectSkill

> ImportedSkill ImportProjectSkill(ctx, id).ImportSkill(importSkill).XOrganizationId(xOrganizationId).Execute()

Activate a skill for one project

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
	var importSkill openapiclient.ImportSkill
	if err := json.Unmarshal([]byte("{\"content\":\"text\",\"slug\":\"text\"}"), &importSkill); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ImportsAPI.ImportProjectSkill(ctx, id).ImportSkill(importSkill).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiImportProjectSkillRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importSkill** | [**ImportSkill**](ImportSkill.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ImportedSkill**](ImportedSkill.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

