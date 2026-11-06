# GrowthRun

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

### NewGrowthRun

`func NewGrowthRun(droppedFacts NullableInt32, error_ NullableString, finishedAt NullableString, id string, input GrowthProjectCreatedRunInput, organizationId string, pagesRead []string, projectId string, startedAt string, startedByUserId NullableString, status string, websiteUrl NullableString, ) *GrowthRun`

NewGrowthRun instantiates a new GrowthRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthRunWithDefaults

`func NewGrowthRunWithDefaults() *GrowthRun`

NewGrowthRunWithDefaults instantiates a new GrowthRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDroppedFacts

`func (o *GrowthRun) GetDroppedFacts() int32`

GetDroppedFacts returns the DroppedFacts field if non-nil, zero value otherwise.

### GetDroppedFactsOk

`func (o *GrowthRun) GetDroppedFactsOk() (*int32, bool)`

GetDroppedFactsOk returns a tuple with the DroppedFacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDroppedFacts

`func (o *GrowthRun) SetDroppedFacts(v int32)`

SetDroppedFacts sets DroppedFacts field to given value.


### SetDroppedFactsNil

`func (o *GrowthRun) SetDroppedFactsNil(b bool)`

 SetDroppedFactsNil sets the value for DroppedFacts to be an explicit nil

### UnsetDroppedFacts
`func (o *GrowthRun) UnsetDroppedFacts()`

UnsetDroppedFacts ensures that no value is present for DroppedFacts, not even an explicit nil
### GetError

`func (o *GrowthRun) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GrowthRun) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GrowthRun) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *GrowthRun) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GrowthRun) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFinishedAt

`func (o *GrowthRun) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *GrowthRun) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *GrowthRun) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.


### SetFinishedAtNil

`func (o *GrowthRun) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *GrowthRun) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetId

`func (o *GrowthRun) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthRun) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthRun) SetId(v string)`

SetId sets Id field to given value.


### GetInput

`func (o *GrowthRun) GetInput() GrowthProjectCreatedRunInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *GrowthRun) GetInputOk() (*GrowthProjectCreatedRunInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *GrowthRun) SetInput(v GrowthProjectCreatedRunInput)`

SetInput sets Input field to given value.


### GetOrganizationId

`func (o *GrowthRun) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthRun) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthRun) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPagesRead

`func (o *GrowthRun) GetPagesRead() []string`

GetPagesRead returns the PagesRead field if non-nil, zero value otherwise.

### GetPagesReadOk

`func (o *GrowthRun) GetPagesReadOk() (*[]string, bool)`

GetPagesReadOk returns a tuple with the PagesRead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPagesRead

`func (o *GrowthRun) SetPagesRead(v []string)`

SetPagesRead sets PagesRead field to given value.


### GetProjectId

`func (o *GrowthRun) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GrowthRun) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GrowthRun) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetStartedAt

`func (o *GrowthRun) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GrowthRun) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GrowthRun) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStartedByUserId

`func (o *GrowthRun) GetStartedByUserId() string`

GetStartedByUserId returns the StartedByUserId field if non-nil, zero value otherwise.

### GetStartedByUserIdOk

`func (o *GrowthRun) GetStartedByUserIdOk() (*string, bool)`

GetStartedByUserIdOk returns a tuple with the StartedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedByUserId

`func (o *GrowthRun) SetStartedByUserId(v string)`

SetStartedByUserId sets StartedByUserId field to given value.


### SetStartedByUserIdNil

`func (o *GrowthRun) SetStartedByUserIdNil(b bool)`

 SetStartedByUserIdNil sets the value for StartedByUserId to be an explicit nil

### UnsetStartedByUserId
`func (o *GrowthRun) UnsetStartedByUserId()`

UnsetStartedByUserId ensures that no value is present for StartedByUserId, not even an explicit nil
### GetStatus

`func (o *GrowthRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetWebsiteUrl

`func (o *GrowthRun) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *GrowthRun) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *GrowthRun) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### SetWebsiteUrlNil

`func (o *GrowthRun) SetWebsiteUrlNil(b bool)`

 SetWebsiteUrlNil sets the value for WebsiteUrl to be an explicit nil

### UnsetWebsiteUrl
`func (o *GrowthRun) UnsetWebsiteUrl()`

UnsetWebsiteUrl ensures that no value is present for WebsiteUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


