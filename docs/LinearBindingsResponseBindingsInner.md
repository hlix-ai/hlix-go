# LinearBindingsResponseBindingsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**Id** | **string** |  | 
**InstallationId** | **string** |  | 
**LabelId** | **NullableString** |  | 
**LabelName** | **NullableString** |  | 
**LastError** | **NullableString** |  | 
**LastSyncedAt** | **NullableString** |  | 
**LastWebhookAt** | **NullableString** |  | 
**LinearProjectId** | **NullableString** |  | 
**LinearProjectName** | **NullableString** |  | 
**LinearWorkspaceName** | **string** |  | 
**Mode** | **string** |  | 
**ProjectId** | **string** |  | 
**ProjectName** | **string** |  | 
**TeamId** | **string** |  | 
**TeamKey** | **string** |  | 
**TeamName** | **string** |  | 

## Methods

### NewLinearBindingsResponseBindingsInner

`func NewLinearBindingsResponseBindingsInner(enabled bool, id string, installationId string, labelId NullableString, labelName NullableString, lastError NullableString, lastSyncedAt NullableString, lastWebhookAt NullableString, linearProjectId NullableString, linearProjectName NullableString, linearWorkspaceName string, mode string, projectId string, projectName string, teamId string, teamKey string, teamName string, ) *LinearBindingsResponseBindingsInner`

NewLinearBindingsResponseBindingsInner instantiates a new LinearBindingsResponseBindingsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinearBindingsResponseBindingsInnerWithDefaults

`func NewLinearBindingsResponseBindingsInnerWithDefaults() *LinearBindingsResponseBindingsInner`

NewLinearBindingsResponseBindingsInnerWithDefaults instantiates a new LinearBindingsResponseBindingsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *LinearBindingsResponseBindingsInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *LinearBindingsResponseBindingsInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *LinearBindingsResponseBindingsInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetId

`func (o *LinearBindingsResponseBindingsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LinearBindingsResponseBindingsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LinearBindingsResponseBindingsInner) SetId(v string)`

SetId sets Id field to given value.


### GetInstallationId

`func (o *LinearBindingsResponseBindingsInner) GetInstallationId() string`

GetInstallationId returns the InstallationId field if non-nil, zero value otherwise.

### GetInstallationIdOk

`func (o *LinearBindingsResponseBindingsInner) GetInstallationIdOk() (*string, bool)`

GetInstallationIdOk returns a tuple with the InstallationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationId

`func (o *LinearBindingsResponseBindingsInner) SetInstallationId(v string)`

SetInstallationId sets InstallationId field to given value.


### GetLabelId

`func (o *LinearBindingsResponseBindingsInner) GetLabelId() string`

GetLabelId returns the LabelId field if non-nil, zero value otherwise.

### GetLabelIdOk

`func (o *LinearBindingsResponseBindingsInner) GetLabelIdOk() (*string, bool)`

GetLabelIdOk returns a tuple with the LabelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelId

`func (o *LinearBindingsResponseBindingsInner) SetLabelId(v string)`

SetLabelId sets LabelId field to given value.


### SetLabelIdNil

`func (o *LinearBindingsResponseBindingsInner) SetLabelIdNil(b bool)`

 SetLabelIdNil sets the value for LabelId to be an explicit nil

### UnsetLabelId
`func (o *LinearBindingsResponseBindingsInner) UnsetLabelId()`

UnsetLabelId ensures that no value is present for LabelId, not even an explicit nil
### GetLabelName

`func (o *LinearBindingsResponseBindingsInner) GetLabelName() string`

GetLabelName returns the LabelName field if non-nil, zero value otherwise.

### GetLabelNameOk

`func (o *LinearBindingsResponseBindingsInner) GetLabelNameOk() (*string, bool)`

GetLabelNameOk returns a tuple with the LabelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelName

`func (o *LinearBindingsResponseBindingsInner) SetLabelName(v string)`

SetLabelName sets LabelName field to given value.


### SetLabelNameNil

`func (o *LinearBindingsResponseBindingsInner) SetLabelNameNil(b bool)`

 SetLabelNameNil sets the value for LabelName to be an explicit nil

### UnsetLabelName
`func (o *LinearBindingsResponseBindingsInner) UnsetLabelName()`

UnsetLabelName ensures that no value is present for LabelName, not even an explicit nil
### GetLastError

