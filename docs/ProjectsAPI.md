# ProjectsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddProjectInitialProposalComment**](ProjectsAPI.md#addprojectinitialproposalcomment) | **Post** /v1/api/projects/{id}/initial-proposal/comments | Comment on a proposal section
[**ApplyCanvasAgentOps**](ProjectsAPI.md#applycanvasagentops) | **Post** /v1/api/projects/{id}/canvas/agent/ops | Draw on the project canvas as hlix, for the caller
[**ApproveProjectInitialProposal**](ProjectsAPI.md#approveprojectinitialproposal) | **Post** /v1/api/projects/{id}/initial-proposal/approve | Approve the initial plan and release delivery
[**ArchiveProject**](ProjectsAPI.md#archiveproject) | **Post** /v1/api/projects/{id}/archive | Archive a project
[**AssignProject**](ProjectsAPI.md#assignproject) | **Patch** /v1/api/projects/{id}/assign | Hand a project to a teammate
[**AttachProjectGithubRepository**](ProjectsAPI.md#attachprojectgithubrepository) | **Post** /v1/api/projects/{id}/repos/github | Attach an existing GitHub repository by owner/name
[**AttachProjectRepo**](ProjectsAPI.md#attachprojectrepo) | **Post** /v1/api/projects/{id}/repos | Attach a repository to a project
[**BuildDesign**](ProjectsAPI.md#builddesign) | **Post** /v1/api/projects/{projectId}/designs/{designId}/build | Submit implementation of an accepted prototype
[**BuildProjectMobileApp**](ProjectsAPI.md#buildprojectmobileapp) | **Post** /v1/api/projects/{id}/mobile/builds | Build a native app preview
[**ControlDesktop**](ProjectsAPI.md#controldesktop) | **Post** /v1/api/projects/{id}/desktops/{desktopId}/control | Take control of a Desktop, or give it back
[**CreateDesign**](ProjectsAPI.md#createdesign) | **Post** /v1/api/projects/{projectId}/designs | Submit a native prototype brief
[**CreateDesignComment**](ProjectsAPI.md#createdesigncomment) | **Post** /v1/api/projects/{projectId}/designs/{designId}/comments | Comment on a frame without dispatching work
[**CreateProject**](ProjectsAPI.md#createproject) | **Post** /v1/api/projects | Create a project
[**DecideDesign**](ProjectsAPI.md#decidedesign) | **Post** /v1/api/projects/{projectId}/designs/{designId}/decisions | Accept a revision or submit revision work
[**DecideProjectInitialProposal**](ProjectsAPI.md#decideprojectinitialproposal) | **Post** /v1/api/projects/{id}/initial-proposal/decision | Record the invited client review agent&#39;s optional decision
[**DeleteProject**](ProjectsAPI.md#deleteproject) | **Delete** /v1/api/projects/{id} | Delete a project
[**DetachProjectRepo**](ProjectsAPI.md#detachprojectrepo) | **Delete** /v1/api/projects/{id}/repos/{repoId} | Detach a repository from a project
[**DetectProjectCommands**](ProjectsAPI.md#detectprojectcommands) | **Post** /v1/api/projects/{id}/detect-commands | Re-run command detection without writing anything
[**DownloadDesktopEvidence**](ProjectsAPI.md#downloaddesktopevidence) | **Get** /v1/api/projects/{id}/desktops/{desktopId}/evidence/{kind} | Download the screen or replay a finished run kept
[**EditProjectInitialProposal**](ProjectsAPI.md#editprojectinitialproposal) | **Put** /v1/api/projects/{id}/initial-proposal/revisions/manual | Create a manual business-copy revision
[**GetCanvasAgentView**](ProjectsAPI.md#getcanvasagentview) | **Get** /v1/api/projects/{id}/canvas/agent | Read the project canvas as an agent may see it
[**GetDesign**](ProjectsAPI.md#getdesign) | **Get** /v1/api/projects/{projectId}/designs/{designId} | Read a design revision and its review threads
[**GetDesktop**](ProjectsAPI.md#getdesktop) | **Get** /v1/api/projects/{id}/desktops/{desktopId} | Read one Desktop and the links to its screen
[**GetProject**](ProjectsAPI.md#getproject) | **Get** /v1/api/projects/{id} | Get one project
[**GetProjectArchitecture**](ProjectsAPI.md#getprojectarchitecture) | **Get** /v1/api/projects/{id}/architecture | Read the application&#39;s source dependency graph
[**GetProjectArtifactUrl**](ProjectsAPI.md#getprojectartifacturl) | **Get** /v1/api/projects/{id}/artifacts/{filename} | Get a signed download URL for one project artifact
[**GetProjectBoard**](ProjectsAPI.md#getprojectboard) | **Get** /v1/api/projects/{id}/board | Read the rows a project&#39;s board shows
[**GetProjectBudget**](ProjectsAPI.md#getprojectbudget) | **Get** /v1/api/projects/{id}/budget | Get the project&#39;s delivery budget and spend to date
[**GetProjectCanvas**](ProjectsAPI.md#getprojectcanvas) | **Get** /v1/api/projects/{id}/canvas | Read the project canvas without waking its Cloud Machine
[**GetProjectChatDirectory**](ProjectsAPI.md#getprojectchatdirectory) | **Get** /v1/api/projects/{id}/chats | Get the project&#39;s conversation tree
[**GetProjectCycleMetrics**](ProjectsAPI.md#getprojectcyclemetrics) | **Get** /v1/api/projects/{id}/cycle-metrics | Get a project&#39;s flow metrics computed from cycle stage history
[**GetProjectDirectorClip**](ProjectsAPI.md#getprojectdirectorclip) | **Get** /v1/api/projects/{id}/director/clips/{clipId} | Read an audience-scoped Director video segment
[**GetProjectEnvironment**](ProjectsAPI.md#getprojectenvironment) | **Get** /v1/api/projects/{id}/environment | Read the project&#39;s saved Cloud Machine environment
[**GetProjectInitialProposal**](ProjectsAPI.md#getprojectinitialproposal) | **Get** /v1/api/projects/{id}/initial-proposal | Read the current initial SDD/SOW
[**GetProjectInitialProposalLogo**](ProjectsAPI.md#getprojectinitialproposallogo) | **Get** /v1/api/projects/{id}/initial-proposal/logo | Read the frozen agency logo
[**GetProjectMobileAgentSession**](ProjectsAPI.md#getprojectmobileagentsession) | **Get** /v1/api/projects/{id}/mobile/agent-sessions/{sessionId} | Read this agent run&#39;s native test device
[**GetProjectMobileBuilds**](ProjectsAPI.md#getprojectmobilebuilds) | **Get** /v1/api/projects/{id}/mobile/builds | List saved native builds
[**GetProjectMobileSession**](ProjectsAPI.md#getprojectmobilesession) | **Get** /v1/api/projects/{id}/mobile/sessions/{sessionId} | Read your private app preview
[**GetProjectMobileTargets**](ProjectsAPI.md#getprojectmobiletargets) | **Get** /v1/api/projects/{id}/mobile/targets | List native app targets
[**GetProjectReview**](ProjectsAPI.md#getprojectreview) | **Get** /v1/api/projects/{id}/review | Read recorded verification evidence for completed project cycles
[**GetProjectRoadmap**](ProjectsAPI.md#getprojectroadmap) | **Get** /v1/api/projects/{id}/roadmap | Get the project&#39;s roadmap
[**GetProjectRunDiagnostics**](ProjectsAPI.md#getprojectrundiagnostics) | **Get** /v1/api/projects/{id}/diagnostics | Read why a project failed or is waiting
[**GetProjectSequence**](ProjectsAPI.md#getprojectsequence) | **Get** /v1/api/projects/{id}/sequence | Watch a cycle&#39;s narrated Sequence
[**GetProjectStatus**](ProjectsAPI.md#getprojectstatus) | **Get** /v1/api/projects/{id}/status | Read a project&#39;s delivery status
[**GetProjectTeamInsights**](ProjectsAPI.md#getprojectteaminsights) | **Get** /v1/api/projects/{id}/insights | Get a project&#39;s Cloud Machine totals and estimated completion
[**GetProjectTerminalAccess**](ProjectsAPI.md#getprojectterminalaccess) | **Get** /v1/api/projects/{id}/terminal | Open a shell into the project&#39;s Cloud Machine
[**GetProjectUsage**](ProjectsAPI.md#getprojectusage) | **Get** /v1/api/projects/{id}/usage | Get the project&#39;s cost and token roll-up
[**KeepProjectEnvironmentAlive**](ProjectsAPI.md#keepprojectenvironmentalive) | **Post** /v1/api/projects/{id}/environment/keepalive | Tell a running environment it is still in use
[**ListDesigns**](ProjectsAPI.md#listdesigns) | **Get** /v1/api/projects/{projectId}/designs | List native project designs
[**ListDesktops**](ProjectsAPI.md#listdesktops) | **Get** /v1/api/projects/{id}/desktops | List the project&#39;s Desktops
[**ListProjectArtifacts**](ProjectsAPI.md#listprojectartifacts) | **Get** /v1/api/projects/{id}/artifacts | List a project&#39;s stored artifacts
[**ListProjectImageBuilds**](ProjectsAPI.md#listprojectimagebuilds) | **Get** /v1/api/projects/{id}/image-builds | List the project&#39;s Cloud Machine image builds
[**ListProjectInitialProposalComments**](ProjectsAPI.md#listprojectinitialproposalcomments) | **Get** /v1/api/projects/{id}/initial-proposal/comments | List section-anchored proposal comments
[**ListProjectInitialProposalRevisions**](ProjectsAPI.md#listprojectinitialproposalrevisions) | **Get** /v1/api/projects/{id}/initial-proposal/revisions | List proposal revision history
[**ListProjectLinearSessions**](ProjectsAPI.md#listprojectlinearsessions) | **Get** /v1/api/projects/{id}/linear-sessions | List the Linear conversations delegated into this project
[**ListProjectMessages**](ProjectsAPI.md#listprojectmessages) | **Get** /v1/api/projects/{id}/messages | Read the project&#39;s conversation
[**ListProjectRepos**](ProjectsAPI.md#listprojectrepos) | **Get** /v1/api/projects/{id}/repos | List a project&#39;s repositories
[**ListProjects**](ProjectsAPI.md#listprojects) | **Get** /v1/api/projects | List the workspace&#39;s projects
[**MergeProjectReview**](ProjectsAPI.md#mergeprojectreview) | **Post** /v1/api/projects/{id}/review/merge | Merge a reviewed preview pull request at its exact head commit
[**ProjectWorkspaceExec**](ProjectsAPI.md#projectworkspaceexec) | **Post** /v1/api/projects/{id}/workspace/exec | Run a command in the project&#39;s Cloud Machine
[**ProjectWorkspaceFs**](ProjectsAPI.md#projectworkspacefs) | **Post** /v1/api/projects/{id}/workspace/fs | Read or write a file in the project&#39;s Cloud Machine
[**PublishDesignRevision**](ProjectsAPI.md#publishdesignrevision) | **Post** /v1/api/projects/{projectId}/designs/{designId}/revisions | Publish a tested playable prototype
[**PublishProjectInitialProposal**](ProjectsAPI.md#publishprojectinitialproposal) | **Post** /v1/api/projects/{id}/initial-proposal/publish | Publish a branded proposal revision
[**RebuildProjectEnvironment**](ProjectsAPI.md#rebuildprojectenvironment) | **Post** /v1/api/projects/{id}/environment/rebuild | Build the project&#39;s environment again
[**RequestProjectDelivery**](ProjectsAPI.md#requestprojectdelivery) | **Post** /v1/api/projects/{id}/delivery | Open the project&#39;s pull request now
[**ResolveDesignComment**](ProjectsAPI.md#resolvedesigncomment) | **Patch** /v1/api/projects/{projectId}/designs/{designId}/comments/{commentId} | Resolve or reopen a design comment
[**ResolveProjectInitialProposal**](ProjectsAPI.md#resolveprojectinitialproposal) | **Get** /v1/api/projects/initial-proposal-by-id/{proposalId} | Resolve a proposal deep link
[**ResolveProjectInitialProposalComment**](ProjectsAPI.md#resolveprojectinitialproposalcomment) | **Patch** /v1/api/projects/{id}/initial-proposal/comments/{commentId} | Resolve or reopen a proposal comment
[**ResumeProject**](ProjectsAPI.md#resumeproject) | **Post** /v1/api/projects/{id}/resume | Resume a stopped project, or start one that never started
[**ReviseProjectInitialProposal**](ProjectsAPI.md#reviseprojectinitialproposal) | **Post** /v1/api/projects/{id}/initial-proposal/revisions | Request a targeted AI revision
[**SetPrimaryProjectRepo**](ProjectsAPI.md#setprimaryprojectrepo) | **Post** /v1/api/projects/{id}/repos/{repoId}/primary | Make a repository the project&#39;s primary
[**SetProjectMobileTargets**](ProjectsAPI.md#setprojectmobiletargets) | **Put** /v1/api/projects/{id}/mobile/targets | Configure native app targets
[**StartProject**](ProjectsAPI.md#startproject) | **Post** /v1/api/projects/{id}/start | Start the project&#39;s autonomous run
[**StartProjectMobileAgentSession**](ProjectsAPI.md#startprojectmobileagentsession) | **Post** /v1/api/projects/{id}/mobile/agent-sessions | Start a native test device for this agent run
[**StartProjectMobileSession**](ProjectsAPI.md#startprojectmobilesession) | **Post** /v1/api/projects/{id}/mobile/sessions | Start a private app preview
[**StopProject**](ProjectsAPI.md#stopproject) | **Post** /v1/api/projects/{id}/stop | Stop every agent working on the project
[**StopProjectMobileAgentSession**](ProjectsAPI.md#stopprojectmobileagentsession) | **Delete** /v1/api/projects/{id}/mobile/agent-sessions/{sessionId} | Stop this agent run&#39;s native test device
[**StopProjectMobileSession**](ProjectsAPI.md#stopprojectmobilesession) | **Delete** /v1/api/projects/{id}/mobile/sessions/{sessionId} | End your private app preview
[**SuggestProjectStack**](ProjectsAPI.md#suggestprojectstack) | **Post** /v1/api/projects/{id}/suggest-stack | Propose a stack string from the project&#39;s own evidence
[**UnarchiveProject**](ProjectsAPI.md#unarchiveproject) | **Post** /v1/api/projects/{id}/unarchive | Restore an archived project
[**UndoCanvasAgentEdit**](ProjectsAPI.md#undocanvasagentedit) | **Post** /v1/api/projects/{id}/canvas/agent/undo | Undo hlix&#39;s most recent canvas edit
[**UpdateProject**](ProjectsAPI.md#updateproject) | **Patch** /v1/api/projects/{id} | Update a project&#39;s configuration
[**UpdateProjectRepo**](ProjectsAPI.md#updateprojectrepo) | **Patch** /v1/api/projects/{id}/repos/{repoId} | Update a repository&#39;s branch or label
[**WatchProjectDirector**](ProjectsAPI.md#watchprojectdirector) | **Get** /v1/api/projects/{id}/director | Watch the Director Explainer&#39;s evolving video segments



## AddProjectInitialProposalComment

> InitialProposalComment AddProjectInitialProposalComment(ctx, id).CreateInitialProposalComment(createInitialProposalComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Comment on a proposal section

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
	var createInitialProposalComment openapiclient.CreateInitialProposalComment
	if err := json.Unmarshal([]byte("{\"blockId\":\"text\",\"body\":\"text\",\"parentId\":\"text\",\"revisionHash\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"revisionId\":\"text\",\"selectedText\":\"text\"}"), &createInitialProposalComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AddProjectInitialProposalComment(ctx, id).CreateInitialProposalComment(createInitialProposalComment).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAddProjectInitialProposalCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createInitialProposalComment** | [**CreateInitialProposalComment**](CreateInitialProposalComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposalComment**](InitialProposalComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var canvasAgentOps openapiclient.CanvasAgentOps
	if err := json.Unmarshal([]byte("{\"ops\":[{\"element\":{\"h\":1,\"id\":\"text\",\"kind\":\"frame\",\"w\":1,\"x\":1,\"y\":1,\"z\":1},\"op\":\"create\"}]}"), &canvasAgentOps); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ApplyCanvasAgentOps(ctx, id).CanvasAgentOps(canvasAgentOps).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiApplyCanvasAgentOpsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **canvasAgentOps** | [**CanvasAgentOps**](CanvasAgentOps.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CanvasAgentWrite**](CanvasAgentWrite.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var initialProposalApprove openapiclient.InitialProposalApprove
	if err := json.Unmarshal([]byte("{\"contentHash\":\"textxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx\",\"revisionId\":\"text\"}"), &initialProposalApprove); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ApproveProjectInitialProposal(ctx, id).InitialProposalApprove(initialProposalApprove).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiApproveProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalApprove** | [**InitialProposalApprove**](InitialProposalApprove.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**InitialProposal**](InitialProposal.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ArchiveProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiArchiveProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var assign openapiclient.Assign
	if err := json.Unmarshal([]byte("{\"userId\":\"text\"}"), &assign); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AssignProject(ctx, id).Assign(assign).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAssignProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assign** | [**Assign**](Assign.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectRow**](ProjectRow.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var attachGithubRepository openapiclient.AttachGithubRepository
	if err := json.Unmarshal([]byte("{\"githubRepository\":\"acme/site\"}"), &attachGithubRepository); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AttachProjectGithubRepository(ctx, id).AttachGithubRepository(attachGithubRepository).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAttachProjectGithubRepositoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachGithubRepository** | [**AttachGithubRepository**](AttachGithubRepository.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var attachProjectRepo openapiclient.AttachProjectRepo
	if err := json.Unmarshal([]byte("{\"cloneUrl\":\"https://example.com\",\"name\":\"text\",\"owner\":\"text\"}"), &attachProjectRepo); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.AttachProjectRepo(ctx, id).AttachProjectRepo(attachProjectRepo).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAttachProjectRepoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **attachProjectRepo** | [**AttachProjectRepo**](AttachProjectRepo.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	var buildDesign openapiclient.BuildDesign
	if err := json.Unmarshal([]byte("{\"revisionId\":\"text\"}"), &buildDesign); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.BuildDesign(ctx, projectId, designId).BuildDesign(buildDesign).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiBuildDesignRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **buildDesign** | [**BuildDesign**](BuildDesign.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var mobileBuildStart openapiclient.MobileBuildStart
	if err := json.Unmarshal([]byte("{\"targetId\":\"text\"}"), &mobileBuildStart); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.BuildProjectMobileApp(ctx, id).MobileBuildStart(mobileBuildStart).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiBuildProjectMobileAppRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileBuildStart** | [**MobileBuildStart**](MobileBuildStart.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileBuild**](MobileBuild.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ControlDesktop

> DesktopControlResult ControlDesktop(ctx, id, desktopId).DesktopControl(desktopControl).XOrganizationId(xOrganizationId).Execute()

Take control of a Desktop, or give it back

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
	desktopId := "desktopId_example" // string |
	var desktopControl openapiclient.DesktopControl
	if err := json.Unmarshal([]byte("{\"action\":\"take\"}"), &desktopControl); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ControlDesktop(ctx, id, desktopId).DesktopControl(desktopControl).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ControlDesktop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ControlDesktop`: DesktopControlResult
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ControlDesktop`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**desktopId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiControlDesktopRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **desktopControl** | [**DesktopControl**](DesktopControl.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DesktopControlResult**](DesktopControlResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var createDesign openapiclient.CreateDesign
	if err := json.Unmarshal([]byte("{\"intent\":\"design_only\",\"title\":\"text\"}"), &createDesign); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateDesign(ctx, projectId).CreateDesign(createDesign).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateDesignRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createDesign** | [**CreateDesign**](CreateDesign.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Design**](Design.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	var createDesignComment openapiclient.CreateDesignComment
	if err := json.Unmarshal([]byte("{\"body\":\"text\",\"frameId\":\"text\",\"revisionId\":\"text\"}"), &createDesignComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateDesignComment(ctx, projectId, designId).CreateDesignComment(createDesignComment).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateDesignCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **createDesignComment** | [**CreateDesignComment**](CreateDesignComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DesignComment**](DesignComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var createProject openapiclient.CreateProject
	if err := json.Unmarshal([]byte("{}"), &createProject); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateProject(ctx).CreateProject(createProject).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProject** | [**CreateProject**](CreateProject.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	var designDecision openapiclient.DesignDecision
	if err := json.Unmarshal([]byte("{\"decision\":\"approved\",\"revisionId\":\"text\"}"), &designDecision); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DecideDesign(ctx, projectId, designId).DesignDecision(designDecision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDecideDesignRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **designDecision** | [**DesignDecision**](DesignDecision.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DecideProjectInitialProposal

> InitialProposal DecideProjectInitialProposal(ctx, id).InitialProposalClientDecision(initialProposalClientDecision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Record the invited client review agent's optional decision

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
	var initialProposalClientDecision openapiclient.InitialProposalClientDecision
	if err := json.Unmarshal([]byte("{\"comment\":\"text\",\"decision\":\"approved\",\"revisionHash\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"revisionId\":\"text\"}"), &initialProposalClientDecision); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DecideProjectInitialProposal(ctx, id).InitialProposalClientDecision(initialProposalClientDecision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDecideProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalClientDecision** | [**InitialProposalClientDecision**](InitialProposalClientDecision.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposal**](InitialProposal.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.DeleteProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDeleteProjectRequest` request builder.


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


## DetachProjectRepo

> MessageAck DetachProjectRepo(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()

Detach a repository from a project

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
	repoId := "repoId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DetachProjectRepo(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDetachProjectRepoRequest` request builder.


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


## DetectProjectCommands

> ProjectCommandDetection DetectProjectCommands(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()

Re-run command detection without writing anything

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
	body := map[string]interface{}{ ... } // map[string]interface{} |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DetectProjectCommands(ctx, id).Body(body).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDetectProjectCommandsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **body** | **map[string]interface{}** |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectCommandDetection**](ProjectCommandDetection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadDesktopEvidence

> *os.File DownloadDesktopEvidence(ctx, id, desktopId, kind).XOrganizationId(xOrganizationId).Execute()

Download the screen or replay a finished run kept

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
	desktopId := "desktopId_example" // string |
	kind := "kind_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.DownloadDesktopEvidence(ctx, id, desktopId, kind).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.DownloadDesktopEvidence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadDesktopEvidence`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.DownloadDesktopEvidence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**desktopId** | **string** |  |
**kind** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDownloadDesktopEvidenceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var initialProposalManualRevision openapiclient.InitialProposalManualRevision
	if err := json.Unmarshal([]byte("{\"baseHash\":\"textxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx\",\"baseRevisionId\":\"text\",\"blocks\":[{\"body\":\"text\",\"id\":\"text\",\"kind\":\"cover\",\"title\":\"text\"}]}"), &initialProposalManualRevision); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.EditProjectInitialProposal(ctx, id).InitialProposalManualRevision(initialProposalManualRevision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiEditProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalManualRevision** | [**InitialProposalManualRevision**](InitialProposalManualRevision.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**InitialProposalRevision**](InitialProposalRevision.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetCanvasAgentView(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetCanvasAgentViewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CanvasAgentView**](CanvasAgentView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	revision := "revision_example" // string | Exact immutable revision; latest when omitted (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetDesign(ctx, projectId, designId).Revision(revision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDesignRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **revision** | **string** | Exact immutable revision; latest when omitted |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDesktop

> Desktop GetDesktop(ctx, id, desktopId).XOrganizationId(xOrganizationId).Execute()

Read one Desktop and the links to its screen

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
	desktopId := "desktopId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetDesktop(ctx, id, desktopId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetDesktop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDesktop`: Desktop
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetDesktop`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**desktopId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetDesktopRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Desktop**](Desktop.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectDetail**](ProjectDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string | Optional cycle UUID belonging to this project; scopes changed paths and recorded aggregate checks. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectArchitecture(ctx, id).CycleId(cycleId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectArchitectureRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Optional cycle UUID belonging to this project; scopes changed paths and recorded aggregate checks. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ApplicationArchitecture**](ApplicationArchitecture.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	filename := "filename_example" // string |
	download := "download_example" // string | Set to `1` to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with `download=1` in its `url`. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectArtifactUrl(ctx, id, filename).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectArtifactUrlRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Set to &#x60;1&#x60; to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with &#x60;download&#x3D;1&#x60; in its &#x60;url&#x60;. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectBoard(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectBoardRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectBoard**](ProjectBoard.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectBudget(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectBudgetRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectBudget**](ProjectBudget.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectCanvas(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectCanvasRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectCanvas**](ProjectCanvas.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectChatDirectory

> ProjectChatDirectory GetProjectChatDirectory(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the project's conversation tree

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectChatDirectory(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.GetProjectChatDirectory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectChatDirectory`: ProjectChatDirectory
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.GetProjectChatDirectory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectChatDirectoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectChatDirectory**](ProjectChatDirectory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectCycleMetrics(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectCycleMetricsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CycleMetrics**](CycleMetrics.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	clipId := "clipId_example" // string |
	cycleId := "cycleId_example" // string | Selected chapter (optional)
	language := "language_example" // string | en, de or fr (optional)
	download := "download_example" // string | 1 for authenticated video bytes when no signed URL is available (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectDirectorClip(ctx, id, clipId).CycleId(cycleId).Language(language).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectDirectorClipRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **cycleId** | **string** | Selected chapter |
 **language** | **string** | en, de or fr |
 **download** | **string** | 1 for authenticated video bytes when no signed URL is available |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectEnvironment

> ProjectEnvironment GetProjectEnvironment(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read the project's saved Cloud Machine environment

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectEnvironment(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectEnvironmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectEnvironment**](ProjectEnvironment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	revision := "revision_example" // string | Revision number to read; agency only. Clients always receive the published revision. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectInitialProposal(ctx, id).Revision(revision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revision** | **string** | Revision number to read; agency only. Clients always receive the published revision. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	revisionId := "revisionId_example" // string | Revision whose frozen logo should be read; clients must name the published revision. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectInitialProposalLogo(ctx, id).RevisionId(revisionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectInitialProposalLogoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revisionId** | **string** | Revision whose frozen logo should be read; clients must name the published revision. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sessionId := "sessionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileAgentSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectMobileAgentSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileAgentSession**](MobileAgentSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileBuilds(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectMobileBuildsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileBuildsView**](MobileBuildsView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sessionId := "sessionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectMobileSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileSession**](MobileSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectMobileTargets(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectMobileTargetsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileTargetsView**](MobileTargetsView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectReview(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectReviewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectReview**](ProjectReview.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectRoadmap(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectRoadmapRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectRoadmap**](ProjectRoadmap.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectRunDiagnostics

> ProjectDiagnostics GetProjectRunDiagnostics(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read why a project failed or is waiting

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectRunDiagnostics(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectRunDiagnosticsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectDiagnostics**](ProjectDiagnostics.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string | Cycle in this project; defaults to the active or most recent cycle. (optional)
	language := "language_example" // string | Narration language: en (default), de, or fr. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.GetProjectSequence(ctx, id).CycleId(cycleId).Language(language).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectSequenceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Cycle in this project; defaults to the active or most recent cycle. |
 **language** | **string** | Narration language: en (default), de, or fr. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Sequence**](Sequence.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectStatus

> ProjectStatusSummary GetProjectStatus(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a project's delivery status

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectStatus(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectStatusRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectStatusSummary**](ProjectStatusSummary.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectTeamInsights

> ProjectTeamInsights GetProjectTeamInsights(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get a project's Cloud Machine totals and estimated completion

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectTeamInsights(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectTeamInsightsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectTeamInsights**](ProjectTeamInsights.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectTerminalAccess(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectTerminalAccessRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectTerminalAccess**](ProjectTerminalAccess.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.GetProjectUsage(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetProjectUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgentUsageRollup**](AgentUsageRollup.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.KeepProjectEnvironmentAlive(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiKeepProjectEnvironmentAliveRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectEnvironmentKeepAlive**](ProjectEnvironmentKeepAlive.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListDesigns(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDesignsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]Design**](Design.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDesktops

> Desktops ListDesktops(ctx, id).XOrganizationId(xOrganizationId).Execute()

List the project's Desktops

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
	resp, r, err := apiClient.ProjectsAPI.ListDesktops(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListDesktops``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDesktops`: Desktops
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListDesktops`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListDesktopsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Desktops**](Desktops.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectArtifacts(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectArtifactsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]StoredArtifact**](StoredArtifact.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectImageBuilds(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectImageBuildsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ProjectImageBuild**](ProjectImageBuild.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectInitialProposalComments(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectInitialProposalCommentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposalCommentsResponse**](InitialProposalCommentsResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectInitialProposalRevisions(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectInitialProposalRevisionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposalHistoryResponse**](InitialProposalHistoryResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectLinearSessions(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectLinearSessionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectLinearSessions**](ProjectLinearSessions.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	agentId := "agentId_example" // string | Read this agent's project thread instead of the project manager's. (optional)
	limit := "limit_example" // string | How many stored turns one page holds, 1 to 200. Default 50. (optional)
	before := "before_example" // string | The `nextCursor` of the page you have: read the turns older than it. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjectMessages(ctx, id).AgentId(agentId).Limit(limit).Before(before).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectMessagesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentId** | **string** | Read this agent&#39;s project thread instead of the project manager&#39;s. |
 **limit** | **string** | How many stored turns one page holds, 1 to 200. Default 50. |
 **before** | **string** | The &#x60;nextCursor&#x60; of the page you have: read the turns older than it. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**WireMessagePage**](WireMessagePage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ListProjectRepos(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectReposRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	includeArchived := "includeArchived_example" // string | Set to `true` to include archived projects. They are hidden by default. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjects(ctx).IncludeArchived(includeArchived).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeArchived** | **string** | Set to &#x60;true&#x60; to include archived projects. They are hidden by default. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]ProjectSummary**](ProjectSummary.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var mergeProjectReview openapiclient.MergeProjectReview
	if err := json.Unmarshal([]byte("{\"headSha\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"repoId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &mergeProjectReview); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.MergeProjectReview(ctx, id).MergeProjectReview(mergeProjectReview).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiMergeProjectReviewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mergeProjectReview** | [**MergeProjectReview**](MergeProjectReview.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var projectWorkspaceExec openapiclient.ProjectWorkspaceExec
	if err := json.Unmarshal([]byte("{\"command\":\"text\"}"), &projectWorkspaceExec); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ProjectWorkspaceExec(ctx, id).ProjectWorkspaceExec(projectWorkspaceExec).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiProjectWorkspaceExecRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectWorkspaceExec** | [**ProjectWorkspaceExec**](ProjectWorkspaceExec.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceExecResult**](WorkspaceExecResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var projectWorkspaceFs openapiclient.ProjectWorkspaceFs
	if err := json.Unmarshal([]byte("{\"op\":\"read\",\"path\":\"text\"}"), &projectWorkspaceFs); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ProjectWorkspaceFs(ctx, id).ProjectWorkspaceFs(projectWorkspaceFs).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiProjectWorkspaceFsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectWorkspaceFs** | [**ProjectWorkspaceFs**](ProjectWorkspaceFs.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**WorkspaceFsResult**](WorkspaceFsResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	var publishDesignRevision openapiclient.PublishDesignRevision
	if err := json.Unmarshal([]byte("{\"context\":{},\"evidence\":[{\"flowId\":\"text\",\"note\":\"text\",\"result\":\"passed\"}],\"expectedRevisionId\":\"text\",\"flows\":[{\"entryFrameId\":\"text\",\"frameIds\":[\"text\"],\"id\":\"text\",\"name\":\"text\"}],\"frames\":[{\"height\":240,\"id\":\"text\",\"name\":\"text\",\"route\":\"#1f2937\",\"width\":240}],\"html\":\"text\"}"), &publishDesignRevision); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.PublishDesignRevision(ctx, projectId, designId).PublishDesignRevision(publishDesignRevision).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPublishDesignRevisionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **publishDesignRevision** | [**PublishDesignRevision**](PublishDesignRevision.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DesignDetail**](DesignDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var initialProposalPublish openapiclient.InitialProposalPublish
	if err := json.Unmarshal([]byte("{}"), &initialProposalPublish); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.PublishProjectInitialProposal(ctx, id).InitialProposalPublish(initialProposalPublish).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPublishProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalPublish** | [**InitialProposalPublish**](InitialProposalPublish.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RebuildProjectEnvironment

> ProjectEnvironmentRebuild RebuildProjectEnvironment(ctx, id).XOrganizationId(xOrganizationId).Execute()

Build the project's environment again

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
	resp, r, err := apiClient.ProjectsAPI.RebuildProjectEnvironment(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.RebuildProjectEnvironment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RebuildProjectEnvironment`: ProjectEnvironmentRebuild
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.RebuildProjectEnvironment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRebuildProjectEnvironmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectEnvironmentRebuild**](ProjectEnvironmentRebuild.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestProjectDelivery

> ProjectDelivery RequestProjectDelivery(ctx, id).XOrganizationId(xOrganizationId).Execute()

Open the project's pull request now

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
	resp, r, err := apiClient.ProjectsAPI.RequestProjectDelivery(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRequestProjectDeliveryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectDelivery**](ProjectDelivery.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	designId := "designId_example" // string |
	commentId := "commentId_example" // string |
	var resolveDesignComment openapiclient.ResolveDesignComment
	if err := json.Unmarshal([]byte("{\"resolved\":true}"), &resolveDesignComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveDesignComment(ctx, projectId, designId, commentId).ResolveDesignComment(resolveDesignComment).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResolveDesignCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **resolveDesignComment** | [**ResolveDesignComment**](ResolveDesignComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DesignComment**](DesignComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	proposalId := "proposalId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveProjectInitialProposal(ctx, proposalId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResolveProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**InitialProposalDetailResponse**](InitialProposalDetailResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	commentId := "commentId_example" // string |
	var initialProposalResolveComment openapiclient.InitialProposalResolveComment
	if err := json.Unmarshal([]byte("{\"resolved\":true}"), &initialProposalResolveComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ResolveProjectInitialProposalComment(ctx, id, commentId).InitialProposalResolveComment(initialProposalResolveComment).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResolveProjectInitialProposalCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **initialProposalResolveComment** | [**InitialProposalResolveComment**](InitialProposalResolveComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**InitialProposalComment**](InitialProposalComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.ResumeProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResumeProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectResumed**](ProjectResumed.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var initialProposalRevisionTarget openapiclient.InitialProposalRevisionTarget
	if err := json.Unmarshal([]byte("{\"baseHash\":\"textxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx\",\"baseRevisionId\":\"text\",\"instruction\":\"text\"}"), &initialProposalRevisionTarget); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ReviseProjectInitialProposal(ctx, id).InitialProposalRevisionTarget(initialProposalRevisionTarget).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiReviseProjectInitialProposalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initialProposalRevisionTarget** | [**InitialProposalRevisionTarget**](InitialProposalRevisionTarget.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**InitialProposalRevision**](InitialProposalRevision.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	repoId := "repoId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SetPrimaryProjectRepo(ctx, id, repoId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetPrimaryProjectRepoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var mobileTargetsInput openapiclient.MobileTargetsInput
	if err := json.Unmarshal([]byte("{\"targets\":[{\"buildCommand\":\"text\",\"bundleId\":\"app.example.com\",\"framework\":\"native\",\"id\":\"text\",\"name\":\"text\",\"outputPath\":\"text\",\"path\":\"text\",\"platform\":\"ios\",\"repoId\":\"text\"}]}"), &mobileTargetsInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.SetProjectMobileTargets(ctx, id).MobileTargetsInput(mobileTargetsInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetProjectMobileTargetsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileTargetsInput** | [**MobileTargetsInput**](MobileTargetsInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileTargetsSaved**](MobileTargetsSaved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var startProject openapiclient.StartProject
	if err := json.Unmarshal([]byte("{\"brief\":\"text\"}"), &startProject); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProject(ctx, id).StartProject(startProject).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStartProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startProject** | [**StartProject**](StartProject.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectStarted**](ProjectStarted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProjectMobileAgentSession

> MobileAgentSession StartProjectMobileAgentSession(ctx, id).MobileAgentSessionStart(mobileAgentSessionStart).XOrganizationId(xOrganizationId).Execute()

Start a native test device for this agent run

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
	var mobileAgentSessionStart openapiclient.MobileAgentSessionStart
	if err := json.Unmarshal([]byte("{\"buildId\":\"123e4567-e89b-42d3-a456-426614174000\",\"requestId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &mobileAgentSessionStart); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProjectMobileAgentSession(ctx, id).MobileAgentSessionStart(mobileAgentSessionStart).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStartProjectMobileAgentSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileAgentSessionStart** | [**MobileAgentSessionStart**](MobileAgentSessionStart.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileAgentSession**](MobileAgentSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var mobileSessionStart openapiclient.MobileSessionStart
	if err := json.Unmarshal([]byte("{\"buildId\":\"123e4567-e89b-42d3-a456-426614174000\",\"tabId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &mobileSessionStart); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StartProjectMobileSession(ctx, id).MobileSessionStart(mobileSessionStart).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStartProjectMobileSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mobileSessionStart** | [**MobileSessionStart**](MobileSessionStart.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileSession**](MobileSession.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.StopProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStopProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectStopped**](ProjectStopped.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sessionId := "sessionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StopProjectMobileAgentSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStopProjectMobileAgentSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileStopped**](MobileStopped.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	sessionId := "sessionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.StopProjectMobileSession(ctx, id, sessionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStopProjectMobileSessionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MobileStopped**](MobileStopped.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.SuggestProjectStack(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSuggestProjectStackRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectStackSuggestion**](ProjectStackSuggestion.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.UnarchiveProject(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUnarchiveProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ProjectsAPI.UndoCanvasAgentEdit(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUndoCanvasAgentEditRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CanvasAgentUndo**](CanvasAgentUndo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var updateProject openapiclient.UpdateProject
	if err := json.Unmarshal([]byte("{}"), &updateProject); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UpdateProject(ctx, id).UpdateProject(updateProject).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateProject** | [**UpdateProject**](UpdateProject.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Project**](Project.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	repoId := "repoId_example" // string |
	var updateProjectRepo openapiclient.UpdateProjectRepo
	if err := json.Unmarshal([]byte("{}"), &updateProjectRepo); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.UpdateProjectRepo(ctx, id, repoId).UpdateProjectRepo(updateProjectRepo).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateProjectRepoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateProjectRepo** | [**UpdateProjectRepo**](UpdateProjectRepo.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectRepo**](ProjectRepo.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string | Selected chapter (optional)
	language := "language_example" // string | en, de or fr (optional)
	retry := "retry_example" // string | 1 to retry a failed render after automatic retries are exhausted (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.WatchProjectDirector(ctx, id).CycleId(cycleId).Language(language).Retry(retry).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiWatchProjectDirectorRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleId** | **string** | Selected chapter |
 **language** | **string** | en, de or fr |
 **retry** | **string** | 1 to retry a failed render after automatic retries are exhausted |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DirectorState**](DirectorState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

