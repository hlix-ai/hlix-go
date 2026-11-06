# SequenceCycle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Stage** | **string** |  | 
**StartedAt** | **NullableString** |  | 
**Title** | **string** |  | 

## Methods

### NewSequenceCycle

`func NewSequenceCycle(id string, stage string, startedAt NullableString, title string, ) *SequenceCycle`

NewSequenceCycle instantiates a new SequenceCycle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSequenceCycleWithDefaults

`func NewSequenceCycleWithDefaults() *SequenceCycle`

NewSequenceCycleWithDefaults instantiates a new SequenceCycle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SequenceCycle) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SequenceCycle) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SequenceCycle) SetId(v string)`

SetId sets Id field to given value.


### GetStage

`func (o *SequenceCycle) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *SequenceCycle) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *SequenceCycle) SetStage(v string)`

SetStage sets Stage field to given value.


### GetStartedAt

`func (o *SequenceCycle) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *SequenceCycle) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *SequenceCycle) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *SequenceCycle) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *SequenceCycle) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetTitle

`func (o *SequenceCycle) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SequenceCycle) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SequenceCycle) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


