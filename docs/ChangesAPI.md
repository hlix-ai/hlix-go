# ChangesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CommitProjectFileEdits**](ChangesAPI.md#commitprojectfileedits) | **Post** /v1/api/projects/{id}/files/commit | Commit hand edits to an edit branch
[**GetProjectChangeFile**](ChangesAPI.md#getprojectchangefile) | **Get** /v1/api/projects/{id}/changes/file | Get one changed file&#39;s unified diff
[**GetProjectChanges**](ChangesAPI.md#getprojectchanges) | **Get** /v1/api/projects/{id}/changes | Get the project&#39;s changed files and checkpoint commits
[**GetProjectFileContent**](ChangesAPI.md#getprojectfilecontent) | **Get** /v1/api/projects/{id}/files/content | Get one file of the project&#39;s head tree
[**ListProjectBranches**](ChangesAPI.md#listprojectbranches) | **Get** /v1/api/projects/{id}/branches | List the branches of the project the Files surface can read
[**ListProjectFiles**](ChangesAPI.md#listprojectfiles) | **Get** /v1/api/projects/{id}/files | List every path in the project&#39;s head tree
[**MergeProjectEditBranch**](ChangesAPI.md#mergeprojecteditbranch) | **Post** /v1/api/projects/{id}/branches/merge | Merge an edit branch back into the branch it was cut from
[**SaveProjectWorkingFile**](ChangesAPI.md#saveprojectworkingfile) | **Put** /v1/api/projects/{id}/files/working | Save one file into a running cycle&#39;s Cloud Machine
[**StartProjectEditBranch**](ChangesAPI.md#startprojecteditbranch) | **Post** /v1/api/projects/{id}/branches | Cut a branch to edit files by hand



## CommitProjectFileEdits

> CommitEditsResult CommitProjectFileEdits(ctx, id).CommitEdits(commitEdits).XOrganizationId(xOrganizationId).Execute()

Commit hand edits to an edit branch

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
	var commitEdits openapiclient.CommitEdits
	if err := json.Unmarshal([]byte("{\"files\":[{\"content\":\"text\",\"path\":\"text\"}],\"headSha\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"message\":\"text\",\"ref\":\"text\"}"), &commitEdits); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.CommitProjectFileEdits(ctx, id).CommitEdits(commitEdits).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.CommitProjectFileEdits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CommitProjectFileEdits`: CommitEditsResult
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.CommitProjectFileEdits`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCommitProjectFileEditsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **commitEdits** | [**CommitEdits**](CommitEdits.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CommitEditsResult**](CommitEditsResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectChangeFile

> ChangeFilePatch GetProjectChangeFile(ctx, id).Path(path).Repo(repo).Since(since).CycleId(cycleId).Ref(ref).XOrganizationId(xOrganizationId).Execute()

Get one changed file's unified diff

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
	path := "path_example" // string | The repository-relative file path.
	repo := "repo_example" // string | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). (optional)
	since := "since_example" // string | A 40-character commit sha to compare against instead of the default branch. (optional)
	cycleId := "cycleId_example" // string | Read from this cycle's running build agent Cloud Machine instead of the repository. (optional)
	ref := "ref_example" // string | Read this branch instead of the project's preview branch. Only a branch `GET /v1/api/projects/:id/branches` lists is accepted; any other name, another project's branch in a shared repository included, is a 404. Naming a branch is agency-only. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.GetProjectChangeFile(ctx, id).Path(path).Repo(repo).Since(since).CycleId(cycleId).Ref(ref).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.GetProjectChangeFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectChangeFile`: ChangeFilePatch
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.GetProjectChangeFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectChangeFileRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **path** | **string** | The repository-relative file path. |
 **repo** | **string** | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). |
 **since** | **string** | A 40-character commit sha to compare against instead of the default branch. |
 **cycleId** | **string** | Read from this cycle&#39;s running build agent Cloud Machine instead of the repository. |
 **ref** | **string** | Read this branch instead of the project&#39;s preview branch. Only a branch &#x60;GET /v1/api/projects/:id/branches&#x60; lists is accepted; any other name, another project&#39;s branch in a shared repository included, is a 404. Naming a branch is agency-only. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ChangeFilePatch**](ChangeFilePatch.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectChanges

> ProjectChanges GetProjectChanges(ctx, id).Repo(repo).Since(since).Ref(ref).Page(page).XOrganizationId(xOrganizationId).Execute()

Get the project's changed files and checkpoint commits

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
	repo := "repo_example" // string | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). (optional)
	since := "since_example" // string | A 40-character commit sha to compare against instead of the default branch. (optional)
	ref := "ref_example" // string | Read this branch instead of the project's preview branch. Only a branch `GET /v1/api/projects/:id/branches` lists is accepted; any other name, another project's branch in a shared repository included, is a 404. Naming a branch is agency-only. (optional)
	page := "page_example" // string | Which page of an HLIX Repos repository's change list, from 0 (the default). Each page lists up to 500 files in path order; the response's `nextPage` names the next one. Ignored for GitHub repositories, whose list is not paged. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.GetProjectChanges(ctx, id).Repo(repo).Since(since).Ref(ref).Page(page).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.GetProjectChanges``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectChanges`: ProjectChanges
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.GetProjectChanges`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectChangesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repo** | **string** | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). |
 **since** | **string** | A 40-character commit sha to compare against instead of the default branch. |
 **ref** | **string** | Read this branch instead of the project&#39;s preview branch. Only a branch &#x60;GET /v1/api/projects/:id/branches&#x60; lists is accepted; any other name, another project&#39;s branch in a shared repository included, is a 404. Naming a branch is agency-only. |
 **page** | **string** | Which page of an HLIX Repos repository&#39;s change list, from 0 (the default). Each page lists up to 500 files in path order; the response&#39;s &#x60;nextPage&#x60; names the next one. Ignored for GitHub repositories, whose list is not paged. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectChanges**](ProjectChanges.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectFileContent

> FileContent GetProjectFileContent(ctx, id).Path(path).Repo(repo).CycleId(cycleId).Ref(ref).At(at).XOrganizationId(xOrganizationId).Execute()

Get one file of the project's head tree

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
	path := "path_example" // string | The repository-relative file path.
	repo := "repo_example" // string | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). (optional)
	cycleId := "cycleId_example" // string | Read from this cycle's running build agent Cloud Machine instead of the repository. (optional)
	ref := "ref_example" // string | Read this branch instead of the project's preview branch. Only a branch `GET /v1/api/projects/:id/branches` lists is accepted; any other name, another project's branch in a shared repository included, is a 404. Naming a branch is agency-only. (optional)
	at := "at_example" // string | Read the file at this 40-character commit (the one the tree was listed at) instead of the branch head, so a push between listing and reading cannot change the answer. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.GetProjectFileContent(ctx, id).Path(path).Repo(repo).CycleId(cycleId).Ref(ref).At(at).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.GetProjectFileContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectFileContent`: FileContent
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.GetProjectFileContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectFileContentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **path** | **string** | The repository-relative file path. |
 **repo** | **string** | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). |
 **cycleId** | **string** | Read from this cycle&#39;s running build agent Cloud Machine instead of the repository. |
 **ref** | **string** | Read this branch instead of the project&#39;s preview branch. Only a branch &#x60;GET /v1/api/projects/:id/branches&#x60; lists is accepted; any other name, another project&#39;s branch in a shared repository included, is a 404. Naming a branch is agency-only. |
 **at** | **string** | Read the file at this 40-character commit (the one the tree was listed at) instead of the branch head, so a push between listing and reading cannot change the answer. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**FileContent**](FileContent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectBranches

> ProjectBranches ListProjectBranches(ctx, id).Repo(repo).XOrganizationId(xOrganizationId).Execute()

List the branches of the project the Files surface can read

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
	repo := "repo_example" // string | Which repository of a multi-repo project. Omitted, the primary one. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.ListProjectBranches(ctx, id).Repo(repo).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.ListProjectBranches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectBranches`: ProjectBranches
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.ListProjectBranches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectBranchesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repo** | **string** | Which repository of a multi-repo project. Omitted, the primary one. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectBranches**](ProjectBranches.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectFiles

> TreeListing ListProjectFiles(ctx, id).Repo(repo).Ref(ref).XOrganizationId(xOrganizationId).Execute()

List every path in the project's head tree

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
	repo := "repo_example" // string | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). (optional)
	ref := "ref_example" // string | Read this branch instead of the project's preview branch. Only a branch `GET /v1/api/projects/:id/branches` lists is accepted; any other name, another project's branch in a shared repository included, is a 404. Naming a branch is agency-only. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.ListProjectFiles(ctx, id).Repo(repo).Ref(ref).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.ListProjectFiles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectFiles`: TreeListing
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.ListProjectFiles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListProjectFilesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repo** | **string** | Which repository of a multi-repo project. Omitted, every repository (the primary one for a single-file read). |
 **ref** | **string** | Read this branch instead of the project&#39;s preview branch. Only a branch &#x60;GET /v1/api/projects/:id/branches&#x60; lists is accepted; any other name, another project&#39;s branch in a shared repository included, is a 404. Naming a branch is agency-only. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**TreeListing**](TreeListing.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MergeProjectEditBranch

> MergeEditBranchResult MergeProjectEditBranch(ctx, id).MergeEditBranch(mergeEditBranch).XOrganizationId(xOrganizationId).Execute()

Merge an edit branch back into the branch it was cut from

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
	var mergeEditBranch openapiclient.MergeEditBranch
	if err := json.Unmarshal([]byte("{\"ref\":\"text\"}"), &mergeEditBranch); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.MergeProjectEditBranch(ctx, id).MergeEditBranch(mergeEditBranch).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.MergeProjectEditBranch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MergeProjectEditBranch`: MergeEditBranchResult
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.MergeProjectEditBranch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiMergeProjectEditBranchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mergeEditBranch** | [**MergeEditBranch**](MergeEditBranch.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MergeEditBranchResult**](MergeEditBranchResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveProjectWorkingFile

> SaveWorkingFileResult SaveProjectWorkingFile(ctx, id).WriteWorkingFile(writeWorkingFile).XOrganizationId(xOrganizationId).Execute()

Save one file into a running cycle's Cloud Machine

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
	var writeWorkingFile openapiclient.WriteWorkingFile
	if err := json.Unmarshal([]byte("{\"base\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"content\":\"text\",\"cycleId\":\"text\",\"path\":\"text\"}"), &writeWorkingFile); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.SaveProjectWorkingFile(ctx, id).WriteWorkingFile(writeWorkingFile).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.SaveProjectWorkingFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveProjectWorkingFile`: SaveWorkingFileResult
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.SaveProjectWorkingFile`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSaveProjectWorkingFileRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **writeWorkingFile** | [**WriteWorkingFile**](WriteWorkingFile.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SaveWorkingFileResult**](SaveWorkingFileResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartProjectEditBranch

> EditBranch StartProjectEditBranch(ctx, id).StartEditBranch(startEditBranch).XOrganizationId(xOrganizationId).Execute()

Cut a branch to edit files by hand

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
	var startEditBranch openapiclient.StartEditBranch
	if err := json.Unmarshal([]byte("{\"from\":\"text\",\"fromSha\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\"}"), &startEditBranch); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChangesAPI.StartProjectEditBranch(ctx, id).StartEditBranch(startEditBranch).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChangesAPI.StartProjectEditBranch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartProjectEditBranch`: EditBranch
	fmt.Fprintf(os.Stdout, "Response from `ChangesAPI.StartProjectEditBranch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiStartProjectEditBranchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startEditBranch** | [**StartEditBranch**](StartEditBranch.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**EditBranch**](EditBranch.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

