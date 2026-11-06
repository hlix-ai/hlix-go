# ProjectKnowledge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Extractions** | [**[]ProjectKnowledgeExtractionsInner**](ProjectKnowledgeExtractionsInner.md) |  | 
**Memories** | [**[]ProjectKnowledgeMemoriesInner**](ProjectKnowledgeMemoriesInner.md) |  | 
**MemoryAvailability** | [**ProjectKnowledgeMemoryAvailability**](ProjectKnowledgeMemoryAvailability.md) |  | 
**ProjectId** | **string** |  | 

## Methods

### NewProjectKnowledge

`func NewProjectKnowledge(extractions []ProjectKnowledgeExtractionsInner, memories []ProjectKnowledgeMemoriesInner, memoryAvailability ProjectKnowledgeMemoryAvailability, projectId string, ) *ProjectKnowledge`

NewProjectKnowledge instantiates a new ProjectKnowledge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectKnowledgeWithDefaults

`func NewProjectKnowledgeWithDefaults() *ProjectKnowledge`

NewProjectKnowledgeWithDefaults instantiates a new ProjectKnowledge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtractions

`func (o *ProjectKnowledge) GetExtractions() []ProjectKnowledgeExtractionsInner`

GetExtractions returns the Extractions field if non-nil, zero value otherwise.

### GetExtractionsOk

`func (o *ProjectKnowledge) GetExtractionsOk() (*[]ProjectKnowledgeExtractionsInner, bool)`

GetExtractionsOk returns a tuple with the Extractions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractions

`func (o *ProjectKnowledge) SetExtractions(v []ProjectKnowledgeExtractionsInner)`

SetExtractions sets Extractions field to given value.


### GetMemories

`func (o *ProjectKnowledge) GetMemories() []ProjectKnowledgeMemoriesInner`

GetMemories returns the Memories field if non-nil, zero value otherwise.

### GetMemoriesOk

`func (o *ProjectKnowledge) GetMemoriesOk() (*[]ProjectKnowledgeMemoriesInner, bool)`

GetMemoriesOk returns a tuple with the Memories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemories

`func (o *ProjectKnowledge) SetMemories(v []ProjectKnowledgeMemoriesInner)`

SetMemories sets Memories field to given value.


### GetMemoryAvailability

`func (o *ProjectKnowledge) GetMemoryAvailability() ProjectKnowledgeMemoryAvailability`

GetMemoryAvailability returns the MemoryAvailability field if non-nil, zero value otherwise.

### GetMemoryAvailabilityOk

`func (o *ProjectKnowledge) GetMemoryAvailabilityOk() (*ProjectKnowledgeMemoryAvailability, bool)`

GetMemoryAvailabilityOk returns a tuple with the MemoryAvailability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemoryAvailability

`func (o *ProjectKnowledge) SetMemoryAvailability(v ProjectKnowledgeMemoryAvailability)`

SetMemoryAvailability sets MemoryAvailability field to given value.


### GetProjectId

`func (o *ProjectKnowledge) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectKnowledge) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectKnowledge) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


