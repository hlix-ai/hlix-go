# ProjectKnowledgeMemoryAvailability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfiguredNow** | **string** |  | 
**Sources** | [**[]ProjectKnowledgeMemoryAvailabilitySourcesInner**](ProjectKnowledgeMemoryAvailabilitySourcesInner.md) |  | 

## Methods

### NewProjectKnowledgeMemoryAvailability

`func NewProjectKnowledgeMemoryAvailability(configuredNow string, sources []ProjectKnowledgeMemoryAvailabilitySourcesInner, ) *ProjectKnowledgeMemoryAvailability`

NewProjectKnowledgeMemoryAvailability instantiates a new ProjectKnowledgeMemoryAvailability object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectKnowledgeMemoryAvailabilityWithDefaults

`func NewProjectKnowledgeMemoryAvailabilityWithDefaults() *ProjectKnowledgeMemoryAvailability`

NewProjectKnowledgeMemoryAvailabilityWithDefaults instantiates a new ProjectKnowledgeMemoryAvailability object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfiguredNow

`func (o *ProjectKnowledgeMemoryAvailability) GetConfiguredNow() string`

GetConfiguredNow returns the ConfiguredNow field if non-nil, zero value otherwise.

### GetConfiguredNowOk

`func (o *ProjectKnowledgeMemoryAvailability) GetConfiguredNowOk() (*string, bool)`

GetConfiguredNowOk returns a tuple with the ConfiguredNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguredNow

`func (o *ProjectKnowledgeMemoryAvailability) SetConfiguredNow(v string)`

SetConfiguredNow sets ConfiguredNow field to given value.


### GetSources

`func (o *ProjectKnowledgeMemoryAvailability) GetSources() []ProjectKnowledgeMemoryAvailabilitySourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ProjectKnowledgeMemoryAvailability) GetSourcesOk() (*[]ProjectKnowledgeMemoryAvailabilitySourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ProjectKnowledgeMemoryAvailability) SetSources(v []ProjectKnowledgeMemoryAvailabilitySourcesInner)`

SetSources sets Sources field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


