# GrowthStateLastRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DroppedFacts** | **NullableInt32** |  | 
**Error** | **NullableString** |  | 
**FinishedAt** | **NullableString** |  | 
**Id** | **string** |  | 
**Input** | [**GrowthProjectCreatedRunInput**](GrowthProjectCreatedRunInput.md) |  | 
**OrganizationId** | **string** |  | 
**PagesRead** | **[]string** |  | 
**ProjectId** | **string** |  | 
**StartedAt** | **string** |  | 
**StartedByUserId** | **NullableString** |  | 
**Status** | **string** |  | 
**WebsiteUrl** | **NullableString** |  | 

## Methods

### NewGrowthStateLastRun

`func NewGrowthStateLastRun(droppedFacts NullableInt32, error_ NullableString, finishedAt NullableString, id string, input GrowthProjectCreatedRunInput, organizationId string, pagesRead []string, projectId string, startedAt string, startedByUserId NullableString, status string, websiteUrl NullableString, ) *GrowthStateLastRun`

NewGrowthStateLastRun instantiates a new GrowthStateLastRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthStateLastRunWithDefaults

`func NewGrowthStateLastRunWithDefaults() *GrowthStateLastRun`

NewGrowthStateLastRunWithDefaults instantiates a new GrowthStateLastRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDroppedFacts

`func (o *GrowthStateLastRun) GetDroppedFacts() int32`

GetDroppedFacts returns the DroppedFacts field if non-nil, zero value otherwise.

### GetDroppedFactsOk

`func (o *GrowthStateLastRun) GetDroppedFactsOk() (*int32, bool)`

GetDroppedFactsOk returns a tuple with the DroppedFacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDroppedFacts

`func (o *GrowthStateLastRun) SetDroppedFacts(v int32)`

SetDroppedFacts sets DroppedFacts field to given value.


### SetDroppedFactsNil

`func (o *GrowthStateLastRun) SetDroppedFactsNil(b bool)`

 SetDroppedFactsNil sets the value for DroppedFacts to be an explicit nil

### UnsetDroppedFacts
`func (o *GrowthStateLastRun) UnsetDroppedFacts()`

UnsetDroppedFacts ensures that no value is present for DroppedFacts, not even an explicit nil
### GetError

`func (o *GrowthStateLastRun) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GrowthStateLastRun) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GrowthStateLastRun) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *GrowthStateLastRun) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GrowthStateLastRun) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFinishedAt

`func (o *GrowthStateLastRun) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GrowthStateLastRun) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GrowthStateLastRun) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.


### SetFinishedAtNil

`func (o *GrowthStateLastRun) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *GrowthStateLastRun) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetId

`func (o *GrowthStateLastRun) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthStateLastRun) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthStateLastRun) SetId(v string)`

SetId sets Id field to given value.


### GetInput

`func (o *GrowthStateLastRun) GetInput() GrowthProjectCreatedRunInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *GrowthStateLastRun) GetInputOk() (*GrowthProjectCreatedRunInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *GrowthStateLastRun) SetInput(v GrowthProjectCreatedRunInput)`

SetInput sets Input field to given value.


### GetOrganizationId

`func (o *GrowthStateLastRun) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthStateLastRun) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthStateLastRun) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPagesRead

`func (o *GrowthStateLastRun) GetPagesRead() []string`

GetPagesRead returns the PagesRead field if non-nil, zero value otherwise.

### GetPagesReadOk

`func (o *GrowthStateLastRun) GetPagesReadOk() (*[]string, bool)`

GetPagesReadOk returns a tuple with the PagesRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagesRead

`func (o *GrowthStateLastRun) SetPagesRead(v []string)`

SetPagesRead sets PagesRead field to given value.


### GetProjectId

`func (o *GrowthStateLastRun) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GrowthStateLastRun) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GrowthStateLastRun) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetStartedAt

`func (o *GrowthStateLastRun) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GrowthStateLastRun) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GrowthStateLastRun) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStartedByUserId

`func (o *GrowthStateLastRun) GetStartedByUserId() string`

GetStartedByUserId returns the StartedByUserId field if non-nil, zero value otherwise.

### GetStartedByUserIdOk

`func (o *GrowthStateLastRun) GetStartedByUserIdOk() (*string, bool)`

GetStartedByUserIdOk returns a tuple with the StartedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedByUserId

`func (o *GrowthStateLastRun) SetStartedByUserId(v string)`

SetStartedByUserId sets StartedByUserId field to given value.


### SetStartedByUserIdNil

`func (o *GrowthStateLastRun) SetStartedByUserIdNil(b bool)`

 SetStartedByUserIdNil sets the value for StartedByUserId to be an explicit nil

### UnsetStartedByUserId
`func (o *GrowthStateLastRun) UnsetStartedByUserId()`

UnsetStartedByUserId ensures that no value is present for StartedByUserId, not even an explicit nil
### GetStatus

`func (o *GrowthStateLastRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthStateLastRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthStateLastRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetWebsiteUrl

`func (o *GrowthStateLastRun) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *GrowthStateLastRun) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *GrowthStateLastRun) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### SetWebsiteUrlNil

`func (o *GrowthStateLastRun) SetWebsiteUrlNil(b bool)`

 SetWebsiteUrlNil sets the value for WebsiteUrl to be an explicit nil

### UnsetWebsiteUrl
`func (o *GrowthStateLastRun) UnsetWebsiteUrl()`

UnsetWebsiteUrl ensures that no value is present for WebsiteUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


