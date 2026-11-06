# \ProjectsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddProjectInitialProposalComment**](ProjectsAPI.md#AddProjectInitialProposalComment) | **Post** /v1/api/projects/{id}/initial-proposal/comments | Comment on a proposal section
[**ApplyCanvasAgentOps**](ProjectsAPI.md#ApplyCanvasAgentOps) | **Post** /v1/api/projects/{id}/canvas/agent/ops | Draw on the project canvas as hlix, for the caller
[**ApproveProjectInitialProposal**](ProjectsAPI.md#ApproveProjectInitialProposal) | **Post** /v1/api/projects/{id}/initial-proposal/approve | Approve the initial plan and release delivery
[**ArchiveProject**](ProjectsAPI.md#ArchiveProject) | **Post** /v1/api/projects/{id}/archive | Archive a project
[**AssignProject**](ProjectsAPI.md#AssignProject) | **Patch** /v1/api/projects/{id}/assign | Hand a project to a teammate
[**AttachProjectGithubRepository**](ProjectsAPI.md#AttachProjectGithubRepository) | **Post** /v1/api/projects/{id}/repos/github | Attach an existing GitHub repository by owner/name
[**AttachProjectRepo**](ProjectsAPI.md#AttachProjectRepo) | **Post** /v1/api/projects/{id}/repos | Attach a repository to a project
[**BuildDesign**](ProjectsAPI.md#BuildDesign) | **Post** /v1/api/projects/{projectId}/designs/{designId}/build | Submit implementation of an accepted prototype
[**BuildProjectMobileApp**](ProjectsAPI.md#BuildProjectMobileApp) | **Post** /v1/api/projects/{id}/mobile/builds | Build a native app preview
[**ControlTaskComputer**](ProjectsAPI.md#ControlTaskComputer) | **Post** /v1/api/projects/{id}/computers/{computerId}/control | Take, renew or release managed computer input
[**CreateDesign**](ProjectsAPI.md#CreateDesign) | **Post** /v1/api/projects/{projectId}/designs | Submit a native prototype brief
[**CreateDesignComment**](ProjectsAPI.md#CreateDesignComment) | **Post** /v1/api/projects/{projectId}/designs/{designId}/comments | Comment on a frame without dispatching work
[**CreateProject**](ProjectsAPI.md#CreateProject) | **Post** /v1/api/projects | Create a project
[**DecideDesign**](ProjectsAPI.md#DecideDesign) | **Post** /v1/api/projects/{projectId}/designs/{designId}/decisions | Accept a revision or submit revision work
[**DecideProjectInitialProposal**](ProjectsAPI.md#DecideProjectInitialProposal) | **Post** /v1/api/projects/{id}/initial-proposal/decision | Record the invited client reviewer&#39;s optional decision
[**DeleteProject**](ProjectsAPI.md#DeleteProject) | **Delete** /v1/api/projects/{id} | Delete a project
[**DetachProjectRepo**](ProjectsAPI.md#DetachProjectRepo) | **Delete** /v1/api/projects/{id}/repos/{repoId} | Detach a repository from a project
[**DetectProjectCommands**](ProjectsAPI.md#DetectProjectCommands) | **Post** /v1/api/projects/{id}/detect-commands | Re-run command detection without writing anything
[**DownloadTaskComputerEvidence**](ProjectsAPI.md#DownloadTaskComputerEvidence) | **Get** /v1/api/projects/{id}/computers/{computerId}/evidence/{kind} | Download retained execution screen or replay evidence
[**EditProjectInitialProposal**](ProjectsAPI.md#EditProjectInitialProposal) | **Put** /v1/api/projects/{id}/initial-proposal/revisions/manual | Create a manual business-copy revision
[**GetCanvasAgentView**](ProjectsAPI.md#GetCanvasAgentView) | **Get** /v1/api/projects/{id}/canvas/agent | Read the project canvas as an agent may see it
[**GetDesign**](ProjectsAPI.md#GetDesign) | **Get** /v1/api/projects/{projectId}/designs/{designId} | Read a design revision and its review threads
[**GetProject**](ProjectsAPI.md#GetProject) | **Get** /v1/api/projects/{id} | Get one project
[**GetProjectArchitecture**](ProjectsAPI.md#GetProjectArchitecture) | **Get** /v1/api/projects/{id}/architecture | Read the application&#39;s source dependency graph
[**GetProjectArtifactUrl**](ProjectsAPI.md#GetProjectArtifactUrl) | **Get** /v1/api/projects/{id}/artifacts/{filename} | Get a signed download URL for one project artifact
[**GetProjectBoard**](ProjectsAPI.md#GetProjectBoard) | **Get** /v1/api/projects/{id}/board | Read the rows a project&#39;s board shows
[**GetProjectBudget**](ProjectsAPI.md#GetProjectBudget) | **Get** /v1/api/projects/{id}/budget | Get the project&#39;s delivery budget and spend to date
[**GetProjectCanvas**](ProjectsAPI.md#GetProjectCanvas) | **Get** /v1/api/projects/{id}/canvas | Read the project canvas without waking its Cloud Machine
[**GetProjectCycleMetrics**](ProjectsAPI.md#GetProjectCycleMetrics) | **Get** /v1/api/projects/{id}/cycle-metrics | Get a project&#39;s flow metrics computed from cycle stage history
[**GetProjectDesktop**](ProjectsAPI.md#GetProjectDesktop) | **Get** /v1/api/projects/{id}/desktop | Report whether a graphical desktop is reachable
[**GetProjectDirectorClip**](ProjectsAPI.md#GetProjectDirectorClip) | **Get** /v1/api/projects/{id}/director/clips/{clipId} | Read an audience-scoped Director video segment
[**GetProjectEnvironment**](ProjectsAPI.md#GetProjectEnvironment) | **Get** /v1/api/projects/{id}/environment | Read where the project&#39;s boxes start from
[**GetProjectInitialProposal**](ProjectsAPI.md#GetProjectInitialProposal) | **Get** /v1/api/projects/{id}/initial-proposal | Read the current initial SDD/SOW
[**GetProjectInitialProposalLogo**](ProjectsAPI.md#GetProjectInitialProposalLogo) | **Get** /v1/api/projects/{id}/initial-proposal/logo | Read the frozen agency logo
[**GetProjectMobileAgentSession**](ProjectsAPI.md#GetProjectMobileAgentSession) | **Get** /v1/api/projects/{id}/mobile/agent-sessions/{sessionId} | Read this agent run&#39;s native test device
[**GetProjectMobileBuilds**](ProjectsAPI.md#GetProjectMobileBuilds) | **Get** /v1/api/projects/{id}/mobile/builds | List saved native builds
[**GetProjectMobileSession**](ProjectsAPI.md#GetProjectMobileSession) | **Get** /v1/api/projects/{id}/mobile/sessions/{sessionId} | Read your private app preview
[**GetProjectMobileTargets**](ProjectsAPI.md#GetProjectMobileTargets) | **Get** /v1/api/projects/{id}/mobile/targets | List native app targets
[**GetProjectReview**](ProjectsAPI.md#GetProjectReview) | **Get** /v1/api/projects/{id}/review | Read recorded verification evidence for completed project cycles
[**GetProjectRoadmap**](ProjectsAPI.md#GetProjectRoadmap) | **Get** /v1/api/projects/{id}/roadmap | Get the project&#39;s roadmap
[**GetProjectRunDiagnostics**](ProjectsAPI.md#GetProjectRunDiagnostics) | **Get** /v1/api/projects/{id}/diagnostics | Read why the project&#39;s run failed or is parked
[**GetProjectSequence**](ProjectsAPI.md#GetProjectSequence) | **Get** /v1/api/projects/{id}/sequence | Watch a cycle&#39;s narrated Sequence
[**GetProjectStatus**](ProjectsAPI.md#GetProjectStatus) | **Get** /v1/api/projects/{id}/status | Read where a project stands, in a person&#39;s terms
[**GetProjectTeamInsights**](ProjectsAPI.md#GetProjectTeamInsights) | **Get** /v1/api/projects/{id}/insights | Get a project&#39;s all-time cloud machine totals and its expected finish
[**GetProjectTerminalAccess**](ProjectsAPI.md#GetProjectTerminalAccess) | **Get** /v1/api/projects/{id}/terminal | Open a shell into the project&#39;s Cloud Machine
[**GetProjectThreadDirectory**](ProjectsAPI.md#GetProjectThreadDirectory) | **Get** /v1/api/projects/{id}/threads | Get the project&#39;s conversation tree
[**GetProjectUsage**](ProjectsAPI.md#GetProjectUsage) | **Get** /v1/api/projects/{id}/usage | Get the project&#39;s cost and token roll-up
[**GetTaskComputer**](ProjectsAPI.md#GetTaskComputer) | **Get** /v1/api/projects/{id}/computers/{computerId} | Read the exact execution computer&#39;s availability
[**KeepProjectEnvironmentAlive**](ProjectsAPI.md#KeepProjectEnvironmentAlive) | **Post** /v1/api/projects/{id}/environment/keepalive | Tell a running environment it is still in use
[**ListDesigns**](ProjectsAPI.md#ListDesigns) | **Get** /v1/api/projects/{projectId}/designs | List native project designs
[**ListProjectArtifacts**](ProjectsAPI.md#ListProjectArtifacts) | **Get** /v1/api/projects/{id}/artifacts | List a project&#39;s stored artifacts
[**ListProjectImageBuilds**](ProjectsAPI.md#ListProjectImageBuilds) | **Get** /v1/api/projects/{id}/image-builds | List the project&#39;s Cloud Machine image builds
[**ListProjectInitialProposalComments**](ProjectsAPI.md#ListProjectInitialProposalComments) | **Get** /v1/api/projects/{id}/initial-proposal/comments | List section-anchored proposal comments
[**ListProjectInitialProposalRevisions**](ProjectsAPI.md#ListProjectInitialProposalRevisions) | **Get** /v1/api/projects/{id}/initial-proposal/revisions | List proposal revision history
[**ListProjectLinearSessions**](ProjectsAPI.md#ListProjectLinearSessions) | **Get** /v1/api/projects/{id}/linear-sessions | List the Linear conversations delegated into this project
[**ListProjectMessages**](ProjectsAPI.md#ListProjectMessages) | **Get** /v1/api/projects/{id}/messages | Read the project&#39;s conversation
[**ListProjectRepos**](ProjectsAPI.md#ListProjectRepos) | **Get** /v1/api/projects/{id}/repos | List a project&#39;s repositories
[**ListProjects**](ProjectsAPI.md#ListProjects) | **Get** /v1/api/projects | List the workspace&#39;s projects
[**ListTaskComputers**](ProjectsAPI.md#ListTaskComputers) | **Get** /v1/api/projects/{id}/computers | List the project&#39;s task execution computers
[**MergeProjectReview**](ProjectsAPI.md#MergeProjectReview) | **Post** /v1/api/projects/{id}/review/merge | Merge a reviewed preview pull request at its exact head commit
[**ProjectWorkspaceExec**](ProjectsAPI.md#ProjectWorkspaceExec) | **Post** /v1/api/projects/{id}/workspace/exec | Run a command in the project&#39;s Cloud Machine
[**ProjectWorkspaceFs**](ProjectsAPI.md#ProjectWorkspaceFs) | **Post** /v1/api/projects/{id}/workspace/fs | Read or write a file in the project&#39;s Cloud Machine
[**PublishDesignRevision**](ProjectsAPI.md#PublishDesignRevision) | **Post** /v1/api/projects/{projectId}/designs/{designId}/revisions | Publish a tested playable prototype
[**PublishProjectInitialProposal**](ProjectsAPI.md#PublishProjectInitialProposal) | **Post** /v1/api/projects/{id}/initial-proposal/publish | Publish a branded proposal revision
[**RequestProjectDelivery**](ProjectsAPI.md#RequestProjectDelivery) | **Post** /v1/api/projects/{id}/delivery | Open the project&#39;s pull request now
[**ResolveDesignComment**](ProjectsAPI.md#ResolveDesignComment) | **Patch** /v1/api/projects/{projectId}/designs/{designId}/comments/{commentId} | Resolve or reopen a design comment
[**ResolveProjectInitialProposal**](ProjectsAPI.md#ResolveProjectInitialProposal) | **Get** /v1/api/projects/initial-proposal-by-id/{proposalId} | Resolve a proposal deep link
[**ResolveProjectInitialProposalComment**](ProjectsAPI.md#ResolveProjectInitialProposalComment) | **Patch** /v1/api/projects/{id}/initial-proposal/comments/{commentId} | Resolve or reopen a proposal comment
[**ResumeProject**](ProjectsAPI.md#ResumeProject) | **Post** /v1/api/projects/{id}/resume | Resume a stopped project, or start one that never started
[**ReviseProjectInitialProposal**](ProjectsAPI.md#ReviseProjectInitialProposal) | **Post** /v1/api/projects/{id}/initial-proposal/revisions | Request a targeted AI revision
[**SendTaskComputerInput**](ProjectsAPI.md#SendTaskComputerInput) | **Post** /v1/api/projects/{id}/computers/{computerId}/input | Send input to the computer currently owned by the caller
[**SetPrimaryProjectRepo**](ProjectsAPI.md#SetPrimaryProjectRepo) | **Post** /v1/api/projects/{id}/repos/{repoId}/primary | Make a repository the project&#39;s primary
[**SetProjectMobileTargets**](ProjectsAPI.md#SetProjectMobileTargets) | **Put** /v1/api/projects/{id}/mobile/targets | Configure native app targets
[**StartProject**](ProjectsAPI.md#StartProject) | **Post** /v1/api/projects/{id}/start | Start the project&#39;s autonomous run
[**StartProjectDesktop**](ProjectsAPI.md#StartProjectDesktop) | **Post** /v1/api/projects/{id}/desktop | Start the desktop
[**StartProjectMobileAgentSession**](ProjectsAPI.md#StartProjectMobileAgentSession) | **Post** /v1/api/projects/{id}/mobile/agent-sessions | Start a native test device for this agent run
[**StartProjectMobileSession**](ProjectsAPI.md#StartProjectMobileSession) | **Post** /v1/api/projects/{id}/mobile/sessions | Start a private app preview
[**StopProject**](ProjectsAPI.md#StopProject) | **Post** /v1/api/projects/{id}/stop | Stop every agent working on the project
[**StopProjectMobileAgentSession**](ProjectsAPI.md#StopProjectMobileAgentSession) | **Delete** /v1/api/projects/{id}/mobile/agent-sessions/{sessionId} | Stop this agent run&#39;s native test device
[**StopProjectMobileSession**](ProjectsAPI.md#StopProjectMobileSession) | **Delete** /v1/api/projects/{id}/mobile/sessions/{sessionId} | End your private app preview
[**SuggestProjectStack**](ProjectsAPI.md#SuggestProjectStack) | **Post** /v1/api/projects/{id}/suggest-stack | Propose a stack string from the project&#39;s own evidence
[**UnarchiveProject**](ProjectsAPI.md#UnarchiveProject) | **Post** /v1/api/projects/{id}/unarchive | Restore an archived project
[**UndoCanvasAgentEdit**](ProjectsAPI.md#UndoCanvasAgentEdit) | **Post** /v1/api/projects/{id}/canvas/agent/undo | Undo hlix&#39;s most recent canvas edit
[**UpdateProject**](ProjectsAPI.md#UpdateProject) | **Patch** /v1/api/projects/{id} | Update a project&#39;s configuration
[**UpdateProjectRepo**](ProjectsAPI.md#UpdateProjectRepo) | **Patch** /v1/api/projects/{id}/repos/{repoId} | Update a repository&#39;s branch or label
[**WatchProjectDirector**](ProjectsAPI.md#WatchProjectDirector) | **Get** /v1/api/projects/{id}/director | Watch the Director Explainer&#39;s evolving video segments



## AddProjectInitialProposalComment

> InitialProposalComment AddProjectInitialProposalComment(ctx, id).CreateInitialProposalComment(createInitialProposalComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Comment on a proposal section

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
	createInitialProposalComment := *openapiclient.NewCreateInitialProposalComment("BlockId_example", "Body_example", "ParentId_example", "RevisionHash_example", "RevisionId_example", "SelectedText_example") // CreateInitialProposalComment | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AddProjectInitialProposalComment(context.Background(), id).CreateInitialProposalComment(createInitialProposalComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.AddProjectInitialProposalComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddProjectInitialProposalComment`: InitialProposalComment
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.AddProjectInitialProposalComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddProjectInitialProposalCommentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createInitialProposalComment** | [**CreateInitialProposalComment**](CreateInitialProposalComment.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposalComment**](InitialProposalComment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApplyCanvasAgentOps

> CanvasAgentWrite ApplyCanvasAgentOps(ctx, id).CanvasAgentOps(canvasAgentOps).XOrganizationId(xOrganizationId).Execute()

Draw on the project canvas as hlix, for the caller

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
	canvasAgentOps := *openapiclient.NewCanvasAgentOps([]openapiclient.CanvasAgentOpsOpsInner{openapiclient.CanvasAgentOps_ops_inner{CanvasAgentOpsOpsInnerOneOf: openapiclient.NewCanvasAgentOpsOpsInnerOneOf(*openapiclient.NewCanvasAgentOpsOpsInnerOneOfElement(float32(123), "Id_example", "Kind_example", float32(123), float32(123), float32(123), float32(123)), "Op_example")}}) // CanvasAgentOps | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ApplyCanvasAgentOps(context.Background(), id).CanvasAgentOps(canvasAgentOps).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ApplyCanvasAgentOps``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApplyCanvasAgentOps`: CanvasAgentWrite
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ApplyCanvasAgentOps`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApplyCanvasAgentOpsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **canvasAgentOps** | [**CanvasAgentOps**](CanvasAgentOps.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CanvasAgentWrite**](CanvasAgentWrite.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApproveProjectInitialProposal

> InitialProposal ApproveProjectInitialProposal(ctx, id).InitialProposalApprove(initialProposalApprove).XOrganizationId(xOrganizationId).Execute()

Approve the initial plan and release delivery

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
	initialProposalApprove := *openapiclient.NewInitialProposalApprove("ContentHash_example", "RevisionId_example") // InitialProposalApprove | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ApproveProjectInitialProposal(context.Background(), id).InitialProposalApprove(initialProposalApprove).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ApproveProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveProjectInitialProposal`: InitialProposal
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ApproveProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalApprove** | [**InitialProposalApprove**](InitialProposalApprove.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**InitialProposal**](InitialProposal.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ArchiveProject

> Project ArchiveProject(ctx, id).XOrganizationId(xOrganizationId).Execute()

Archive a project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ArchiveProject(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ArchiveProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ArchiveProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ArchiveProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchiveProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AssignProject

> ProjectRow AssignProject(ctx, id).Assign(assign).XOrganizationId(xOrganizationId).Execute()

Hand a project to a teammate

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
	assign := *openapiclient.NewAssign("UserId_example") // Assign | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AssignProject(context.Background(), id).Assign(assign).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.AssignProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AssignProject`: ProjectRow
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.AssignProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAssignProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assign** | [**Assign**](Assign.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

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


## AttachProjectGithubRepository

> ProjectRepo AttachProjectGithubRepository(ctx, id).AttachGithubRepository(attachGithubRepository).XOrganizationId(xOrganizationId).Execute()

Attach an existing GitHub repository by owner/name

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
	attachGithubRepository := *openapiclient.NewAttachGithubRepository("GithubRepository_example") // AttachGithubRepository | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AttachProjectGithubRepository(context.Background(), id).AttachGithubRepository(attachGithubRepository).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.AttachProjectGithubRepository``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AttachProjectGithubRepository`: ProjectRepo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.AttachProjectGithubRepository`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachProjectGithubRepositoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachGithubRepository** | [**AttachGithubRepository**](AttachGithubRepository.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AttachProjectRepo

> ProjectRepo AttachProjectRepo(ctx, id).AttachProjectRepo(attachProjectRepo).XOrganizationId(xOrganizationId).Execute()

Attach a repository to a project

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
	attachProjectRepo := *openapiclient.NewAttachProjectRepo("CloneUrl_example", "Name_example", "Owner_example") // AttachProjectRepo | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AttachProjectRepo(context.Background(), id).AttachProjectRepo(attachProjectRepo).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.AttachProjectRepo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AttachProjectRepo`: ProjectRepo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.AttachProjectRepo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAttachProjectRepoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachProjectRepo** | [**AttachProjectRepo**](AttachProjectRepo.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BuildDesign

> DesignDetail BuildDesign(ctx, projectId, designId).BuildDesign(buildDesign).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Submit implementation of an accepted prototype

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
	designId := "designId_example" // string | 
	buildDesign := *openapiclient.NewBuildDesign("RevisionId_example") // BuildDesign | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.BuildDesign(context.Background(), projectId, designId).BuildDesign(buildDesign).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.BuildDesign``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildDesign`: DesignDetail
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.BuildDesign`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiBuildDesignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **buildDesign** | [**BuildDesign**](BuildDesign.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BuildProjectMobileApp

> MobileBuild BuildProjectMobileApp(ctx, id).MobileBuildStart(mobileBuildStart).XOrganizationId(xOrganizationId).Execute()

Build a native app preview

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
	mobileBuildStart := *openapiclient.NewMobileBuildStart("TargetId_example") // MobileBuildStart | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.BuildProjectMobileApp(context.Background(), id).MobileBuildStart(mobileBuildStart).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.BuildProjectMobileApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildProjectMobileApp`: MobileBuild
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.BuildProjectMobileApp`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiBuildProjectMobileAppRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileBuildStart** | [**MobileBuildStart**](MobileBuildStart.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileBuild**](MobileBuild.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ControlTaskComputer

> TaskComputerControlResult ControlTaskComputer(ctx, id, computerId).TaskComputerControl(taskComputerControl).XOrganizationId(xOrganizationId).Execute()

Take, renew or release managed computer input

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
	computerId := "computerId_example" // string | 
	taskComputerControl := *openapiclient.NewTaskComputerControl("Action_example") // TaskComputerControl | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ControlTaskComputer(context.Background(), id, computerId).TaskComputerControl(taskComputerControl).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ControlTaskComputer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlTaskComputer`: TaskComputerControlResult
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ControlTaskComputer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**computerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiControlTaskComputerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **taskComputerControl** | [**TaskComputerControl**](TaskComputerControl.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**TaskComputerControlResult**](TaskComputerControlResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDesign

> Design CreateDesign(ctx, projectId).CreateDesign(createDesign).XOrganizationId(xOrganizationId).Execute()

Submit a native prototype brief

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
	createDesign := *openapiclient.NewCreateDesign("Intent_example", "Title_example") // CreateDesign | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateDesign(context.Background(), projectId).CreateDesign(createDesign).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.CreateDesign``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDesign`: Design
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.CreateDesign`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDesignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDesign** | [**CreateDesign**](CreateDesign.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Design**](Design.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDesignComment

> DesignComment CreateDesignComment(ctx, projectId, designId).CreateDesignComment(createDesignComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Comment on a frame without dispatching work

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
	designId := "designId_example" // string | 
	createDesignComment := *openapiclient.NewCreateDesignComment("Body_example", "FrameId_example", "RevisionId_example") // CreateDesignComment | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateDesignComment(context.Background(), projectId, designId).CreateDesignComment(createDesignComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.CreateDesignComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDesignComment`: DesignComment
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.CreateDesignComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateDesignCommentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDesignComment** | [**CreateDesignComment**](CreateDesignComment.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DesignComment**](DesignComment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateProject

> Project CreateProject(ctx).CreateProject(createProject).XOrganizationId(xOrganizationId).Execute()

Create a project

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
	createProject := *openapiclient.NewCreateProject() // CreateProject | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateProject(context.Background()).CreateProject(createProject).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.CreateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.CreateProject`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProject** | [**CreateProject**](CreateProject.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DecideDesign

> DesignDetail DecideDesign(ctx, projectId, designId).DesignDecision(designDecision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Accept a revision or submit revision work

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
	designId := "designId_example" // string | 
	designDecision := *openapiclient.NewDesignDecision("Decision_example", "RevisionId_example") // DesignDecision | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DecideDesign(context.Background(), projectId, designId).DesignDecision(designDecision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DecideDesign``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DecideDesign`: DesignDetail
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DecideDesign`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDecideDesignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **designDecision** | [**DesignDecision**](DesignDecision.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DecideProjectInitialProposal

> InitialProposal DecideProjectInitialProposal(ctx, id).InitialProposalClientDecision(initialProposalClientDecision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Record the invited client reviewer's optional decision

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
	initialProposalClientDecision := *openapiclient.NewInitialProposalClientDecision("Comment_example", "Decision_example", "RevisionHash_example", "RevisionId_example") // InitialProposalClientDecision | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DecideProjectInitialProposal(context.Background(), id).InitialProposalClientDecision(initialProposalClientDecision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DecideProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DecideProjectInitialProposal`: InitialProposal
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DecideProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDecideProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalClientDecision** | [**InitialProposalClientDecision**](InitialProposalClientDecision.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposal**](InitialProposal.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProject

> MessageAck DeleteProject(ctx, id).XOrganizationId(xOrganizationId).Execute()

Delete a project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DeleteProject(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DeleteProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteProject`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DeleteProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProjectRequest struct via the builder pattern


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


## DetachProjectRepo

> MessageAck DetachProjectRepo(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()

Detach a repository from a project

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
	repoId := "repoId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DetachProjectRepo(context.Background(), id, repoId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DetachProjectRepo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetachProjectRepo`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DetachProjectRepo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**repoId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetachProjectRepoRequest struct via the builder pattern


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


## DetectProjectCommands

> ProjectCommandDetection DetectProjectCommands(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()

Re-run command detection without writing anything

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
	body := map[string]interface{}{ ... } // map[string]interface{} | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DetectProjectCommands(context.Background(), id).Body(body).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DetectProjectCommands``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetectProjectCommands`: ProjectCommandDetection
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DetectProjectCommands`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDetectProjectCommandsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectCommandDetection**](ProjectCommandDetection.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadTaskComputerEvidence

> *os.File DownloadTaskComputerEvidence(ctx, id, computerId, kind).XOrganizationId(xOrganizationId).Execute()

Download retained execution screen or replay evidence

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
	computerId := "computerId_example" // string | 
	kind := "kind_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DownloadTaskComputerEvidence(context.Background(), id, computerId, kind).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DownloadTaskComputerEvidence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadTaskComputerEvidence`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DownloadTaskComputerEvidence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**computerId** | **string** |  | 
**kind** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadTaskComputerEvidenceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## EditProjectInitialProposal

> InitialProposalRevision EditProjectInitialProposal(ctx, id).InitialProposalManualRevision(initialProposalManualRevision).XOrganizationId(xOrganizationId).Execute()

Create a manual business-copy revision

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
	initialProposalManualRevision := *openapiclient.NewInitialProposalManualRevision("BaseHash_example", "BaseRevisionId_example", []openapiclient.InitialProposalDetailResponseRevisionContentBlocksInner{openapiclient.InitialProposalDetailResponse_revision_content_blocks_inner{InitialProposalDetailResponseRevisionContentBlocksInnerOneOf: openapiclient.NewInitialProposalDetailResponseRevisionContentBlocksInnerOneOf("Body_example", "Id_example", "Kind_example", "Title_example")}}) // InitialProposalManualRevision | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.EditProjectInitialProposal(context.Background(), id).InitialProposalManualRevision(initialProposalManualRevision).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.EditProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `EditProjectInitialProposal`: InitialProposalRevision
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.EditProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEditProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalManualRevision** | [**InitialProposalManualRevision**](InitialProposalManualRevision.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**InitialProposalRevision**](InitialProposalRevision.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCanvasAgentView

> CanvasAgentView GetCanvasAgentView(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read the project canvas as an agent may see it

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetCanvasAgentView(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetCanvasAgentView``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCanvasAgentView`: CanvasAgentView
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetCanvasAgentView`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCanvasAgentViewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CanvasAgentView**](CanvasAgentView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDesign

> DesignDetail GetDesign(ctx, projectId, designId).Revision(revision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a design revision and its review threads

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
	designId := "designId_example" // string | 
	revision := "revision_example" // string | Exact immutable revision; latest when omitted (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetDesign(context.Background(), projectId, designId).Revision(revision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetDesign``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDesign`: DesignDetail
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetDesign`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDesignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **revision** | **string** | Exact immutable revision; latest when omitted | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProject

> ProjectDetail GetProject(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProject(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProject`: ProjectDetail
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectDetail**](ProjectDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectArchitecture

> ApplicationArchitecture GetProjectArchitecture(ctx, id).CycleId(cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the application's source dependency graph

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
	cycleId := "cycleId_example" // string | Optional cycle UUID belonging to this project; scopes changed paths and recorded aggregate checks. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectArchitecture(context.Background(), id).CycleId(cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectArchitecture``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectArchitecture`: ApplicationArchitecture
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectArchitecture`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectArchitectureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Optional cycle UUID belonging to this project; scopes changed paths and recorded aggregate checks. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ApplicationArchitecture**](ApplicationArchitecture.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectArtifactUrl

> SignedArtifactUrl GetProjectArtifactUrl(ctx, id, filename).Download(download).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get a signed download URL for one project artifact

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
	filename := "filename_example" // string | 
	download := "download_example" // string | Set to `1` to receive the object's own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body's `url` is this same route with `download=1` already appended, so following it is the normal flow; any other value, absent included, answers the JSON. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectArtifactUrl(context.Background(), id, filename).Download(download).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectArtifactUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectArtifactUrl`: SignedArtifactUrl
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectArtifactUrl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**filename** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectArtifactUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Set to &#x60;1&#x60; to receive the object&#39;s own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body&#39;s &#x60;url&#x60; is this same route with &#x60;download&#x3D;1&#x60; already appended, so following it is the normal flow; any other value, absent included, answers the JSON. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectBoard

> ProjectBoard GetProjectBoard(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the rows a project's board shows

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectBoard(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectBoard``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectBoard`: ProjectBoard
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectBoard`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectBoardRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectBoard**](ProjectBoard.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectBudget

> ProjectBudget GetProjectBudget(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get the project's delivery budget and spend to date

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectBudget(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectBudget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectBudget`: ProjectBudget
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectBudget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectBudgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectBudget**](ProjectBudget.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectCanvas

> ProjectCanvas GetProjectCanvas(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the project canvas without waking its Cloud Machine

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectCanvas(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectCanvas``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectCanvas`: ProjectCanvas
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectCanvas`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectCanvasRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectCanvas**](ProjectCanvas.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectCycleMetrics

> CycleMetrics GetProjectCycleMetrics(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get a project's flow metrics computed from cycle stage history

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectCycleMetrics(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectCycleMetrics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectCycleMetrics`: CycleMetrics
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectCycleMetrics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectCycleMetricsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CycleMetrics**](CycleMetrics.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectDesktop

> ProjectDesktopAccess GetProjectDesktop(ctx, id).XOrganizationId(xOrganizationId).Execute()

Report whether a graphical desktop is reachable

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectDesktop(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectDesktop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectDesktop`: ProjectDesktopAccess
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectDesktop`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectDesktopRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectDesktopAccess**](ProjectDesktopAccess.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectDirectorClip

> SignedArtifactUrl GetProjectDirectorClip(ctx, id, clipId).CycleId(cycleId).Language(language).Download(download).XOrganizationId(xOrganizationId).Execute()

Read an audience-scoped Director video segment

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
	clipId := "clipId_example" // string | 
	cycleId := "cycleId_example" // string | Selected chapter (optional)
	language := "language_example" // string | en, de or fr (optional)
	download := "download_example" // string | 1 for authenticated video bytes when no signed URL is available (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectDirectorClip(context.Background(), id, clipId).CycleId(cycleId).Language(language).Download(download).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectDirectorClip``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectDirectorClip`: SignedArtifactUrl
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectDirectorClip`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**clipId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectDirectorClipRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **cycleId** | **string** | Selected chapter | 
 **language** | **string** | en, de or fr | 
 **download** | **string** | 1 for authenticated video bytes when no signed URL is available | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectEnvironment

> ProjectEnvironment GetProjectEnvironment(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read where the project's boxes start from

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectEnvironment(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectEnvironment`: ProjectEnvironment
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectEnvironmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectEnvironment**](ProjectEnvironment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectInitialProposal

> InitialProposalDetailResponse GetProjectInitialProposal(ctx, id).Revision(revision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the current initial SDD/SOW

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
	revision := "revision_example" // string | Revision number to read; agency only. Clients always receive the published revision. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectInitialProposal(context.Background(), id).Revision(revision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectInitialProposal`: InitialProposalDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revision** | **string** | Revision number to read; agency only. Clients always receive the published revision. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectInitialProposalLogo

> *os.File GetProjectInitialProposalLogo(ctx, id).RevisionId(revisionId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the frozen agency logo

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
	revisionId := "revisionId_example" // string | Revision whose frozen logo should be read; clients must name the published revision. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectInitialProposalLogo(context.Background(), id).RevisionId(revisionId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectInitialProposalLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectInitialProposalLogo`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectInitialProposalLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectInitialProposalLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revisionId** | **string** | Revision whose frozen logo should be read; clients must name the published revision. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: image/png, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectMobileAgentSession

> MobileAgentSession GetProjectMobileAgentSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()

Read this agent run's native test device

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
	sessionId := "sessionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileAgentSession(context.Background(), id, sessionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectMobileAgentSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectMobileAgentSession`: MobileAgentSession
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectMobileAgentSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**sessionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectMobileAgentSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileAgentSession**](MobileAgentSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectMobileBuilds

> MobileBuildsView GetProjectMobileBuilds(ctx, id).XOrganizationId(xOrganizationId).Execute()

List saved native builds

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileBuilds(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectMobileBuilds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectMobileBuilds`: MobileBuildsView
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectMobileBuilds`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectMobileBuildsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileBuildsView**](MobileBuildsView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectMobileSession

> MobileSession GetProjectMobileSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()

Read your private app preview

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
	sessionId := "sessionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileSession(context.Background(), id, sessionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectMobileSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectMobileSession`: MobileSession
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectMobileSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**sessionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectMobileSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileSession**](MobileSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectMobileTargets

> MobileTargetsView GetProjectMobileTargets(ctx, id).XOrganizationId(xOrganizationId).Execute()

List native app targets

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileTargets(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectMobileTargets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectMobileTargets`: MobileTargetsView
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectMobileTargets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectMobileTargetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileTargetsView**](MobileTargetsView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectReview

> ProjectReview GetProjectReview(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read recorded verification evidence for completed project cycles

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectReview(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectReview`: ProjectReview
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectReview**](ProjectReview.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectRoadmap

> ProjectRoadmap GetProjectRoadmap(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the project's roadmap

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectRoadmap(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectRoadmap``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectRoadmap`: ProjectRoadmap
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectRoadmap`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectRoadmapRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectRoadmap**](ProjectRoadmap.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectRunDiagnostics

> ProjectDiagnostics GetProjectRunDiagnostics(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read why the project's run failed or is parked

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectRunDiagnostics(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectRunDiagnostics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectRunDiagnostics`: ProjectDiagnostics
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectRunDiagnostics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectRunDiagnosticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectDiagnostics**](ProjectDiagnostics.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectSequence

> Sequence GetProjectSequence(ctx, id).CycleId(cycleId).Language(language).XOrganizationId(xOrganizationId).Execute()

Watch a cycle's narrated Sequence

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
	cycleId := "cycleId_example" // string | Cycle in this project; defaults to the active or most recent cycle. (optional)
	language := "language_example" // string | Narration language: en (default), de, or fr. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectSequence(context.Background(), id).CycleId(cycleId).Language(language).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectSequence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectSequence`: Sequence
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectSequence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectSequenceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Cycle in this project; defaults to the active or most recent cycle. | 
 **language** | **string** | Narration language: en (default), de, or fr. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Sequence**](Sequence.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectStatus

> ProjectStatusSummary GetProjectStatus(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read where a project stands, in a person's terms

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectStatus(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectStatus`: ProjectStatusSummary
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectStatusSummary**](ProjectStatusSummary.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectTeamInsights

> ProjectTeamInsights GetProjectTeamInsights(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get a project's all-time cloud machine totals and its expected finish

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectTeamInsights(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectTeamInsights``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectTeamInsights`: ProjectTeamInsights
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectTeamInsights`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectTeamInsightsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectTeamInsights**](ProjectTeamInsights.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectTerminalAccess

> ProjectTerminalAccess GetProjectTerminalAccess(ctx, id).XOrganizationId(xOrganizationId).Execute()

Open a shell into the project's Cloud Machine

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectTerminalAccess(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectTerminalAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectTerminalAccess`: ProjectTerminalAccess
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectTerminalAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectTerminalAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectTerminalAccess**](ProjectTerminalAccess.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectThreadDirectory

> ProjectThreadDirectory GetProjectThreadDirectory(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the project's conversation tree

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectThreadDirectory(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectThreadDirectory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectThreadDirectory`: ProjectThreadDirectory
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectThreadDirectory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectThreadDirectoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectThreadDirectory**](ProjectThreadDirectory.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectUsage

> AgentUsageRollup GetProjectUsage(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get the project's cost and token roll-up

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectUsage(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectUsage`: AgentUsageRollup
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProjectUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AgentUsageRollup**](AgentUsageRollup.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTaskComputer

> TaskComputerStatus GetTaskComputer(ctx, id, computerId).XOrganizationId(xOrganizationId).Execute()

Read the exact execution computer's availability

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
	computerId := "computerId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetTaskComputer(context.Background(), id, computerId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetTaskComputer``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTaskComputer`: TaskComputerStatus
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetTaskComputer`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**computerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTaskComputerRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**TaskComputerStatus**](TaskComputerStatus.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## KeepProjectEnvironmentAlive

> ProjectEnvironmentKeepAlive KeepProjectEnvironmentAlive(ctx, id).XOrganizationId(xOrganizationId).Execute()

Tell a running environment it is still in use

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.KeepProjectEnvironmentAlive(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.KeepProjectEnvironmentAlive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `KeepProjectEnvironmentAlive`: ProjectEnvironmentKeepAlive
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.KeepProjectEnvironmentAlive`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiKeepProjectEnvironmentAliveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectEnvironmentKeepAlive**](ProjectEnvironmentKeepAlive.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDesigns

> []Design ListDesigns(ctx, projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List native project designs

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
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListDesigns(context.Background(), projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListDesigns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDesigns`: []Design
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListDesigns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDesignsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]Design**](Design.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectArtifacts

> []StoredArtifact ListProjectArtifacts(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List a project's stored artifacts

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectArtifacts(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectArtifacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectArtifacts`: []StoredArtifact
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectArtifacts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectArtifactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]StoredArtifact**](StoredArtifact.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectImageBuilds

> []ProjectImageBuild ListProjectImageBuilds(ctx, id).XOrganizationId(xOrganizationId).Execute()

List the project's Cloud Machine image builds

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectImageBuilds(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectImageBuilds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectImageBuilds`: []ProjectImageBuild
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectImageBuilds`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectImageBuildsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]ProjectImageBuild**](ProjectImageBuild.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectInitialProposalComments

> InitialProposalCommentsResponse ListProjectInitialProposalComments(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List section-anchored proposal comments

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectInitialProposalComments(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectInitialProposalComments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectInitialProposalComments`: InitialProposalCommentsResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectInitialProposalComments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectInitialProposalCommentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposalCommentsResponse**](InitialProposalCommentsResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectInitialProposalRevisions

> InitialProposalHistoryResponse ListProjectInitialProposalRevisions(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List proposal revision history

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectInitialProposalRevisions(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectInitialProposalRevisions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectInitialProposalRevisions`: InitialProposalHistoryResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectInitialProposalRevisions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectInitialProposalRevisionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposalHistoryResponse**](InitialProposalHistoryResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectLinearSessions

> ProjectLinearSessions ListProjectLinearSessions(ctx, id).XOrganizationId(xOrganizationId).Execute()

List the Linear conversations delegated into this project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectLinearSessions(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectLinearSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectLinearSessions`: ProjectLinearSessions
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectLinearSessions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectLinearSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectLinearSessions**](ProjectLinearSessions.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectMessages

> WireMessagePage ListProjectMessages(ctx, id).AgentId(agentId).Limit(limit).Before(before).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the project's conversation

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
	agentId := "agentId_example" // string | Read this agent's project thread instead of the conductor's. (optional)
	limit := "limit_example" // string | How many stored turns one page holds, 1 to 200. Default 50. (optional)
	before := "before_example" // string | The `nextCursor` of the page you have: read the turns older than it. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectMessages(context.Background(), id).AgentId(agentId).Limit(limit).Before(before).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectMessages`: WireMessagePage
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectMessages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectMessagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentId** | **string** | Read this agent&#39;s project thread instead of the conductor&#39;s. | 
 **limit** | **string** | How many stored turns one page holds, 1 to 200. Default 50. | 
 **before** | **string** | The &#x60;nextCursor&#x60; of the page you have: read the turns older than it. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**WireMessagePage**](WireMessagePage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectRepos

> []ProjectRepo ListProjectRepos(ctx, id).XOrganizationId(xOrganizationId).Execute()

List a project's repositories

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectRepos(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjectRepos``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectRepos`: []ProjectRepo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjectRepos`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectReposRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjects

> []ProjectSummary ListProjects(ctx).IncludeArchived(includeArchived).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List the workspace's projects

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
	includeArchived := "includeArchived_example" // string | Set to `true` to include archived projects. They are hidden by default. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjects(context.Background()).IncludeArchived(includeArchived).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjects`: []ProjectSummary
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeArchived** | **string** | Set to &#x60;true&#x60; to include archived projects. They are hidden by default. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]ProjectSummary**](ProjectSummary.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTaskComputers

> TaskComputers ListTaskComputers(ctx, id).XOrganizationId(xOrganizationId).Execute()

List the project's task execution computers

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListTaskComputers(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListTaskComputers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTaskComputers`: TaskComputers
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListTaskComputers`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListTaskComputersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**TaskComputers**](TaskComputers.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MergeProjectReview

> MessageAck MergeProjectReview(ctx, id).MergeProjectReview(mergeProjectReview).XOrganizationId(xOrganizationId).Execute()

Merge a reviewed preview pull request at its exact head commit

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
	mergeProjectReview := *openapiclient.NewMergeProjectReview("HeadSha_example", "RepoId_example") // MergeProjectReview | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.MergeProjectReview(context.Background(), id).MergeProjectReview(mergeProjectReview).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.MergeProjectReview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MergeProjectReview`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.MergeProjectReview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMergeProjectReviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mergeProjectReview** | [**MergeProjectReview**](MergeProjectReview.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectWorkspaceExec

> WorkspaceExecResult ProjectWorkspaceExec(ctx, id).ProjectWorkspaceExec(projectWorkspaceExec).XOrganizationId(xOrganizationId).Execute()

Run a command in the project's Cloud Machine

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
	projectWorkspaceExec := *openapiclient.NewProjectWorkspaceExec("Command_example") // ProjectWorkspaceExec | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ProjectWorkspaceExec(context.Background(), id).ProjectWorkspaceExec(projectWorkspaceExec).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ProjectWorkspaceExec``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectWorkspaceExec`: WorkspaceExecResult
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ProjectWorkspaceExec`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectWorkspaceExecRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectWorkspaceExec** | [**ProjectWorkspaceExec**](ProjectWorkspaceExec.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceExecResult**](WorkspaceExecResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProjectWorkspaceFs

> WorkspaceFsResult ProjectWorkspaceFs(ctx, id).ProjectWorkspaceFs(projectWorkspaceFs).XOrganizationId(xOrganizationId).Execute()

Read or write a file in the project's Cloud Machine

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
	projectWorkspaceFs := *openapiclient.NewProjectWorkspaceFs("Op_example", "Path_example") // ProjectWorkspaceFs | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ProjectWorkspaceFs(context.Background(), id).ProjectWorkspaceFs(projectWorkspaceFs).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ProjectWorkspaceFs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProjectWorkspaceFs`: WorkspaceFsResult
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ProjectWorkspaceFs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProjectWorkspaceFsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectWorkspaceFs** | [**ProjectWorkspaceFs**](ProjectWorkspaceFs.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**WorkspaceFsResult**](WorkspaceFsResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishDesignRevision

> DesignDetail PublishDesignRevision(ctx, projectId, designId).PublishDesignRevision(publishDesignRevision).XOrganizationId(xOrganizationId).Execute()

Publish a tested playable prototype

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
	designId := "designId_example" // string | 
	publishDesignRevision := *openapiclient.NewPublishDesignRevision(*openapiclient.NewDesignDetailRevisionContext(), []openapiclient.DesignDetailRevisionEvidenceInner{*openapiclient.NewDesignDetailRevisionEvidenceInner("FlowId_example", "Note_example", "Result_example")}, "ExpectedRevisionId_example", []openapiclient.DesignDetailRevisionFlowsInner{*openapiclient.NewDesignDetailRevisionFlowsInner("EntryFrameId_example", []string{"FrameIds_example"}, "Id_example", "Name_example")}, []openapiclient.DesignDetailRevisionFramesInner{*openapiclient.NewDesignDetailRevisionFramesInner(int32(123), "Id_example", "Name_example", "Route_example", int32(123))}, "Html_example") // PublishDesignRevision | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.PublishDesignRevision(context.Background(), projectId, designId).PublishDesignRevision(publishDesignRevision).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.PublishDesignRevision``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishDesignRevision`: DesignDetail
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.PublishDesignRevision`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublishDesignRevisionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **publishDesignRevision** | [**PublishDesignRevision**](PublishDesignRevision.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishProjectInitialProposal

> InitialProposalDetailResponse PublishProjectInitialProposal(ctx, id).InitialProposalPublish(initialProposalPublish).XOrganizationId(xOrganizationId).Execute()

Publish a branded proposal revision

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
	initialProposalPublish := *openapiclient.NewInitialProposalPublish() // InitialProposalPublish | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.PublishProjectInitialProposal(context.Background(), id).InitialProposalPublish(initialProposalPublish).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.PublishProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishProjectInitialProposal`: InitialProposalDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.PublishProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublishProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalPublish** | [**InitialProposalPublish**](InitialProposalPublish.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestProjectDelivery

> ProjectDelivery RequestProjectDelivery(ctx, id).XOrganizationId(xOrganizationId).Execute()

Open the project's pull request now

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.RequestProjectDelivery(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.RequestProjectDelivery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestProjectDelivery`: ProjectDelivery
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.RequestProjectDelivery`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRequestProjectDeliveryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectDelivery**](ProjectDelivery.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveDesignComment

> DesignComment ResolveDesignComment(ctx, projectId, designId, commentId).ResolveDesignComment(resolveDesignComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Resolve or reopen a design comment

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
	designId := "designId_example" // string | 
	commentId := "commentId_example" // string | 
	resolveDesignComment := *openapiclient.NewResolveDesignComment(false) // ResolveDesignComment | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveDesignComment(context.Background(), projectId, designId, commentId).ResolveDesignComment(resolveDesignComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ResolveDesignComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveDesignComment`: DesignComment
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ResolveDesignComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**designId** | **string** |  | 
**commentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolveDesignCommentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **resolveDesignComment** | [**ResolveDesignComment**](ResolveDesignComment.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DesignComment**](DesignComment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveProjectInitialProposal

> InitialProposalDetailResponse ResolveProjectInitialProposal(ctx, proposalId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Resolve a proposal deep link

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
	proposalId := "proposalId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveProjectInitialProposal(context.Background(), proposalId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ResolveProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveProjectInitialProposal`: InitialProposalDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ResolveProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**proposalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolveProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveProjectInitialProposalComment

> InitialProposalComment ResolveProjectInitialProposalComment(ctx, id, commentId).InitialProposalResolveComment(initialProposalResolveComment).XOrganizationId(xOrganizationId).Execute()

Resolve or reopen a proposal comment

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
	commentId := "commentId_example" // string | 
	initialProposalResolveComment := *openapiclient.NewInitialProposalResolveComment(false) // InitialProposalResolveComment | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveProjectInitialProposalComment(context.Background(), id, commentId).InitialProposalResolveComment(initialProposalResolveComment).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ResolveProjectInitialProposalComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveProjectInitialProposalComment`: InitialProposalComment
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ResolveProjectInitialProposalComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**commentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolveProjectInitialProposalCommentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **initialProposalResolveComment** | [**InitialProposalResolveComment**](InitialProposalResolveComment.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**InitialProposalComment**](InitialProposalComment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResumeProject

> ProjectResumed ResumeProject(ctx, id).XOrganizationId(xOrganizationId).Execute()

Resume a stopped project, or start one that never started

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResumeProject(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ResumeProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResumeProject`: ProjectResumed
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ResumeProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResumeProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectResumed**](ProjectResumed.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReviseProjectInitialProposal

> InitialProposalRevision ReviseProjectInitialProposal(ctx, id).InitialProposalRevisionTarget(initialProposalRevisionTarget).XOrganizationId(xOrganizationId).Execute()

Request a targeted AI revision

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
	initialProposalRevisionTarget := *openapiclient.NewInitialProposalRevisionTarget("BaseHash_example", "BaseRevisionId_example", "Instruction_example") // InitialProposalRevisionTarget | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ReviseProjectInitialProposal(context.Background(), id).InitialProposalRevisionTarget(initialProposalRevisionTarget).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ReviseProjectInitialProposal``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReviseProjectInitialProposal`: InitialProposalRevision
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ReviseProjectInitialProposal`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReviseProjectInitialProposalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalRevisionTarget** | [**InitialProposalRevisionTarget**](InitialProposalRevisionTarget.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**InitialProposalRevision**](InitialProposalRevision.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendTaskComputerInput

> TaskComputerInputResult SendTaskComputerInput(ctx, id, computerId).TaskComputerInput(taskComputerInput).XOrganizationId(xOrganizationId).Execute()

Send input to the computer currently owned by the caller

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
	computerId := "computerId_example" // string | 
	taskComputerInput := *openapiclient.NewTaskComputerInput(int32(123), openapiclient.TaskComputerInput_input{TaskComputerInputInputOneOf: openapiclient.NewTaskComputerInputInputOneOf("Action_example")}) // TaskComputerInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SendTaskComputerInput(context.Background(), id, computerId).TaskComputerInput(taskComputerInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.SendTaskComputerInput``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendTaskComputerInput`: TaskComputerInputResult
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.SendTaskComputerInput`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**computerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendTaskComputerInputRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **taskComputerInput** | [**TaskComputerInput**](TaskComputerInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**TaskComputerInputResult**](TaskComputerInputResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPrimaryProjectRepo

> ProjectRepo SetPrimaryProjectRepo(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()

Make a repository the project's primary

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
	repoId := "repoId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SetPrimaryProjectRepo(context.Background(), id, repoId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.SetPrimaryProjectRepo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPrimaryProjectRepo`: ProjectRepo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.SetPrimaryProjectRepo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**repoId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPrimaryProjectRepoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetProjectMobileTargets

> MobileTargetsSaved SetProjectMobileTargets(ctx, id).MobileTargetsInput(mobileTargetsInput).XOrganizationId(xOrganizationId).Execute()

Configure native app targets

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
	mobileTargetsInput := *openapiclient.NewMobileTargetsInput([]openapiclient.MobileTargetsInputTargetsInner{*openapiclient.NewMobileTargetsInputTargetsInner("BuildCommand_example", "BundleId_example", "Framework_example", "Id_example", "Name_example", "OutputPath_example", "Path_example", "Platform_example", "RepoId_example")}) // MobileTargetsInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SetProjectMobileTargets(context.Background(), id).MobileTargetsInput(mobileTargetsInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.SetProjectMobileTargets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetProjectMobileTargets`: MobileTargetsSaved
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.SetProjectMobileTargets`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetProjectMobileTargetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileTargetsInput** | [**MobileTargetsInput**](MobileTargetsInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileTargetsSaved**](MobileTargetsSaved.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProject

> ProjectStarted StartProject(ctx, id).StartProject(startProject).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Start the project's autonomous run

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
	startProject := *openapiclient.NewStartProject("Brief_example") // StartProject | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProject(context.Background(), id).StartProject(startProject).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StartProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartProject`: ProjectStarted
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StartProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStartProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startProject** | [**StartProject**](StartProject.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectStarted**](ProjectStarted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProjectDesktop

> ProjectDesktopAccess StartProjectDesktop(ctx, id).XOrganizationId(xOrganizationId).Execute()

Start the desktop

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProjectDesktop(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StartProjectDesktop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartProjectDesktop`: ProjectDesktopAccess
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StartProjectDesktop`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStartProjectDesktopRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectDesktopAccess**](ProjectDesktopAccess.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProjectMobileAgentSession

> MobileAgentSession StartProjectMobileAgentSession(ctx, id).MobileAgentSessionStart(mobileAgentSessionStart).XOrganizationId(xOrganizationId).Execute()

Start a native test device for this agent run

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
	mobileAgentSessionStart := *openapiclient.NewMobileAgentSessionStart("BuildId_example", "RequestId_example") // MobileAgentSessionStart | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProjectMobileAgentSession(context.Background(), id).MobileAgentSessionStart(mobileAgentSessionStart).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StartProjectMobileAgentSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartProjectMobileAgentSession`: MobileAgentSession
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StartProjectMobileAgentSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStartProjectMobileAgentSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileAgentSessionStart** | [**MobileAgentSessionStart**](MobileAgentSessionStart.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileAgentSession**](MobileAgentSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProjectMobileSession

> MobileSession StartProjectMobileSession(ctx, id).MobileSessionStart(mobileSessionStart).XOrganizationId(xOrganizationId).Execute()

Start a private app preview

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
	mobileSessionStart := *openapiclient.NewMobileSessionStart("BuildId_example", "TabId_example") // MobileSessionStart | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProjectMobileSession(context.Background(), id).MobileSessionStart(mobileSessionStart).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StartProjectMobileSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartProjectMobileSession`: MobileSession
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StartProjectMobileSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStartProjectMobileSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileSessionStart** | [**MobileSessionStart**](MobileSessionStart.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileSession**](MobileSession.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopProject

> ProjectStopped StopProject(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Stop every agent working on the project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StopProject(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StopProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopProject`: ProjectStopped
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StopProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStopProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectStopped**](ProjectStopped.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopProjectMobileAgentSession

> MobileStopped StopProjectMobileAgentSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()

Stop this agent run's native test device

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
	sessionId := "sessionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StopProjectMobileAgentSession(context.Background(), id, sessionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StopProjectMobileAgentSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopProjectMobileAgentSession`: MobileStopped
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StopProjectMobileAgentSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**sessionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStopProjectMobileAgentSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileStopped**](MobileStopped.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopProjectMobileSession

> MobileStopped StopProjectMobileSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()

End your private app preview

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
	sessionId := "sessionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StopProjectMobileSession(context.Background(), id, sessionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.StopProjectMobileSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopProjectMobileSession`: MobileStopped
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.StopProjectMobileSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**sessionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStopProjectMobileSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**MobileStopped**](MobileStopped.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SuggestProjectStack

> ProjectStackSuggestion SuggestProjectStack(ctx, id).XOrganizationId(xOrganizationId).Execute()

Propose a stack string from the project's own evidence

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SuggestProjectStack(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.SuggestProjectStack``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SuggestProjectStack`: ProjectStackSuggestion
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.SuggestProjectStack`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSuggestProjectStackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectStackSuggestion**](ProjectStackSuggestion.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnarchiveProject

> Project UnarchiveProject(ctx, id).XOrganizationId(xOrganizationId).Execute()

Restore an archived project

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UnarchiveProject(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.UnarchiveProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnarchiveProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.UnarchiveProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnarchiveProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UndoCanvasAgentEdit

> CanvasAgentUndo UndoCanvasAgentEdit(ctx, id).XOrganizationId(xOrganizationId).Execute()

Undo hlix's most recent canvas edit

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
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UndoCanvasAgentEdit(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.UndoCanvasAgentEdit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UndoCanvasAgentEdit`: CanvasAgentUndo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.UndoCanvasAgentEdit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUndoCanvasAgentEditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CanvasAgentUndo**](CanvasAgentUndo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProject

> Project UpdateProject(ctx, id).UpdateProject(updateProject).XOrganizationId(xOrganizationId).Execute()

Update a project's configuration

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
	updateProject := *openapiclient.NewUpdateProject() // UpdateProject | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UpdateProject(context.Background(), id).UpdateProject(updateProject).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.UpdateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProject`: Project
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.UpdateProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateProject** | [**UpdateProject**](UpdateProject.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProjectRepo

> ProjectRepo UpdateProjectRepo(ctx, id, repoId).UpdateProjectRepo(updateProjectRepo).XOrganizationId(xOrganizationId).Execute()

Update a repository's branch or label

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
	repoId := "repoId_example" // string | 
	updateProjectRepo := *openapiclient.NewUpdateProjectRepo() // UpdateProjectRepo | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UpdateProjectRepo(context.Background(), id, repoId).UpdateProjectRepo(updateProjectRepo).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.UpdateProjectRepo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProjectRepo`: ProjectRepo
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.UpdateProjectRepo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**repoId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProjectRepoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateProjectRepo** | [**UpdateProjectRepo**](UpdateProjectRepo.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## WatchProjectDirector

> DirectorState WatchProjectDirector(ctx, id).CycleId(cycleId).Language(language).Retry(retry).XOrganizationId(xOrganizationId).Execute()

Watch the Director Explainer's evolving video segments

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
	cycleId := "cycleId_example" // string | Selected chapter (optional)
	language := "language_example" // string | en, de or fr (optional)
	retry := "retry_example" // string | 1 to retry a failed render after automatic retries are exhausted (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.WatchProjectDirector(context.Background(), id).CycleId(cycleId).Language(language).Retry(retry).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.WatchProjectDirector``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `WatchProjectDirector`: DirectorState
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.WatchProjectDirector`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiWatchProjectDirectorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Selected chapter | 
 **language** | **string** | en, de or fr | 
 **retry** | **string** | 1 to retry a failed render after automatic retries are exhausted | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DirectorState**](DirectorState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

