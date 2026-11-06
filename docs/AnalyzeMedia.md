# AnalyzeMedia

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** |  | 
**ProjectId** | Pointer to **string** |  | [optional] 
**Question** | **string** |  | 
**Source** | [**AnalyzeMediaSource**](AnalyzeMediaSource.md) |  | 

## Methods

### NewAnalyzeMedia

`func NewAnalyzeMedia(kind string, question string, source AnalyzeMediaSource, ) *AnalyzeMedia`

NewAnalyzeMedia instantiates a new AnalyzeMedia object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyzeMediaWithDefaults

`func NewAnalyzeMediaWithDefaults() *AnalyzeMedia`

NewAnalyzeMediaWithDefaults instantiates a new AnalyzeMedia object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *AnalyzeMedia) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AnalyzeMedia) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AnalyzeMedia) SetKind(v string)`

SetKind sets Kind field to given value.


### GetProjectId

`func (o *AnalyzeMedia) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AnalyzeMedia) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AnalyzeMedia) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *AnalyzeMedia) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetQuestion

`func (o *AnalyzeMedia) GetQuestion() string`

GetQuestion returns the Question field if non-nil, zero value otherwise.

### GetQuestionOk

`func (o *AnalyzeMedia) GetQuestionOk() (*string, bool)`

GetQuestionOk returns a tuple with the Question field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestion

`func (o *AnalyzeMedia) SetQuestion(v string)`

SetQuestion sets Question field to given value.


### GetSource

`func (o *AnalyzeMedia) GetSource() AnalyzeMediaSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AnalyzeMedia) GetSourceOk() (*AnalyzeMediaSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AnalyzeMedia) SetSource(v AnalyzeMediaSource)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


