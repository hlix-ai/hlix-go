# ClientPortalsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AcceptClientPortalInvitation**](ClientPortalsAPI.md#acceptclientportalinvitation) | **Post** /v1/api/portal-invitations/{token}/accept | Accept an email-bound client portal invitation
[**CreateClientPortalIdea**](ClientPortalsAPI.md#createclientportalidea) | **Post** /v1/api/portal/projects | Create a planning project
[**EnterWorkspaceClientPortal**](ClientPortalsAPI.md#enterworkspaceclientportal) | **Post** /v1/api/portals/{agencySlug}/session | Enter the agency portal using the signed-in verified email
[**GetClientPortalIdentity**](ClientPortalsAPI.md#getclientportalidentity) | **Get** /v1/api/portals/{agencySlug}/identity | Read the published agency identity
[**GetWorkspacePortalSettings**](ClientPortalsAPI.md#getworkspaceportalsettings) | **Get** /v1/api/client-portal/settings | Read default client permissions
[**InitializePersonalWorkspace**](ClientPortalsAPI.md#initializepersonalworkspace) | **Post** /v1/api/me/workspace | Initialize your personal Hlix workspace
[**InviteWorkspacePortalClient**](ClientPortalsAPI.md#inviteworkspaceportalclient) | **Post** /v1/api/client-portal/invitations | Invite an email directly to the agency client portal
[**ListMyClientPortals**](ClientPortalsAPI.md#listmyclientportals) | **Get** /v1/api/me/portals | Discover your available agency client portals
[**ListWorkspacePortalClients**](ClientPortalsAPI.md#listworkspaceportalclients) | **Get** /v1/api/client-portal/members | List the agency&#39;s portal clients
[**ListWorkspacePortalInvitations**](ClientPortalsAPI.md#listworkspaceportalinvitations) | **Get** /v1/api/client-portal/invitations | List agency client invitations
[**ListWorkspacePortalProjectAccess**](ClientPortalsAPI.md#listworkspaceportalprojectaccess) | **Get** /v1/api/client-portal/members/{userId}/projects | List a client&#39;s current agency portal project access
[**RemoveWorkspacePortalClient**](ClientPortalsAPI.md#removeworkspaceportalclient) | **Delete** /v1/api/client-portal/members/{userId} | Remove a client&#39;s agency portal access
[**RemoveWorkspacePortalCustomerAccess**](ClientPortalsAPI.md#removeworkspaceportalcustomeraccess) | **Delete** /v1/api/client-portal/members/{userId}/accounts/{clientAccountId} | Take one customer away from a client
[**RemoveWorkspacePortalProjectAccess**](ClientPortalsAPI.md#removeworkspaceportalprojectaccess) | **Delete** /v1/api/client-portal/members/{userId}/projects/{projectId} | Remove one explicit portal project grant
[**RestoreWorkspacePortalCustomerAccess**](ClientPortalsAPI.md#restoreworkspaceportalcustomeraccess) | **Put** /v1/api/client-portal/members/{userId}/accounts/{clientAccountId} | Give a client back one customer&#39;s access
[**RevokeWorkspacePortalInvitation**](ClientPortalsAPI.md#revokeworkspaceportalinvitation) | **Delete** /v1/api/client-portal/invitations/{invitationId} | Revoke an unaccepted client invitation
[**SetWorkspacePortalProjectAccess**](ClientPortalsAPI.md#setworkspaceportalprojectaccess) | **Put** /v1/api/client-portal/members/{userId}/projects/{projectId} | Grant one project, with messaging and project insights
[**UpdateWorkspacePortalClient**](ClientPortalsAPI.md#updateworkspaceportalclient) | **Patch** /v1/api/client-portal/members/{userId} | Set or clear a client&#39;s permission override
[**UpdateWorkspacePortalSettings**](ClientPortalsAPI.md#updateworkspaceportalsettings) | **Patch** /v1/api/client-portal/settings | Update default client permissions



## AcceptClientPortalInvitation

> PortalAccepted AcceptClientPortalInvitation(ctx, token).XOrganizationId(xOrganizationId).Execute()

Accept an email-bound client portal invitation

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
	ctx := context.Background()
	token := "token_example" // string |

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.AcceptClientPortalInvitation(ctx, token).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.AcceptClientPortalInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AcceptClientPortalInvitation`: PortalAccepted
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.AcceptClientPortalInvitation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**token** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAcceptClientPortalInvitationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PortalAccepted**](PortalAccepted.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateClientPortalIdea

> ProjectRow CreateClientPortalIdea(ctx).CreatePortalProject(createPortalProject).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Create a planning project

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
	ctx := context.Background()
	var createPortalProject openapiclient.CreatePortalProject
	if err := json.Unmarshal([]byte("{\"name\":\"text\"}"), &createPortalProject); err != nil {
		panic(err)
	}

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.CreateClientPortalIdea(ctx).CreatePortalProject(createPortalProject).XClientPortal(os.Getenv("HLIX_AGENCY_WORKSPACE_ID")).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.CreateClientPortalIdea``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateClientPortalIdea`: ProjectRow
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.CreateClientPortalIdea`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateClientPortalIdeaRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPortalProject** | [**CreatePortalProject**](CreatePortalProject.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectRow**](ProjectRow.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EnterWorkspaceClientPortal

> WorkspacePortal EnterWorkspaceClientPortal(ctx, agencySlug).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Enter the agency portal using the signed-in verified email

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
	ctx := context.Background()
	agencySlug := "agencySlug_example" // string |

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.EnterWorkspaceClientPortal(ctx, agencySlug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.EnterWorkspaceClientPortal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EnterWorkspaceClientPortal`: WorkspacePortal
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.EnterWorkspaceClientPortal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**agencySlug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiEnterWorkspaceClientPortalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**WorkspacePortal**](WorkspacePortal.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientPortalIdentity

> PortalIdentity GetClientPortalIdentity(ctx, agencySlug).Execute()

Read the published agency identity

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
	agencySlug := "agencySlug_example" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.GetClientPortalIdentity(ctx, agencySlug).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.GetClientPortalIdentity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientPortalIdentity`: PortalIdentity
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.GetClientPortalIdentity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**agencySlug** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientPortalIdentityRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PortalIdentity**](PortalIdentity.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspacePortalSettings

> WorkspacePortalSettings GetWorkspacePortalSettings(ctx).XOrganizationId(xOrganizationId).Execute()

Read default client permissions

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
	resp, r, err := apiClient.ClientPortalsAPI.GetWorkspacePortalSettings(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.GetWorkspacePortalSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspacePortalSettings`: WorkspacePortalSettings
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.GetWorkspacePortalSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetWorkspacePortalSettingsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspacePortalSettings**](WorkspacePortalSettings.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitializePersonalWorkspace

> PersonalWorkspace InitializePersonalWorkspace(ctx).XOrganizationId(xOrganizationId).Execute()

Initialize your personal Hlix workspace

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
	ctx := context.Background()

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.InitializePersonalWorkspace(ctx).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.InitializePersonalWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitializePersonalWorkspace`: PersonalWorkspace
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.InitializePersonalWorkspace`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiInitializePersonalWorkspaceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PersonalWorkspace**](PersonalWorkspace.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InviteWorkspacePortalClient

> WorkspacePortalInvitationCreated InviteWorkspacePortalClient(ctx).InviteWorkspacePortal(inviteWorkspacePortal).XOrganizationId(xOrganizationId).Execute()

Invite an email directly to the agency client portal

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
	var inviteWorkspacePortal openapiclient.InviteWorkspacePortal
	if err := json.Unmarshal([]byte("{\"email\":\"person@example.com\"}"), &inviteWorkspacePortal); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.InviteWorkspacePortalClient(ctx).InviteWorkspacePortal(inviteWorkspacePortal).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.InviteWorkspacePortalClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InviteWorkspacePortalClient`: WorkspacePortalInvitationCreated
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.InviteWorkspacePortalClient`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiInviteWorkspacePortalClientRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteWorkspacePortal** | [**InviteWorkspacePortal**](InviteWorkspacePortal.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspacePortalInvitationCreated**](WorkspacePortalInvitationCreated.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMyClientPortals

> []WorkspacePortal ListMyClientPortals(ctx).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Discover your available agency client portals

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
	ctx := context.Background()

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListMyClientPortals(ctx).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.ListMyClientPortals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMyClientPortals`: []WorkspacePortal
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.ListMyClientPortals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListMyClientPortalsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]WorkspacePortal**](WorkspacePortal.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspacePortalClients

> []WorkspacePortalClient ListWorkspacePortalClients(ctx).XOrganizationId(xOrganizationId).Execute()

List the agency's portal clients

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
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalClients(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.ListWorkspacePortalClients``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspacePortalClients`: []WorkspacePortalClient
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.ListWorkspacePortalClients`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListWorkspacePortalClientsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]WorkspacePortalClient**](WorkspacePortalClient.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspacePortalInvitations

> []WorkspacePortalInvitation ListWorkspacePortalInvitations(ctx).XOrganizationId(xOrganizationId).Execute()

List agency client invitations

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
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalInvitations(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.ListWorkspacePortalInvitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspacePortalInvitations`: []WorkspacePortalInvitation
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.ListWorkspacePortalInvitations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListWorkspacePortalInvitationsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]WorkspacePortalInvitation**](WorkspacePortalInvitation.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspacePortalProjectAccess

> []PortalProjectGrant ListWorkspacePortalProjectAccess(ctx, userId).XOrganizationId(xOrganizationId).Execute()

List a client's current agency portal project access

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
	userId := "userId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalProjectAccess(ctx, userId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.ListWorkspacePortalProjectAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspacePortalProjectAccess`: []PortalProjectGrant
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.ListWorkspacePortalProjectAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListWorkspacePortalProjectAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]PortalProjectGrant**](PortalProjectGrant.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveWorkspacePortalClient

> MessageAck RemoveWorkspacePortalClient(ctx, userId).XOrganizationId(xOrganizationId).Execute()

Remove a client's agency portal access

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
	userId := "userId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalClient(ctx, userId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.RemoveWorkspacePortalClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveWorkspacePortalClient`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.RemoveWorkspacePortalClient`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRemoveWorkspacePortalClientRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveWorkspacePortalCustomerAccess

> CustomerAccessRemoved RemoveWorkspacePortalCustomerAccess(ctx, userId, clientAccountId).XOrganizationId(xOrganizationId).Execute()

Take one customer away from a client

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
	userId := "userId_example" // string |
	clientAccountId := "clientAccountId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalCustomerAccess(ctx, userId, clientAccountId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.RemoveWorkspacePortalCustomerAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveWorkspacePortalCustomerAccess`: CustomerAccessRemoved
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.RemoveWorkspacePortalCustomerAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |
**clientAccountId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRemoveWorkspacePortalCustomerAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomerAccessRemoved**](CustomerAccessRemoved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveWorkspacePortalProjectAccess

> MessageAck RemoveWorkspacePortalProjectAccess(ctx, userId, projectId).XOrganizationId(xOrganizationId).Execute()

Remove one explicit portal project grant

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
	userId := "userId_example" // string |
	projectId := "projectId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalProjectAccess(ctx, userId, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.RemoveWorkspacePortalProjectAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveWorkspacePortalProjectAccess`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.RemoveWorkspacePortalProjectAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRemoveWorkspacePortalProjectAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreWorkspacePortalCustomerAccess

> CustomerAccessRestored RestoreWorkspacePortalCustomerAccess(ctx, userId, clientAccountId).RestoreCustomerAccess(restoreCustomerAccess).XOrganizationId(xOrganizationId).Execute()

Give a client back one customer's access

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
	userId := "userId_example" // string |
	clientAccountId := "clientAccountId_example" // string |
	var restoreCustomerAccess openapiclient.RestoreCustomerAccess
	if err := json.Unmarshal([]byte("{\"seat\":true}"), &restoreCustomerAccess); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RestoreWorkspacePortalCustomerAccess(ctx, userId, clientAccountId).RestoreCustomerAccess(restoreCustomerAccess).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.RestoreWorkspacePortalCustomerAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreWorkspacePortalCustomerAccess`: CustomerAccessRestored
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.RestoreWorkspacePortalCustomerAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |
**clientAccountId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRestoreWorkspacePortalCustomerAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **restoreCustomerAccess** | [**RestoreCustomerAccess**](RestoreCustomerAccess.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CustomerAccessRestored**](CustomerAccessRestored.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeWorkspacePortalInvitation

> MessageAck RevokeWorkspacePortalInvitation(ctx, invitationId).XOrganizationId(xOrganizationId).Execute()

Revoke an unaccepted client invitation

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
	invitationId := "invitationId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RevokeWorkspacePortalInvitation(ctx, invitationId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.RevokeWorkspacePortalInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeWorkspacePortalInvitation`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.RevokeWorkspacePortalInvitation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**invitationId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRevokeWorkspacePortalInvitationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetWorkspacePortalProjectAccess

> PortalProjectGrant SetWorkspacePortalProjectAccess(ctx, userId, projectId).PortalProjectPermissions(portalProjectPermissions).XOrganizationId(xOrganizationId).Execute()

Grant one project, with messaging and project insights

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
	userId := "userId_example" // string |
	projectId := "projectId_example" // string |
	var portalProjectPermissions openapiclient.PortalProjectPermissions
	if err := json.Unmarshal([]byte("{\"canMessage\":true}"), &portalProjectPermissions); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.SetWorkspacePortalProjectAccess(ctx, userId, projectId).PortalProjectPermissions(portalProjectPermissions).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.SetWorkspacePortalProjectAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetWorkspacePortalProjectAccess`: PortalProjectGrant
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.SetWorkspacePortalProjectAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSetWorkspacePortalProjectAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **portalProjectPermissions** | [**PortalProjectPermissions**](PortalProjectPermissions.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PortalProjectGrant**](PortalProjectGrant.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWorkspacePortalClient

> WorkspacePortalClientPermissions UpdateWorkspacePortalClient(ctx, userId).WorkspacePortalMember(workspacePortalMember).XOrganizationId(xOrganizationId).Execute()

Set or clear a client's permission override

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
	userId := "userId_example" // string |
	var workspacePortalMember openapiclient.WorkspacePortalMember
	if err := json.Unmarshal([]byte("{\"canCreateProjects\":true}"), &workspacePortalMember); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.UpdateWorkspacePortalClient(ctx, userId).WorkspacePortalMember(workspacePortalMember).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.UpdateWorkspacePortalClient``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWorkspacePortalClient`: WorkspacePortalClientPermissions
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.UpdateWorkspacePortalClient`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateWorkspacePortalClientRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspacePortalMember** | [**WorkspacePortalMember**](WorkspacePortalMember.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspacePortalClientPermissions**](WorkspacePortalClientPermissions.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWorkspacePortalSettings

> WorkspacePortalSettings UpdateWorkspacePortalSettings(ctx).WorkspacePortalSettings(workspacePortalSettings).XOrganizationId(xOrganizationId).Execute()

Update default client permissions

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
	var workspacePortalSettings openapiclient.WorkspacePortalSettings
	if err := json.Unmarshal([]byte("{\"defaultCanCreateProjects\":true}"), &workspacePortalSettings); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.UpdateWorkspacePortalSettings(ctx).WorkspacePortalSettings(workspacePortalSettings).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientPortalsAPI.UpdateWorkspacePortalSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWorkspacePortalSettings`: WorkspacePortalSettings
	fmt.Fprintf(os.Stdout, "Response from `ClientPortalsAPI.UpdateWorkspacePortalSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiUpdateWorkspacePortalSettingsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspacePortalSettings** | [**WorkspacePortalSettings**](WorkspacePortalSettings.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspacePortalSettings**](WorkspacePortalSettings.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

