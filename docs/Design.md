# Design

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** |  | 
**CycleId** | **NullableString** |  | 
**Id** | **string** |  | 
**Intent** | **string** |  | 
**LatestRevisionId** | **NullableString** |  | 
**ProjectId** | **string** |  | 
**Sources** | Pointer to [**[]CreateDesignSourcesInner**](CreateDesignSourcesInner.md) |  | [optional] 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewDesign

`func NewDesign(createdAt string, cycleId NullableString, id string, intent string, latestRevisionId NullableString, projectId string, title string, updatedAt string, ) *Design`

NewDesign instantiates a new Design object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesignWithDefaults

`func NewDesignWithDefaults() *Design`

NewDesignWithDefaults instantiates a new Design object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *Design) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Design) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Design) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *Design) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *Design) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *Design) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *Design) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *Design) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetId

`func (o *Design) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Design) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Design) SetId(v string)`

SetId sets Id field to given value.


### GetIntent

`func (o *Design) GetIntent() string`

GetIntent returns the Intent field if non-nil, zero value otherwise.

### GetIntentOk

`func (o *Design) GetIntentOk() (*string, bool)`

GetIntentOk returns a tuple with the Intent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntent

`func (o *Design) SetIntent(v string)`

SetIntent sets Intent field to given value.


### GetLatestRevisionId

`func (o *Design) GetLatestRevisionId() string`

GetLatestRevisionId returns the LatestRevisionId field if non-nil, zero value otherwise.

### GetLatestRevisionIdOk

`func (o *Design) GetLatestRevisionIdOk() (*string, bool)`

GetLatestRevisionIdOk returns a tuple with the LatestRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestRevisionId

`func (o *Design) SetLatestRevisionId(v string)`

SetLatestRevisionId sets LatestRevisionId field to given value.


### SetLatestRevisionIdNil

`func (o *Design) SetLatestRevisionIdNil(b bool)`

 SetLatestRevisionIdNil sets the value for LatestRevisionId to be an explicit nil

### UnsetLatestRevisionId
`func (o *Design) UnsetLatestRevisionId()`

UnsetLatestRevisionId ensures that no value is present for LatestRevisionId, not even an explicit nil
### GetProjectId

`func (o *Design) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Design) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Design) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetSources

`func (o *Design) GetSources() []CreateDesignSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *Design) GetSourcesOk() (*[]CreateDesignSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *Design) SetSources(v []CreateDesignSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *Design) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetTitle

`func (o *Design) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Design) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Design) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *Design) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Design) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Design) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


