# ProjectThreadDirectoryConductor

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LastMessageAt** | **NullableString** |  | 
**Scope** | [**ProjectThreadDirectoryAgentsInnerScope**](ProjectThreadDirectoryAgentsInnerScope.md) |  | 
**ThreadId** | **string** |  | 
**Title** | **NullableString** |  | 

## Methods

### NewProjectThreadDirectoryConductor

`func NewProjectThreadDirectoryConductor(lastMessageAt NullableString, scope ProjectThreadDirectoryAgentsInnerScope, threadId string, title NullableString, ) *ProjectThreadDirectoryConductor`

NewProjectThreadDirectoryConductor instantiates a new ProjectThreadDirectoryConductor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectThreadDirectoryConductorWithDefaults

`func NewProjectThreadDirectoryConductorWithDefaults() *ProjectThreadDirectoryConductor`

NewProjectThreadDirectoryConductorWithDefaults instantiates a new ProjectThreadDirectoryConductor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLastMessageAt

`func (o *ProjectThreadDirectoryConductor) GetLastMessageAt() string`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *ProjectThreadDirectoryConductor) GetLastMessageAtOk() (*string, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *ProjectThreadDirectoryConductor) SetLastMessageAt(v string)`

SetLastMessageAt sets LastMessageAt field to given value.


### SetLastMessageAtNil

`func (o *ProjectThreadDirectoryConductor) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *ProjectThreadDirectoryConductor) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetScope

`func (o *ProjectThreadDirectoryConductor) GetScope() ProjectThreadDirectoryAgentsInnerScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *ProjectThreadDirectoryConductor) GetScopeOk() (*ProjectThreadDirectoryAgentsInnerScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *ProjectThreadDirectoryConductor) SetScope(v ProjectThreadDirectoryAgentsInnerScope)`

SetScope sets Scope field to given value.


### GetThreadId

`func (o *ProjectThreadDirectoryConductor) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *ProjectThreadDirectoryConductor) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *ProjectThreadDirectoryConductor) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetTitle

`func (o *ProjectThreadDirectoryConductor) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProjectThreadDirectoryConductor) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProjectThreadDirectoryConductor) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *ProjectThreadDirectoryConductor) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ProjectThreadDirectoryConductor) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


