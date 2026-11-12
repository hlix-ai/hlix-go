# AgentsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAgent**](AgentsAPI.md#createagent) | **Post** /v1/api/agents | Create an agent
[**DeactivateAgent**](AgentsAPI.md#deactivateagent) | **Post** /v1/api/agents/{id}/deactivate | Deactivate an agent
[**ForkAgent**](AgentsAPI.md#forkagent) | **Post** /v1/api/agents/{id}/fork | Fork an agent into a new custom one
[**GenerateAgentAvatar**](AgentsAPI.md#generateagentavatar) | **Post** /v1/api/agents/avatar-image | Generate a custom avatar using the Hlix avatar skill
[**GetAgent**](AgentsAPI.md#getagent) | **Get** /v1/api/agents/{id} | Get one agent
[**GetAgentAvatarImage**](AgentsAPI.md#getagentavatarimage) | **Get** /v1/api/agents/avatar-image | Read a generated avatar in this workspace
[**ListAgentRoles**](AgentsAPI.md#listagentroles) | **Get** /v1/api/agents/roles | List the role library the project manager hires from
[**ListAgents**](AgentsAPI.md#listagents) | **Get** /v1/api/agents | List the workspace&#39;s agents
[**UpdateAgent**](AgentsAPI.md#updateagent) | **Patch** /v1/api/agents/{id} | Update an agent



## CreateAgent

> Agent CreateAgent(ctx).CreateAgent(createAgent).XOrganizationId(xOrganizationId).Execute()

Create an agent

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
	var createAgent openapiclient.CreateAgent
	if err := json.Unmarshal([]byte("{\"name\":\"text\"}"), &createAgent); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.CreateAgent(ctx).CreateAgent(createAgent).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.CreateAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAgent`: Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.CreateAgent`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAgent** | [**CreateAgent**](CreateAgent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeactivateAgent

> Agent DeactivateAgent(ctx, id).XOrganizationId(xOrganizationId).Execute()

Deactivate an agent

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
	resp, r, err := apiClient.AgentsAPI.DeactivateAgent(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.DeactivateAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeactivateAgent`: Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.DeactivateAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeactivateAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ForkAgent

> Agent ForkAgent(ctx, id).ForkAgent(forkAgent).XOrganizationId(xOrganizationId).Execute()

Fork an agent into a new custom one

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
	var forkAgent openapiclient.ForkAgent
	if err := json.Unmarshal([]byte("{\"name\":\"text\"}"), &forkAgent); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ForkAgent(ctx, id).ForkAgent(forkAgent).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ForkAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ForkAgent`: Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ForkAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiForkAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **forkAgent** | [**ForkAgent**](ForkAgent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateAgentAvatar

> GeneratedAgentAvatar GenerateAgentAvatar(ctx).GenerateAgentAvatar(generateAgentAvatar).XOrganizationId(xOrganizationId).Execute()

Generate a custom avatar using the Hlix avatar skill

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
	var generateAgentAvatar openapiclient.GenerateAgentAvatar
	if err := json.Unmarshal([]byte("{\"prompt\":\"text\"}"), &generateAgentAvatar); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.GenerateAgentAvatar(ctx).GenerateAgentAvatar(generateAgentAvatar).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.GenerateAgentAvatar``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateAgentAvatar`: GeneratedAgentAvatar
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.GenerateAgentAvatar`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGenerateAgentAvatarRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateAgentAvatar** | [**GenerateAgentAvatar**](GenerateAgentAvatar.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GeneratedAgentAvatar**](GeneratedAgentAvatar.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgent

> Agent GetAgent(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get one agent

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
	resp, r, err := apiClient.AgentsAPI.GetAgent(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.GetAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgent`: Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.GetAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAgentAvatarImage

> AgentAvatarImage GetAgentAvatarImage(ctx).Key(key).XOrganizationId(xOrganizationId).Execute()

Read a generated avatar in this workspace

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
	key := "key_example" // string | The generated avatar key returned by this workspace.
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.GetAgentAvatarImage(ctx).Key(key).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.GetAgentAvatarImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAgentAvatarImage`: AgentAvatarImage
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.GetAgentAvatarImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetAgentAvatarImageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **string** | The generated avatar key returned by this workspace. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgentAvatarImage**](AgentAvatarImage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgentRoles

> []Role ListAgentRoles(ctx).XOrganizationId(xOrganizationId).Execute()

List the role library the project manager hires from

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
	resp, r, err := apiClient.AgentsAPI.ListAgentRoles(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ListAgentRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentRoles`: []Role
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ListAgentRoles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListAgentRolesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Role**](Role.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgents

> []Agent ListAgents(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()

List the workspace's agents

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
	projectId := "projectId_example" // string | With `projectId`, returns that project's agents and workspace-wide agents. Without it, returns all active workspace agents. Deactivated agents remain readable by ID. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.ListAgents(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.ListAgents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgents`: []Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.ListAgents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListAgentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | With &#x60;projectId&#x60;, returns that project&#39;s agents and workspace-wide agents. Without it, returns all active workspace agents. Deactivated agents remain readable by ID. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAgent

> Agent UpdateAgent(ctx, id).UpdateAgent(updateAgent).XOrganizationId(xOrganizationId).Execute()

Update an agent

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
	var updateAgent openapiclient.UpdateAgent
	if err := json.Unmarshal([]byte("{}"), &updateAgent); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AgentsAPI.UpdateAgent(ctx, id).UpdateAgent(updateAgent).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AgentsAPI.UpdateAgent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAgent`: Agent
	fmt.Fprintf(os.Stdout, "Response from `AgentsAPI.UpdateAgent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateAgentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAgent** | [**UpdateAgent**](UpdateAgent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Agent**](Agent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