`func (o *LinearBindingsResponseBindingsInner) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *LinearBindingsResponseBindingsInner) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *LinearBindingsResponseBindingsInner) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *LinearBindingsResponseBindingsInner) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *LinearBindingsResponseBindingsInner) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetLastSyncedAt

`func (o *LinearBindingsResponseBindingsInner) GetLastSyncedAt() string`

GetLastSyncedAt returns the LastSyncedAt field if non-nil, zero value otherwise.

### GetLastSyncedAtOk

`func (o *LinearBindingsResponseBindingsInner) GetLastSyncedAtOk() (*string, bool)`

GetLastSyncedAtOk returns a tuple with the LastSyncedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSyncedAt

`func (o *LinearBindingsResponseBindingsInner) SetLastSyncedAt(v string)`

SetLastSyncedAt sets LastSyncedAt field to given value.


### SetLastSyncedAtNil

`func (o *LinearBindingsResponseBindingsInner) SetLastSyncedAtNil(b bool)`

 SetLastSyncedAtNil sets the value for LastSyncedAt to be an explicit nil

### UnsetLastSyncedAt
`func (o *LinearBindingsResponseBindingsInner) UnsetLastSyncedAt()`

UnsetLastSyncedAt ensures that no value is present for LastSyncedAt, not even an explicit nil
### GetLastWebhookAt

`func (o *LinearBindingsResponseBindingsInner) GetLastWebhookAt() string`

GetLastWebhookAt returns the LastWebhookAt field if non-nil, zero value otherwise.

### GetLastWebhookAtOk

`func (o *LinearBindingsResponseBindingsInner) GetLastWebhookAtOk() (*string, bool)`

GetLastWebhookAtOk returns a tuple with the LastWebhookAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastWebhookAt

`func (o *LinearBindingsResponseBindingsInner) SetLastWebhookAt(v string)`

SetLastWebhookAt sets LastWebhookAt field to given value.


### SetLastWebhookAtNil

`func (o *LinearBindingsResponseBindingsInner) SetLastWebhookAtNil(b bool)`

 SetLastWebhookAtNil sets the value for LastWebhookAt to be an explicit nil

### UnsetLastWebhookAt
`func (o *LinearBindingsResponseBindingsInner) UnsetLastWebhookAt()`

UnsetLastWebhookAt ensures that no value is present for LastWebhookAt, not even an explicit nil
### GetLinearProjectId

`func (o *LinearBindingsResponseBindingsInner) GetLinearProjectId() string`

GetLinearProjectId returns the LinearProjectId field if non-nil, zero value otherwise.

### GetLinearProjectIdOk

`func (o *LinearBindingsResponseBindingsInner) GetLinearProjectIdOk() (*string, bool)`

GetLinearProjectIdOk returns a tuple with the LinearProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearProjectId

`func (o *LinearBindingsResponseBindingsInner) SetLinearProjectId(v string)`

SetLinearProjectId sets LinearProjectId field to given value.


### SetLinearProjectIdNil

`func (o *LinearBindingsResponseBindingsInner) SetLinearProjectIdNil(b bool)`

 SetLinearProjectIdNil sets the value for LinearProjectId to be an explicit nil

### UnsetLinearProjectId
`func (o *LinearBindingsResponseBindingsInner) UnsetLinearProjectId()`

UnsetLinearProjectId ensures that no value is present for LinearProjectId, not even an explicit nil
### GetLinearProjectName

`func (o *LinearBindingsResponseBindingsInner) GetLinearProjectName() string`

GetLinearProjectName returns the LinearProjectName field if non-nil, zero value otherwise.

### GetLinearProjectNameOk

`func (o *LinearBindingsResponseBindingsInner) GetLinearProjectNameOk() (*string, bool)`

GetLinearProjectNameOk returns a tuple with the LinearProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearProjectName

`func (o *LinearBindingsResponseBindingsInner) SetLinearProjectName(v string)`

SetLinearProjectName sets LinearProjectName field to given value.


### SetLinearProjectNameNil

`func (o *LinearBindingsResponseBindingsInner) SetLinearProjectNameNil(b bool)`

 SetLinearProjectNameNil sets the value for LinearProjectName to be an explicit nil

### UnsetLinearProjectName
`func (o *LinearBindingsResponseBindingsInner) UnsetLinearProjectName()`

UnsetLinearProjectName ensures that no value is present for LinearProjectName, not even an explicit nil
### GetLinearWorkspaceName

`func (o *LinearBindingsResponseBindingsInner) GetLinearWorkspaceName() string`

GetLinearWorkspaceName returns the LinearWorkspaceName field if non-nil, zero value otherwise.

### GetLinearWorkspaceNameOk

`func (o *LinearBindingsResponseBindingsInner) GetLinearWorkspaceNameOk() (*string, bool)`

GetLinearWorkspaceNameOk returns a tuple with the LinearWorkspaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearWorkspaceName

`func (o *LinearBindingsResponseBindingsInner) SetLinearWorkspaceName(v string)`

SetLinearWorkspaceName sets LinearWorkspaceName field to given value.


### GetMode

`func (o *LinearBindingsResponseBindingsInner) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *LinearBindingsResponseBindingsInner) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *LinearBindingsResponseBindingsInner) SetMode(v string)`

SetMode sets Mode field to given value.


### GetProjectId

`func (o *LinearBindingsResponseBindingsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *LinearBindingsResponseBindingsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *LinearBindingsResponseBindingsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProjectName

`func (o *LinearBindingsResponseBindingsInner) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *LinearBindingsResponseBindingsInner) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *LinearBindingsResponseBindingsInner) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### GetTeamId

`func (o *LinearBindingsResponseBindingsInner) GetTeamId() string`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *LinearBindingsResponseBindingsInner) GetTeamIdOk() (*string, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *LinearBindingsResponseBindingsInner) SetTeamId(v string)`

SetTeamId sets TeamId field to given value.


### GetTeamKey

`func (o *LinearBindingsResponseBindingsInner) GetTeamKey() string`

GetTeamKey returns the TeamKey field if non-nil, zero value otherwise.

### GetTeamKeyOk

`func (o *LinearBindingsResponseBindingsInner) GetTeamKeyOk() (*string, bool)`

GetTeamKeyOk returns a tuple with the TeamKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamKey

`func (o *LinearBindingsResponseBindingsInner) SetTeamKey(v string)`

SetTeamKey sets TeamKey field to given value.


### GetTeamName

`func (o *LinearBindingsResponseBindingsInner) GetTeamName() string`

GetTeamName returns the TeamName field if non-nil, zero value otherwise.

### GetTeamNameOk

`func (o *LinearBindingsResponseBindingsInner) GetTeamNameOk() (*string, bool)`

GetTeamNameOk returns a tuple with the TeamName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamName

`func (o *LinearBindingsResponseBindingsInner) SetTeamName(v string)`

SetTeamName sets TeamName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


