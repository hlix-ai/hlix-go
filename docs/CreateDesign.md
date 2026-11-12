# CreateDesign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Brief** | Pointer to **string** |  | [optional]
**CycleId** | Pointer to **string** |  | [optional]
**IdempotencyKey** | Pointer to **string** |  | [optional]
**Intent** | **string** |  |
**Sources** | Pointer to [**[]CreateDesignSourcesInner**](CreateDesignSourcesInner.md) |  | [optional]
**Title** | **string** |  |

## Methods

### NewCreateDesign

`func NewCreateDesign(intent string, title string, ) *CreateDesign`

NewCreateDesign instantiates a new CreateDesign object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateDesignWithDefaults

`func NewCreateDesignWithDefaults() *CreateDesign`

NewCreateDesignWithDefaults instantiates a new CreateDesign object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBrief

`func (o *CreateDesign) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *CreateDesign) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *CreateDesign) SetBrief(v string)`

SetBrief sets Brief field to given value.

### HasBrief

`func (o *CreateDesign) HasBrief() bool`

HasBrief returns a boolean if a field has been set.

### GetCycleId

`func (o *CreateDesign) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CreateDesign) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CreateDesign) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.

### HasCycleId

`func (o *CreateDesign) HasCycleId() bool`

HasCycleId returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *CreateDesign) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *CreateDesign) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *CreateDesign) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *CreateDesign) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.

### GetIntent

`func (o *CreateDesign) GetIntent() string`

GetIntent returns the Intent field if non-nil, zero value otherwise.

### GetIntentOk

`func (o *CreateDesign) GetIntentOk() (*string, bool)`

GetIntentOk returns a tuple with the Intent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntent

`func (o *CreateDesign) SetIntent(v string)`

SetIntent sets Intent field to given value.


### GetSources

`func (o *CreateDesign) GetSources() []CreateDesignSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *CreateDesign) GetSourcesOk() (*[]CreateDesignSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *CreateDesign) SetSources(v []CreateDesignSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *CreateDesign) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetTitle

`func (o *CreateDesign) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateDesign) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateDesign) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


