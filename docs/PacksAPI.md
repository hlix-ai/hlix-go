# PacksAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AttachProjectPack**](PacksAPI.md#attachprojectpack) | **Post** /v1/api/packs/project/{projectId} | Attach a pack to a project
[**CreateCustomSkill**](PacksAPI.md#createcustomskill) | **Post** /v1/api/packs/custom-skills | Write a custom skill
[**DeleteCustomSkill**](PacksAPI.md#deletecustomskill) | **Delete** /v1/api/packs/custom-skills/{slug} | Delete a custom skill
[**DetachProjectPack**](PacksAPI.md#detachprojectpack) | **Delete** /v1/api/packs/{id} | Detach a pack from a project
[**GenerateCustomSkill**](PacksAPI.md#generatecustomskill) | **Post** /v1/api/packs/custom-skills/generate | Draft a custom skill without saving it
[**GetCustomSkill**](PacksAPI.md#getcustomskill) | **Get** /v1/api/packs/custom-skills/{slug} | Get one custom skill
[**ListAvailablePacks**](PacksAPI.md#listavailablepacks) | **Get** /v1/api/packs | List every pack the registry knows
[**ListCustomSkills**](PacksAPI.md#listcustomskills) | **Get** /v1/api/packs/custom-skills | List the workspace&#39;s own skills
[**ListProjectPacks**](PacksAPI.md#listprojectpacks) | **Get** /v1/api/packs/project/{projectId} | List a project&#39;s attached packs
[**UpdateCustomSkill**](PacksAPI.md#updatecustomskill) | **Patch** /v1/api/packs/custom-skills/{slug} | Update a custom skill
[**UpdateProjectPack**](PacksAPI.md#updateprojectpack) | **Patch** /v1/api/packs/{id} | Toggle an attached pack



## AttachProjectPack

> ProjectPack AttachProjectPack(ctx, projectId).ActivatePack(activatePack).XOrganizationId(xOrganizationId).Execute()

Attach a pack to a project

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
	var activatePack openapiclient.ActivatePack
	if err := json.Unmarshal([]byte("{\"packName\":\"text\"}"), &activatePack); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.AttachProjectPack(ctx, projectId).ActivatePack(activatePack).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.AttachProjectPack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AttachProjectPack`: ProjectPack
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.AttachProjectPack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAttachProjectPackRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **activatePack** | [**ActivatePack**](ActivatePack.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectPack**](ProjectPack.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCustomSkill

> CustomSkill CreateCustomSkill(ctx).CreateCustomSkill(createCustomSkill).XOrganizationId(xOrganizationId).Execute()

Write a custom skill

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
	var createCustomSkill openapiclient.CreateCustomSkill
	if err := json.Unmarshal([]byte("{\"content\":\"text\",\"description\":\"text\",\"name\":\"text\",\"slug\":\"text\"}"), &createCustomSkill); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.CreateCustomSkill(ctx).CreateCustomSkill(createCustomSkill).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.CreateCustomSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCustomSkill`: CustomSkill
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.CreateCustomSkill`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateCustomSkillRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCustomSkill** | [**CreateCustomSkill**](CreateCustomSkill.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomSkill**](CustomSkill.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCustomSkill

> DeletedAck DeleteCustomSkill(ctx, slug).XOrganizationId(xOrganizationId).Execute()

Delete a custom skill

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
	slug := "slug_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.DeleteCustomSkill(ctx, slug).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.DeleteCustomSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCustomSkill`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.DeleteCustomSkill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteCustomSkillRequest` request builder.


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


## DetachProjectPack

> DeletedAck DetachProjectPack(ctx, id).XOrganizationId(xOrganizationId).Execute()

Detach a pack from a project

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
	resp, r, err := apiClient.PacksAPI.DetachProjectPack(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.DetachProjectPack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetachProjectPack`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.DetachProjectPack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDetachProjectPackRequest` request builder.


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


## GenerateCustomSkill

> GeneratedSkillDraft GenerateCustomSkill(ctx).GenerateCustomSkill(generateCustomSkill).XOrganizationId(xOrganizationId).Execute()

Draft a custom skill without saving it

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
	var generateCustomSkill openapiclient.GenerateCustomSkill
	if err := json.Unmarshal([]byte("{\"description\":\"text\"}"), &generateCustomSkill); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.GenerateCustomSkill(ctx).GenerateCustomSkill(generateCustomSkill).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.GenerateCustomSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateCustomSkill`: GeneratedSkillDraft
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.GenerateCustomSkill`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGenerateCustomSkillRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateCustomSkill** | [**GenerateCustomSkill**](GenerateCustomSkill.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GeneratedSkillDraft**](GeneratedSkillDraft.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCustomSkill

> CustomSkill GetCustomSkill(ctx, slug).XOrganizationId(xOrganizationId).Execute()

Get one custom skill

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
	slug := "slug_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.GetCustomSkill(ctx, slug).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.GetCustomSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCustomSkill`: CustomSkill
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.GetCustomSkill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCustomSkillRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomSkill**](CustomSkill.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAvailablePacks

> []AvailablePack ListAvailablePacks(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()

List every pack the registry knows

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
	projectId := "projectId_example" // string | Report attachment state for this project. Without `projectId`, every entry has `isActive: false`; this indicates that no project was selected. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.ListAvailablePacks(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.ListAvailablePacks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAvailablePacks`: []AvailablePack
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.ListAvailablePacks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListAvailablePacksRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Report attachment state for this project. Without &#x60;projectId&#x60;, every entry has &#x60;isActive: false&#x60;; this indicates that no project was selected. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]AvailablePack**](AvailablePack.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCustomSkills

> []CustomSkill ListCustomSkills(ctx).XOrganizationId(xOrganizationId).Execute()

List the workspace's own skills

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
	resp, r, err := apiClient.PacksAPI.ListCustomSkills(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.ListCustomSkills``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCustomSkills`: []CustomSkill
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.ListCustomSkills`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListCustomSkillsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]CustomSkill**](CustomSkill.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectPacks

> []ProjectPack ListProjectPacks(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

List a project's attached packs

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
	resp, r, err := apiClient.PacksAPI.ListProjectPacks(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.ListProjectPacks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectPacks`: []ProjectPack
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.ListProjectPacks`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectPacksRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ProjectPack**](ProjectPack.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCustomSkill

> CustomSkill UpdateCustomSkill(ctx, slug).UpdateCustomSkill(updateCustomSkill).XOrganizationId(xOrganizationId).Execute()

Update a custom skill

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
	slug := "slug_example" // string |
	var updateCustomSkill openapiclient.UpdateCustomSkill
	if err := json.Unmarshal([]byte("{}"), &updateCustomSkill); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.UpdateCustomSkill(ctx, slug).UpdateCustomSkill(updateCustomSkill).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.UpdateCustomSkill``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCustomSkill`: CustomSkill
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.UpdateCustomSkill`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCustomSkillRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCustomSkill** | [**UpdateCustomSkill**](UpdateCustomSkill.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomSkill**](CustomSkill.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProjectPack

> ProjectPack UpdateProjectPack(ctx, id).UpdatePack(updatePack).XOrganizationId(xOrganizationId).Execute()

Toggle an attached pack

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
	var updatePack openapiclient.UpdatePack
	if err := json.Unmarshal([]byte("{\"isActive\":true}"), &updatePack); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PacksAPI.UpdateProjectPack(ctx, id).UpdatePack(updatePack).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PacksAPI.UpdateProjectPack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProjectPack`: ProjectPack
	fmt.Fprintf(os.Stdout, "Response from `PacksAPI.UpdateProjectPack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateProjectPackRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePack** | [**UpdatePack**](UpdatePack.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectPack**](ProjectPack.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

