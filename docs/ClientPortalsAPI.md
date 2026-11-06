# \ClientPortalsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AcceptClientPortalInvitation**](ClientPortalsAPI.md#AcceptClientPortalInvitation) | **Post** /v1/api/portal-invitations/{token}/accept | Accept an email-bound client portal invitation
[**CreateClientPortalIdea**](ClientPortalsAPI.md#CreateClientPortalIdea) | **Post** /v1/api/portal/projects | Create a brainstorming project
[**EnterWorkspaceClientPortal**](ClientPortalsAPI.md#EnterWorkspaceClientPortal) | **Post** /v1/api/portals/{agencySlug}/session | Enter the agency portal using the signed-in verified email
[**GetClientPortalIdentity**](ClientPortalsAPI.md#GetClientPortalIdentity) | **Get** /v1/api/portals/{agencySlug}/identity | Read the published agency identity
[**GetWorkspacePortalSettings**](ClientPortalsAPI.md#GetWorkspacePortalSettings) | **Get** /v1/api/client-portal/settings | Read default client permissions
[**InitializePersonalWorkspace**](ClientPortalsAPI.md#InitializePersonalWorkspace) | **Post** /v1/api/me/workspace | Initialize your personal Hlix workspace
[**InviteWorkspacePortalClient**](ClientPortalsAPI.md#InviteWorkspacePortalClient) | **Post** /v1/api/client-portal/invitations | Invite an email directly to the agency client portal
[**ListMyClientPortals**](ClientPortalsAPI.md#ListMyClientPortals) | **Get** /v1/api/me/portals | Discover your available agency client portals
[**ListWorkspacePortalClients**](ClientPortalsAPI.md#ListWorkspacePortalClients) | **Get** /v1/api/client-portal/members | List the agency&#39;s portal clients
[**ListWorkspacePortalInvitations**](ClientPortalsAPI.md#ListWorkspacePortalInvitations) | **Get** /v1/api/client-portal/invitations | List agency client invitations
[**ListWorkspacePortalProjectAccess**](ClientPortalsAPI.md#ListWorkspacePortalProjectAccess) | **Get** /v1/api/client-portal/members/{userId}/projects | List a client&#39;s current agency portal project access
[**RemoveWorkspacePortalClient**](ClientPortalsAPI.md#RemoveWorkspacePortalClient) | **Delete** /v1/api/client-portal/members/{userId} | Remove a client&#39;s agency portal access
[**RemoveWorkspacePortalCustomerAccess**](ClientPortalsAPI.md#RemoveWorkspacePortalCustomerAccess) | **Delete** /v1/api/client-portal/members/{userId}/accounts/{clientAccountId} | Take one customer away from a client
[**RemoveWorkspacePortalProjectAccess**](ClientPortalsAPI.md#RemoveWorkspacePortalProjectAccess) | **Delete** /v1/api/client-portal/members/{userId}/projects/{projectId} | Remove one explicit portal project grant
[**RestoreWorkspacePortalCustomerAccess**](ClientPortalsAPI.md#RestoreWorkspacePortalCustomerAccess) | **Put** /v1/api/client-portal/members/{userId}/accounts/{clientAccountId} | Give a client back one customer&#39;s access
[**RevokeWorkspacePortalInvitation**](ClientPortalsAPI.md#RevokeWorkspacePortalInvitation) | **Delete** /v1/api/client-portal/invitations/{invitationId} | Revoke an unaccepted client invitation
[**SetWorkspacePortalProjectAccess**](ClientPortalsAPI.md#SetWorkspacePortalProjectAccess) | **Put** /v1/api/client-portal/members/{userId}/projects/{projectId} | Grant one project, with steering and project insights
[**UpdateWorkspacePortalClient**](ClientPortalsAPI.md#UpdateWorkspacePortalClient) | **Patch** /v1/api/client-portal/members/{userId} | Set or clear a client&#39;s permission override
[**UpdateWorkspacePortalSettings**](ClientPortalsAPI.md#UpdateWorkspacePortalSettings) | **Patch** /v1/api/client-portal/settings | Update default client permissions



## AcceptClientPortalInvitation

> PortalAccepted AcceptClientPortalInvitation(ctx, token).XOrganizationId(xOrganizationId).Execute()

Accept an email-bound client portal invitation

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
	token := "token_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.AcceptClientPortalInvitation(context.Background(), token).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiAcceptClientPortalInvitationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PortalAccepted**](PortalAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateClientPortalIdea

> ProjectRow CreateClientPortalIdea(ctx).CreatePortalProject(createPortalProject).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Create a brainstorming project

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
	createPortalProject := *openapiclient.NewCreatePortalProject("Name_example") // CreatePortalProject | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.CreateClientPortalIdea(context.Background()).CreatePortalProject(createPortalProject).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiCreateClientPortalIdeaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPortalProject** | [**CreatePortalProject**](CreatePortalProject.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectRow**](ProjectRow.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	agencySlug := "agencySlug_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.EnterWorkspaceClientPortal(context.Background(), agencySlug).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiEnterWorkspaceClientPortalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**WorkspacePortal**](WorkspacePortal.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	agencySlug := "agencySlug_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.GetClientPortalIdentity(context.Background(), agencySlug).Execute()
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

Other parameters are passed through a pointer to a apiGetClientPortalIdentityRequest struct via the builder pattern


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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.GetWorkspacePortalSettings(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetWorkspacePortalSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspacePortalSettings**](WorkspacePortalSettings.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.InitializePersonalWorkspace(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiInitializePersonalWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PersonalWorkspace**](PersonalWorkspace.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	inviteWorkspacePortal := *openapiclient.NewInviteWorkspacePortal("Email_example") // InviteWorkspacePortal | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.InviteWorkspacePortalClient(context.Background()).InviteWorkspacePortal(inviteWorkspacePortal).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiInviteWorkspacePortalClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteWorkspacePortal** | [**InviteWorkspacePortal**](InviteWorkspacePortal.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspacePortalInvitationCreated**](WorkspacePortalInvitationCreated.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListMyClientPortals(context.Background()).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiListMyClientPortalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]WorkspacePortal**](WorkspacePortal.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalClients(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListWorkspacePortalClientsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]WorkspacePortalClient**](WorkspacePortalClient.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalInvitations(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListWorkspacePortalInvitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]WorkspacePortalInvitation**](WorkspacePortalInvitation.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.ListWorkspacePortalProjectAccess(context.Background(), userId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListWorkspacePortalProjectAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]PortalProjectGrant**](PortalProjectGrant.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalClient(context.Background(), userId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRemoveWorkspacePortalClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	clientAccountId := "clientAccountId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalCustomerAccess(context.Background(), userId, clientAccountId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRemoveWorkspacePortalCustomerAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CustomerAccessRemoved**](CustomerAccessRemoved.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RemoveWorkspacePortalProjectAccess(context.Background(), userId, projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRemoveWorkspacePortalProjectAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	clientAccountId := "clientAccountId_example" // string | 
	restoreCustomerAccess := *openapiclient.NewRestoreCustomerAccess(false) // RestoreCustomerAccess | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RestoreWorkspacePortalCustomerAccess(context.Background(), userId, clientAccountId).RestoreCustomerAccess(restoreCustomerAccess).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRestoreWorkspacePortalCustomerAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **restoreCustomerAccess** | [**RestoreCustomerAccess**](RestoreCustomerAccess.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CustomerAccessRestored**](CustomerAccessRestored.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	invitationId := "invitationId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.RevokeWorkspacePortalInvitation(context.Background(), invitationId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRevokeWorkspacePortalInvitationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetWorkspacePortalProjectAccess

> PortalProjectGrant SetWorkspacePortalProjectAccess(ctx, userId, projectId).PortalProjectPermissions(portalProjectPermissions).XOrganizationId(xOrganizationId).Execute()

Grant one project, with steering and project insights

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
	userId := "userId_example" // string | 
	projectId := "projectId_example" // string | 
	portalProjectPermissions := *openapiclient.NewPortalProjectPermissions(false) // PortalProjectPermissions | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.SetWorkspacePortalProjectAccess(context.Background(), userId, projectId).PortalProjectPermissions(portalProjectPermissions).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiSetWorkspacePortalProjectAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **portalProjectPermissions** | [**PortalProjectPermissions**](PortalProjectPermissions.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PortalProjectGrant**](PortalProjectGrant.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	userId := "userId_example" // string | 
	workspacePortalMember := *openapiclient.NewWorkspacePortalMember(false) // WorkspacePortalMember | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.UpdateWorkspacePortalClient(context.Background(), userId).WorkspacePortalMember(workspacePortalMember).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUpdateWorkspacePortalClientRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspacePortalMember** | [**WorkspacePortalMember**](WorkspacePortalMember.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspacePortalClientPermissions**](WorkspacePortalClientPermissions.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	workspacePortalSettings := *openapiclient.NewWorkspacePortalSettings(false) // WorkspacePortalSettings | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientPortalsAPI.UpdateWorkspacePortalSettings(context.Background()).WorkspacePortalSettings(workspacePortalSettings).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUpdateWorkspacePortalSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspacePortalSettings** | [**WorkspacePortalSettings**](WorkspacePortalSettings.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspacePortalSettings**](WorkspacePortalSettings.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

