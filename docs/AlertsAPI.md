# AlertsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteSlackAlertRoute**](AlertsAPI.md#deleteslackalertroute) | **Delete** /v1/api/alerts/slack | Stop posting alerts to Slack
[**GetAlertSettings**](AlertsAPI.md#getalertsettings) | **Get** /v1/api/alerts | Get where workspace alerts are posted
[**ListSlackAlertChannels**](AlertsAPI.md#listslackalertchannels) | **Get** /v1/api/alerts/slack/channels | List Slack channels the bot can post alerts to
[**SaveSlackAlertRoute**](AlertsAPI.md#saveslackalertroute) | **Put** /v1/api/alerts/slack | Choose the Slack channel and alert kinds
[**SaveTelegramAlertRoute**](AlertsAPI.md#savetelegramalertroute) | **Put** /v1/api/alerts/telegram | Choose which alerts the linked Telegram chats receive
[**TestSlackAlertRoute**](AlertsAPI.md#testslackalertroute) | **Post** /v1/api/alerts/slack/test | Send a test alert to the Slack channel
[**TestTelegramAlertRoute**](AlertsAPI.md#testtelegramalertroute) | **Post** /v1/api/alerts/telegram/test | Send a test alert to the linked Telegram chats



## DeleteSlackAlertRoute

> AlertRouteRemoved DeleteSlackAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()

Stop posting alerts to Slack

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
	resp, r, err := apiClient.AlertsAPI.DeleteSlackAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.DeleteSlackAlertRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteSlackAlertRoute`: AlertRouteRemoved
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.DeleteSlackAlertRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiDeleteSlackAlertRouteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertRouteRemoved**](AlertRouteRemoved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAlertSettings

> AlertSettings GetAlertSettings(ctx).XOrganizationId(xOrganizationId).Execute()

Get where workspace alerts are posted

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
	resp, r, err := apiClient.AlertsAPI.GetAlertSettings(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.GetAlertSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlertSettings`: AlertSettings
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.GetAlertSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetAlertSettingsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertSettings**](AlertSettings.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListSlackAlertChannels

> SlackChannelPage ListSlackAlertChannels(ctx).TeamId(teamId).Query(query).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()

List Slack channels the bot can post alerts to

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
	teamId := "teamId_example" // string | The connected Slack workspace (`team_id`).
	query := "query_example" // string | Only channels whose name contains this (a leading `#` is ignored). (optional)
	cursor := "cursor_example" // string | `nextCursor` from the previous page. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.ListSlackAlertChannels(ctx).TeamId(teamId).Query(query).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.ListSlackAlertChannels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListSlackAlertChannels`: SlackChannelPage
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.ListSlackAlertChannels`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListSlackAlertChannelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **teamId** | **string** | The connected Slack workspace (&#x60;team_id&#x60;). |
 **query** | **string** | Only channels whose name contains this (a leading &#x60;#&#x60; is ignored). |
 **cursor** | **string** | &#x60;nextCursor&#x60; from the previous page. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SlackChannelPage**](SlackChannelPage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveSlackAlertRoute

> AlertRoute SaveSlackAlertRoute(ctx).SaveSlackAlertRoute(saveSlackAlertRoute).XOrganizationId(xOrganizationId).Execute()

Choose the Slack channel and alert kinds

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
	var saveSlackAlertRoute openapiclient.SaveSlackAlertRoute
	if err := json.Unmarshal([]byte("{\"channelId\":\"EUR\",\"enabled\":true,\"kinds\":[\"reply.interested\"],\"teamId\":\"EUR\"}"), &saveSlackAlertRoute); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.SaveSlackAlertRoute(ctx).SaveSlackAlertRoute(saveSlackAlertRoute).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.SaveSlackAlertRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveSlackAlertRoute`: AlertRoute
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.SaveSlackAlertRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSaveSlackAlertRouteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveSlackAlertRoute** | [**SaveSlackAlertRoute**](SaveSlackAlertRoute.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertRoute**](AlertRoute.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveTelegramAlertRoute

> AlertRoute SaveTelegramAlertRoute(ctx).SaveTelegramAlertRoute(saveTelegramAlertRoute).XOrganizationId(xOrganizationId).Execute()

Choose which alerts the linked Telegram chats receive

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
	var saveTelegramAlertRoute openapiclient.SaveTelegramAlertRoute
	if err := json.Unmarshal([]byte("{\"enabled\":true,\"kinds\":[\"reply.interested\"]}"), &saveTelegramAlertRoute); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.SaveTelegramAlertRoute(ctx).SaveTelegramAlertRoute(saveTelegramAlertRoute).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.SaveTelegramAlertRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveTelegramAlertRoute`: AlertRoute
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.SaveTelegramAlertRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSaveTelegramAlertRouteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveTelegramAlertRoute** | [**SaveTelegramAlertRoute**](SaveTelegramAlertRoute.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertRoute**](AlertRoute.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestSlackAlertRoute

> AlertTestResult TestSlackAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()

Send a test alert to the Slack channel

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
	resp, r, err := apiClient.AlertsAPI.TestSlackAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.TestSlackAlertRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestSlackAlertRoute`: AlertTestResult
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.TestSlackAlertRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiTestSlackAlertRouteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertTestResult**](AlertTestResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestTelegramAlertRoute

> AlertTestResult TestTelegramAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()

Send a test alert to the linked Telegram chats

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
	resp, r, err := apiClient.AlertsAPI.TestTelegramAlertRoute(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.TestTelegramAlertRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestTelegramAlertRoute`: AlertTestResult
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.TestTelegramAlertRoute`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiTestTelegramAlertRouteRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AlertTestResult**](AlertTestResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

