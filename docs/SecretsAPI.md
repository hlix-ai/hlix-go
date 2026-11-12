# SecretsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProjectSecretsConfig**](SecretsAPI.md#createprojectsecretsconfig) | **Post** /v1/api/secrets/project/{projectId} | Configure a secrets provider
[**DeleteProjectSecretEntry**](SecretsAPI.md#deleteprojectsecretentry) | **Delete** /v1/api/secrets/project/{projectId}/entries/{key} | Remove one secret from the project store
[**DeleteProjectSecretsConfig**](SecretsAPI.md#deleteprojectsecretsconfig) | **Delete** /v1/api/secrets/project/{projectId}/{configId} | Delete a secrets config
[**ExportProjectSecrets**](SecretsAPI.md#exportprojectsecrets) | **Post** /v1/api/secrets/project/{projectId}/export | Export one source file&#39;s secrets, values in clear
[**ImportProjectSecretFiles**](SecretsAPI.md#importprojectsecretfiles) | **Put** /v1/api/secrets/project/{projectId}/files | Upload whole secret files and let the store parse them
[**ListProjectSecretEntries**](SecretsAPI.md#listprojectsecretentries) | **Get** /v1/api/secrets/project/{projectId}/entries | List the project&#39;s secrets, masked, with the file each belongs to
[**ListProjectSecretsConfigs**](SecretsAPI.md#listprojectsecretsconfigs) | **Get** /v1/api/secrets/project/{projectId} | List a project&#39;s secrets configs
[**ListProjectSecretsSyncLogs**](SecretsAPI.md#listprojectsecretssynclogs) | **Get** /v1/api/secrets/project/{projectId}/sync-logs | List a project&#39;s secrets sync history
[**TestProjectSecrets**](SecretsAPI.md#testprojectsecrets) | **Post** /v1/api/secrets/project/{projectId}/test | Resolve the project&#39;s secrets and report the key names
[**UpdateProjectSecretsConfig**](SecretsAPI.md#updateprojectsecretsconfig) | **Patch** /v1/api/secrets/project/{projectId}/{configId} | Update a secrets config
[**UpsertProjectSecretEntries**](SecretsAPI.md#upsertprojectsecretentries) | **Put** /v1/api/secrets/project/{projectId}/entries | Create or replace secrets in the project store



## CreateProjectSecretsConfig

> SecretsConfig CreateProjectSecretsConfig(ctx, projectId).CreateSecretsConfig(createSecretsConfig).XOrganizationId(xOrganizationId).Execute()

Configure a secrets provider

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
	createSecretsConfig := openapiclient.CreateSecretsConfig{CreateSecretsConfigOneOf: openapiclient.NewCreateSecretsConfigOneOf(*openapiclient.NewCreateSecretsConfigOneOfConfig("ClientId_example", "ClientSecret_example", "Environment_example", "ProjectId_example"), "Label_example", "Provider_example")} // CreateSecretsConfig |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.CreateProjectSecretsConfig(ctx, projectId).CreateSecretsConfig(createSecretsConfig).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.CreateProjectSecretsConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProjectSecretsConfig`: SecretsConfig
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.CreateProjectSecretsConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCreateProjectSecretsConfigRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createSecretsConfig** | [**CreateSecretsConfig**](CreateSecretsConfig.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretsConfig**](SecretsConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProjectSecretEntry

> SecretEntryDeleted DeleteProjectSecretEntry(ctx, projectId, key).Source(source).XOrganizationId(xOrganizationId).Execute()

Remove one secret from the project store

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
	key := "key_example" // string |
	source := "source_example" // string | Remove the key only from this source file. If omitted, remove it from every file that declares it. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.DeleteProjectSecretEntry(ctx, projectId, key).Source(source).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.DeleteProjectSecretEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProjectSecretEntry`: SecretEntryDeleted
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.DeleteProjectSecretEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**key** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteProjectSecretEntryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **source** | **string** | Remove the key only from this source file. If omitted, remove it from every file that declares it. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretEntryDeleted**](SecretEntryDeleted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProjectSecretsConfig

> DeletedAck DeleteProjectSecretsConfig(ctx, projectId, configId).XOrganizationId(xOrganizationId).Execute()

Delete a secrets config

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
	configId := "configId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.DeleteProjectSecretsConfig(ctx, projectId, configId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.DeleteProjectSecretsConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProjectSecretsConfig`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.DeleteProjectSecretsConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**configId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteProjectSecretsConfigRequest` request builder.


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


## ExportProjectSecrets

> *os.File ExportProjectSecrets(ctx, projectId).ExportSecrets(exportSecrets).XOrganizationId(xOrganizationId).Execute()

Export one source file's secrets, values in clear

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
	var exportSecrets openapiclient.ExportSecrets
	if err := json.Unmarshal([]byte("{}"), &exportSecrets); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ExportProjectSecrets(ctx, projectId).ExportSecrets(exportSecrets).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.ExportProjectSecrets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportProjectSecrets`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.ExportProjectSecrets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiExportProjectSecretsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **exportSecrets** | [**ExportSecrets**](ExportSecrets.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportProjectSecretFiles

> SecretFilesImported ImportProjectSecretFiles(ctx, projectId).ImportSecretFiles(importSecretFiles).XOrganizationId(xOrganizationId).Execute()

Upload whole secret files and let the store parse them

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
	var importSecretFiles openapiclient.ImportSecretFiles
	if err := json.Unmarshal([]byte("{\"files\":[{\"contentBase64\":\"text\",\"path\":\"text\"}]}"), &importSecretFiles); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ImportProjectSecretFiles(ctx, projectId).ImportSecretFiles(importSecretFiles).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.ImportProjectSecretFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportProjectSecretFiles`: SecretFilesImported
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.ImportProjectSecretFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiImportProjectSecretFilesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importSecretFiles** | [**ImportSecretFiles**](ImportSecretFiles.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretFilesImported**](SecretFilesImported.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectSecretEntries

> SecretEntries ListProjectSecretEntries(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

List the project's secrets, masked, with the file each belongs to

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
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretEntries(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.ListProjectSecretEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectSecretEntries`: SecretEntries
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.ListProjectSecretEntries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectSecretEntriesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretEntries**](SecretEntries.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectSecretsConfigs

> []SecretsConfigSummary ListProjectSecretsConfigs(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

List a project's secrets configs

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
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretsConfigs(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.ListProjectSecretsConfigs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectSecretsConfigs`: []SecretsConfigSummary
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.ListProjectSecretsConfigs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectSecretsConfigsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]SecretsConfigSummary**](SecretsConfigSummary.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectSecretsSyncLogs

> []SecretsSyncLog ListProjectSecretsSyncLogs(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

List a project's secrets sync history

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
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretsSyncLogs(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.ListProjectSecretsSyncLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectSecretsSyncLogs`: []SecretsSyncLog
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.ListProjectSecretsSyncLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectSecretsSyncLogsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]SecretsSyncLog**](SecretsSyncLog.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestProjectSecrets

> SecretsProbe TestProjectSecrets(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Resolve the project's secrets and report the key names

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
	resp, r, err := apiClient.SecretsAPI.TestProjectSecrets(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.TestProjectSecrets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestProjectSecrets`: SecretsProbe
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.TestProjectSecrets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiTestProjectSecretsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretsProbe**](SecretsProbe.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProjectSecretsConfig

> SecretsConfig UpdateProjectSecretsConfig(ctx, projectId, configId).UpdateSecretsConfig(updateSecretsConfig).XOrganizationId(xOrganizationId).Execute()

Update a secrets config

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
	configId := "configId_example" // string |
	var updateSecretsConfig openapiclient.UpdateSecretsConfig
	if err := json.Unmarshal([]byte("{}"), &updateSecretsConfig); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.UpdateProjectSecretsConfig(ctx, projectId, configId).UpdateSecretsConfig(updateSecretsConfig).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.UpdateProjectSecretsConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProjectSecretsConfig`: SecretsConfig
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.UpdateProjectSecretsConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**configId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateProjectSecretsConfigRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateSecretsConfig** | [**UpdateSecretsConfig**](UpdateSecretsConfig.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretsConfig**](SecretsConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertProjectSecretEntries

> SecretEntriesWritten UpsertProjectSecretEntries(ctx, projectId).UpsertSecretEntries(upsertSecretEntries).XOrganizationId(xOrganizationId).Execute()

Create or replace secrets in the project store

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
	var upsertSecretEntries openapiclient.UpsertSecretEntries
	if err := json.Unmarshal([]byte("{\"entries\":[{\"key\":\"text\",\"value\":\"text\"}]}"), &upsertSecretEntries); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.UpsertProjectSecretEntries(ctx, projectId).UpsertSecretEntries(upsertSecretEntries).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecretsAPI.UpsertProjectSecretEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertProjectSecretEntries`: SecretEntriesWritten
	fmt.Fprintf(os.Stdout, "Response from `SecretsAPI.UpsertProjectSecretEntries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpsertProjectSecretEntriesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertSecretEntries** | [**UpsertSecretEntries**](UpsertSecretEntries.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SecretEntriesWritten**](SecretEntriesWritten.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

