# ModelCatalog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Models** | [**[]ModelCatalogModelsInner**](ModelCatalogModelsInner.md) |  | 
**Stale** | **bool** |  | 
**UpdatedAt** | **NullableString** |  | 

## Methods

### NewModelCatalog

`func NewModelCatalog(models []ModelCatalogModelsInner, stale bool, updatedAt NullableString, ) *ModelCatalog`

NewModelCatalog instantiates a new ModelCatalog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelCatalogWithDefaults

`func NewModelCatalogWithDefaults() *ModelCatalog`

NewModelCatalogWithDefaults instantiates a new ModelCatalog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModels

`func (o *ModelCatalog) GetModels() []ModelCatalogModelsInner`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *ModelCatalog) GetModelsOk() (*[]ModelCatalogModelsInner, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *ModelCatalog) SetModels(v []ModelCatalogModelsInner)`

SetModels sets Models field to given value.


### GetStale

`func (o *ModelCatalog) GetStale() bool`

GetStale returns the Stale field if non-nil, zero value otherwise.

### GetStaleOk

`func (o *ModelCatalog) GetStaleOk() (*bool, bool)`

GetStaleOk returns a tuple with the Stale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStale

`func (o *ModelCatalog) SetStale(v bool)`

SetStale sets Stale field to given value.


### GetUpdatedAt

`func (o *ModelCatalog) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ModelCatalog) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ModelCatalog) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *ModelCatalog) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ModelCatalog) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


