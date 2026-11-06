# \SecretsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProjectSecretsConfig**](SecretsAPI.md#CreateProjectSecretsConfig) | **Post** /v1/api/secrets/project/{projectId} | Configure a secrets provider
[**DeleteProjectSecretEntry**](SecretsAPI.md#DeleteProjectSecretEntry) | **Delete** /v1/api/secrets/project/{projectId}/entries/{key} | Remove one secret from the project store
[**DeleteProjectSecretsConfig**](SecretsAPI.md#DeleteProjectSecretsConfig) | **Delete** /v1/api/secrets/project/{projectId}/{configId} | Delete a secrets config
[**ExportProjectSecrets**](SecretsAPI.md#ExportProjectSecrets) | **Post** /v1/api/secrets/project/{projectId}/export | Export one source file&#39;s secrets, values in clear
[**ImportProjectSecretFiles**](SecretsAPI.md#ImportProjectSecretFiles) | **Put** /v1/api/secrets/project/{projectId}/files | Upload whole secret files and let the store parse them
[**ListProjectSecretEntries**](SecretsAPI.md#ListProjectSecretEntries) | **Get** /v1/api/secrets/project/{projectId}/entries | List the project&#39;s secrets, masked, with the file each belongs to
[**ListProjectSecretsConfigs**](SecretsAPI.md#ListProjectSecretsConfigs) | **Get** /v1/api/secrets/project/{projectId} | List a project&#39;s secrets configs
[**ListProjectSecretsSyncLogs**](SecretsAPI.md#ListProjectSecretsSyncLogs) | **Get** /v1/api/secrets/project/{projectId}/sync-logs | List a project&#39;s secrets sync history
[**TestProjectSecrets**](SecretsAPI.md#TestProjectSecrets) | **Post** /v1/api/secrets/project/{projectId}/test | Resolve the project&#39;s secrets and report the key names
[**UpdateProjectSecretsConfig**](SecretsAPI.md#UpdateProjectSecretsConfig) | **Patch** /v1/api/secrets/project/{projectId}/{configId} | Update a secrets config
[**UpsertProjectSecretEntries**](SecretsAPI.md#UpsertProjectSecretEntries) | **Put** /v1/api/secrets/project/{projectId}/entries | Create or replace secrets in the project store



## CreateProjectSecretsConfig

> SecretsConfig CreateProjectSecretsConfig(ctx, projectId).CreateSecretsConfig(createSecretsConfig).XOrganizationId(xOrganizationId).Execute()

Configure a secrets provider

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
	projectId := "projectId_example" // string | 
	createSecretsConfig := openapiclient.CreateSecretsConfig{CreateSecretsConfigOneOf: openapiclient.NewCreateSecretsConfigOneOf(*openapiclient.NewCreateSecretsConfigOneOfConfig("ClientId_example", "ClientSecret_example", "Environment_example", "ProjectId_example"), "Label_example", "Provider_example")} // CreateSecretsConfig | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.CreateProjectSecretsConfig(context.Background(), projectId).CreateSecretsConfig(createSecretsConfig).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCreateProjectSecretsConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createSecretsConfig** | [**CreateSecretsConfig**](CreateSecretsConfig.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretsConfig**](SecretsConfig.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	key := "key_example" // string | 
	source := "source_example" // string | Remove the key only from this source file. Omitted, the key is removed from EVERY file that declares it. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.DeleteProjectSecretEntry(context.Background(), projectId, key).Source(source).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiDeleteProjectSecretEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **source** | **string** | Remove the key only from this source file. Omitted, the key is removed from EVERY file that declares it. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretEntryDeleted**](SecretEntryDeleted.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	configId := "configId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.DeleteProjectSecretsConfig(context.Background(), projectId, configId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiDeleteProjectSecretsConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	exportSecrets := *openapiclient.NewExportSecrets() // ExportSecrets | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ExportProjectSecrets(context.Background(), projectId).ExportSecrets(exportSecrets).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiExportProjectSecretsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **exportSecrets** | [**ExportSecrets**](ExportSecrets.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	importSecretFiles := *openapiclient.NewImportSecretFiles([]openapiclient.ImportSecretFilesFilesInner{*openapiclient.NewImportSecretFilesFilesInner("ContentBase64_example", "Path_example")}) // ImportSecretFiles | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ImportProjectSecretFiles(context.Background(), projectId).ImportSecretFiles(importSecretFiles).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiImportProjectSecretFilesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importSecretFiles** | [**ImportSecretFiles**](ImportSecretFiles.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretFilesImported**](SecretFilesImported.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretEntries(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListProjectSecretEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretEntries**](SecretEntries.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretsConfigs(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListProjectSecretsConfigsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]SecretsConfigSummary**](SecretsConfigSummary.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.ListProjectSecretsSyncLogs(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListProjectSecretsSyncLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]SecretsSyncLog**](SecretsSyncLog.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.TestProjectSecrets(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiTestProjectSecretsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretsProbe**](SecretsProbe.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	configId := "configId_example" // string | 
	updateSecretsConfig := *openapiclient.NewUpdateSecretsConfig() // UpdateSecretsConfig | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.UpdateProjectSecretsConfig(context.Background(), projectId, configId).UpdateSecretsConfig(updateSecretsConfig).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUpdateProjectSecretsConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateSecretsConfig** | [**UpdateSecretsConfig**](UpdateSecretsConfig.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretsConfig**](SecretsConfig.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	projectId := "projectId_example" // string | 
	upsertSecretEntries := *openapiclient.NewUpsertSecretEntries([]openapiclient.UpsertSecretEntriesEntriesInner{*openapiclient.NewUpsertSecretEntriesEntriesInner("Key_example", "Value_example")}) // UpsertSecretEntries | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SecretsAPI.UpsertProjectSecretEntries(context.Background(), projectId).UpsertSecretEntries(upsertSecretEntries).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUpsertProjectSecretEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertSecretEntries** | [**UpsertSecretEntries**](UpsertSecretEntries.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SecretEntriesWritten**](SecretEntriesWritten.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

