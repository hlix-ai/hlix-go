# ProvidersAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ConnectModelProvider**](ProvidersAPI.md#connectmodelprovider) | **Post** /v1/api/providers | Save a workspace model provider
[**DeleteModelProvider**](ProvidersAPI.md#deletemodelprovider) | **Delete** /v1/api/providers/{provider} | Disconnect a model provider
[**GetModelProvider**](ProvidersAPI.md#getmodelprovider) | **Get** /v1/api/providers/{provider} | Read a model provider configuration
[**GetModelProviderModels**](ProvidersAPI.md#getmodelprovidermodels) | **Get** /v1/api/providers/{provider}/models | Read cached models advertised by this billing provider
[**ListModelProviders**](ProvidersAPI.md#listmodelproviders) | **Get** /v1/api/providers | List connected model billing providers
[**RefreshModelProviderModels**](ProvidersAPI.md#refreshmodelprovidermodels) | **Post** /v1/api/providers/{provider}/models/refresh | Refresh the connected provider model catalog
[**TestModelProvider**](ProvidersAPI.md#testmodelprovider) | **Post** /v1/api/providers/{provider}/test | Test provider credentials without inference
[**UpdateModelProvider**](ProvidersAPI.md#updatemodelprovider) | **Patch** /v1/api/providers/{provider} | Update a model provider



## ConnectModelProvider

> ModelProviderConfig ConnectModelProvider(ctx).UpsertProvider(upsertProvider).XOrganizationId(xOrganizationId).Execute()

Save a workspace model provider

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
	var upsertProvider openapiclient.UpsertProvider
	if err := json.Unmarshal([]byte("{\"provider\":\"openai\"}"), &upsertProvider); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.ConnectModelProvider(ctx).UpsertProvider(upsertProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.ConnectModelProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectModelProvider`: ModelProviderConfig
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.ConnectModelProvider`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiConnectModelProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **upsertProvider** | [**UpsertProvider**](UpsertProvider.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ModelProviderConfig**](ModelProviderConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteModelProvider

> ModelProviderRemoved DeleteModelProvider(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Disconnect a model provider

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
	provider := "provider_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.DeleteModelProvider(ctx, provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.DeleteModelProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteModelProvider`: ModelProviderRemoved
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.DeleteModelProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteModelProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ModelProviderRemoved**](ModelProviderRemoved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetModelProvider

> ModelProviderConfig GetModelProvider(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Read a model provider configuration

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
	provider := "provider_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.GetModelProvider(ctx, provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.GetModelProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetModelProvider`: ModelProviderConfig
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.GetModelProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetModelProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ModelProviderConfig**](ModelProviderConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetModelProviderModels

> CoderAccountModelCatalog GetModelProviderModels(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Read cached models advertised by this billing provider

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
	provider := "provider_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.GetModelProviderModels(ctx, provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.GetModelProviderModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetModelProviderModels`: CoderAccountModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.GetModelProviderModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetModelProviderModelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListModelProviders

> []ModelProviderConfig ListModelProviders(ctx).XOrganizationId(xOrganizationId).Execute()

List connected model billing providers

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
	resp, r, err := apiClient.ProvidersAPI.ListModelProviders(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.ListModelProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListModelProviders`: []ModelProviderConfig
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.ListModelProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListModelProvidersRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ModelProviderConfig**](ModelProviderConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefreshModelProviderModels

> CoderAccountModelCatalog RefreshModelProviderModels(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Refresh the connected provider model catalog

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
	provider := "provider_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.RefreshModelProviderModels(ctx, provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.RefreshModelProviderModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshModelProviderModels`: CoderAccountModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.RefreshModelProviderModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRefreshModelProviderModelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestModelProvider

> ModelProviderProbe TestModelProvider(ctx, provider).TestModelProvider(testModelProvider).XOrganizationId(xOrganizationId).Execute()

Test provider credentials without inference

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
	provider := "provider_example" // string |
	var testModelProvider openapiclient.TestModelProvider
	if err := json.Unmarshal([]byte("{}"), &testModelProvider); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.TestModelProvider(ctx, provider).TestModelProvider(testModelProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.TestModelProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestModelProvider`: ModelProviderProbe
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.TestModelProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiTestModelProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **testModelProvider** | [**TestModelProvider**](TestModelProvider.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ModelProviderProbe**](ModelProviderProbe.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateModelProvider

> ModelProviderConfig UpdateModelProvider(ctx, provider).PatchProvider(patchProvider).XOrganizationId(xOrganizationId).Execute()

Update a model provider

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
	provider := "provider_example" // string |
	var patchProvider openapiclient.PatchProvider
	if err := json.Unmarshal([]byte("{}"), &patchProvider); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProvidersAPI.UpdateModelProvider(ctx, provider).PatchProvider(patchProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProvidersAPI.UpdateModelProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateModelProvider`: ModelProviderConfig
	fmt.Fprintf(os.Stdout, "Response from `ProvidersAPI.UpdateModelProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateModelProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchProvider** | [**PatchProvider**](PatchProvider.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ModelProviderConfig**](ModelProviderConfig.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

