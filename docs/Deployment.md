# Deployment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuildId** | **NullableString** |  |
**CreatedAt** | **string** |  |
**CycleId** | **NullableString** |  |
**ErrorMessage** | **NullableString** |  |
**ExpiresAt** | **NullableString** |  |
**GitBranch** | **NullableString** |  |
**GitSha** | **NullableString** |  |
**Id** | **string** |  |
**ImageUri** | **NullableString** |  |
**Kind** | **string** |  |
**LastAccessedAt** | **NullableString** |  |
**OrganizationId** | **string** |  |
**ProjectId** | **string** |  |
**Region** | **string** |  |
**Revision** | **NullableString** |  |
**ServiceName** | **string** |  |
**Slug** | **string** |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |
**Url** | **NullableString** |  |

## Methods

### NewDeployment

`func NewDeployment(buildId NullableString, createdAt string, cycleId NullableString, errorMessage NullableString, expiresAt NullableString, gitBranch NullableString, gitSha NullableString, id string, imageUri NullableString, kind string, lastAccessedAt NullableString, organizationId string, projectId string, region string, revision NullableString, serviceName string, slug string, status string, updatedAt string, url NullableString, ) *Deployment`

NewDeployment instantiates a new Deployment object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeploymentWithDefaults

`func NewDeploymentWithDefaults() *Deployment`

NewDeploymentWithDefaults instantiates a new Deployment object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBuildId

`func (o *Deployment) GetBuildId() string`

GetBuildId returns the BuildId field if non-nil, zero value otherwise.

### GetBuildIdOk

`func (o *Deployment) GetBuildIdOk() (*string, bool)`

GetBuildIdOk returns a tuple with the BuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildId

`func (o *Deployment) SetBuildId(v string)`

SetBuildId sets BuildId field to given value.


### SetBuildIdNil

`func (o *Deployment) SetBuildIdNil(b bool)`

 SetBuildIdNil sets the value for BuildId to be an explicit nil

### UnsetBuildId
`func (o *Deployment) UnsetBuildId()`

UnsetBuildId ensures that no value is present for BuildId, not even an explicit nil
### GetCreatedAt

`func (o *Deployment) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Deployment) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Deployment) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *Deployment) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *Deployment) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *Deployment) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *Deployment) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *Deployment) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetErrorMessage

`func (o *Deployment) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *Deployment) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *Deployment) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.


### SetErrorMessageNil

`func (o *Deployment) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *Deployment) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetExpiresAt

`func (o *Deployment) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Deployment) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Deployment) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *Deployment) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *Deployment) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetGitBranch

`func (o *Deployment) GetGitBranch() string`

GetGitBranch returns the GitBranch field if non-nil, zero value otherwise.

### GetGitBranchOk

`func (o *Deployment) GetGitBranchOk() (*string, bool)`

GetGitBranchOk returns a tuple with the GitBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitBranch

`func (o *Deployment) SetGitBranch(v string)`

SetGitBranch sets GitBranch field to given value.


### SetGitBranchNil

`func (o *Deployment) SetGitBranchNil(b bool)`

 SetGitBranchNil sets the value for GitBranch to be an explicit nil

### UnsetGitBranch
`func (o *Deployment) UnsetGitBranch()`

UnsetGitBranch ensures that no value is present for GitBranch, not even an explicit nil
### GetGitSha

`func (o *Deployment) GetGitSha() string`

GetGitSha returns the GitSha field if non-nil, zero value otherwise.

### GetGitShaOk

`func (o *Deployment) GetGitShaOk() (*string, bool)`

GetGitShaOk returns a tuple with the GitSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitSha

`func (o *Deployment) SetGitSha(v string)`

SetGitSha sets GitSha field to given value.


### SetGitShaNil

`func (o *Deployment) SetGitShaNil(b bool)`

 SetGitShaNil sets the value for GitSha to be an explicit nil

### UnsetGitSha
`func (o *Deployment) UnsetGitSha()`

UnsetGitSha ensures that no value is present for GitSha, not even an explicit nil
### GetId

`func (o *Deployment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Deployment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Deployment) SetId(v string)`

SetId sets Id field to given value.


### GetImageUri

`func (o *Deployment) GetImageUri() string`

GetImageUri returns the ImageUri field if non-nil, zero value otherwise.

### GetImageUriOk

`func (o *Deployment) GetImageUriOk() (*string, bool)`

GetImageUriOk returns a tuple with the ImageUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUri

`func (o *Deployment) SetImageUri(v string)`

SetImageUri sets ImageUri field to given value.


### SetImageUriNil

`func (o *Deployment) SetImageUriNil(b bool)`

 SetImageUriNil sets the value for ImageUri to be an explicit nil

### UnsetImageUri
`func (o *Deployment) UnsetImageUri()`

UnsetImageUri ensures that no value is present for ImageUri, not even an explicit nil
### GetKind

`func (o *Deployment) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Deployment) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Deployment) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLastAccessedAt

`func (o *Deployment) GetLastAccessedAt() string`

GetLastAccessedAt returns the LastAccessedAt field if non-nil, zero value otherwise.

### GetLastAccessedAtOk

`func (o *Deployment) GetLastAccessedAtOk() (*string, bool)`

GetLastAccessedAtOk returns a tuple with the LastAccessedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAccessedAt

`func (o *Deployment) SetLastAccessedAt(v string)`

SetLastAccessedAt sets LastAccessedAt field to given value.


### SetLastAccessedAtNil

`func (o *Deployment) SetLastAccessedAtNil(b bool)`

 SetLastAccessedAtNil sets the value for LastAccessedAt to be an explicit nil

### UnsetLastAccessedAt
`func (o *Deployment) UnsetLastAccessedAt()`

UnsetLastAccessedAt ensures that no value is present for LastAccessedAt, not even an explicit nil
### GetOrganizationId

`func (o *Deployment) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Deployment) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Deployment) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *Deployment) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Deployment) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Deployment) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRegion

`func (o *Deployment) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *Deployment) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *Deployment) SetRegion(v string)`

SetRegion sets Region field to given value.


### GetRevision

`func (o *Deployment) GetRevision() string`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *Deployment) GetRevisionOk() (*string, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *Deployment) SetRevision(v string)`

SetRevision sets Revision field to given value.


### SetRevisionNil

`func (o *Deployment) SetRevisionNil(b bool)`

 SetRevisionNil sets the value for Revision to be an explicit nil

### UnsetRevision
`func (o *Deployment) UnsetRevision()`

UnsetRevision ensures that no value is present for Revision, not even an explicit nil
### GetServiceName

`func (o *Deployment) GetServiceName() string`

GetServiceName returns the ServiceName field if non-nil, zero value otherwise.

### GetServiceNameOk

`func (o *Deployment) GetServiceNameOk() (*string, bool)`

GetServiceNameOk returns a tuple with the ServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceName

`func (o *Deployment) SetServiceName(v string)`

SetServiceName sets ServiceName field to given value.


### GetSlug

`func (o *Deployment) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *Deployment) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *Deployment) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetStatus

`func (o *Deployment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Deployment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Deployment) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *Deployment) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Deployment) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Deployment) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUrl

`func (o *Deployment) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Deployment) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Deployment) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *Deployment) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *Deployment) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


