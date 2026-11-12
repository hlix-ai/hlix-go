# GrowthThreadLead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Company** | [**GrowthThreadLeadCompany**](GrowthThreadLeadCompany.md) |  |
**Evidence** | [**[]GrowthLeadPageItemsInnerEvidenceInner**](GrowthLeadPageItemsInnerEvidenceInner.md) |  |
**FitScore** | **NullableInt32** |  |
**Id** | **string** |  |
**Person** | [**GrowthThreadLeadPerson**](GrowthThreadLeadPerson.md) |  |
**PlayId** | **string** |  |
**ProjectId** | **string** |  |
**Status** | **string** |  |

## Methods

### NewGrowthThreadLead

`func NewGrowthThreadLead(company GrowthThreadLeadCompany, evidence []GrowthLeadPageItemsInnerEvidenceInner, fitScore NullableInt32, id string, person GrowthThreadLeadPerson, playId string, projectId string, status string, ) *GrowthThreadLead`

NewGrowthThreadLead instantiates a new GrowthThreadLead object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthThreadLeadWithDefaults

`func NewGrowthThreadLeadWithDefaults() *GrowthThreadLead`

NewGrowthThreadLeadWithDefaults instantiates a new GrowthThreadLead object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCompany

`func (o *GrowthThreadLead) GetCompany() GrowthThreadLeadCompany`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *GrowthThreadLead) GetCompanyOk() (*GrowthThreadLeadCompany, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *GrowthThreadLead) SetCompany(v GrowthThreadLeadCompany)`

SetCompany sets Company field to given value.


### GetEvidence

`func (o *GrowthThreadLead) GetEvidence() []GrowthLeadPageItemsInnerEvidenceInner`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *GrowthThreadLead) GetEvidenceOk() (*[]GrowthLeadPageItemsInnerEvidenceInner, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *GrowthThreadLead) SetEvidence(v []GrowthLeadPageItemsInnerEvidenceInner)`

SetEvidence sets Evidence field to given value.


### GetFitScore

`func (o *GrowthThreadLead) GetFitScore() int32`

GetFitScore returns the FitScore field if non-nil, zero value otherwise.

### GetFitScoreOk

`func (o *GrowthThreadLead) GetFitScoreOk() (*int32, bool)`

GetFitScoreOk returns a tuple with the FitScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFitScore

`func (o *GrowthThreadLead) SetFitScore(v int32)`

SetFitScore sets FitScore field to given value.


### SetFitScoreNil

`func (o *GrowthThreadLead) SetFitScoreNil(b bool)`

 SetFitScoreNil sets the value for FitScore to be an explicit nil

### UnsetFitScore
`func (o *GrowthThreadLead) UnsetFitScore()`

UnsetFitScore ensures that no value is present for FitScore, not even an explicit nil
### GetId

`func (o *GrowthThreadLead) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthThreadLead) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthThreadLead) SetId(v string)`

SetId sets Id field to given value.


### GetPerson

`func (o *GrowthThreadLead) GetPerson() GrowthThreadLeadPerson`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *GrowthThreadLead) GetPersonOk() (*GrowthThreadLeadPerson, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *GrowthThreadLead) SetPerson(v GrowthThreadLeadPerson)`

SetPerson sets Person field to given value.


### GetPlayId

`func (o *GrowthThreadLead) GetPlayId() string`

GetPlayId returns the PlayId field if non-nil, zero value otherwise.

### GetPlayIdOk

`func (o *GrowthThreadLead) GetPlayIdOk() (*string, bool)`

GetPlayIdOk returns a tuple with the PlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayId

`func (o *GrowthThreadLead) SetPlayId(v string)`

SetPlayId sets PlayId field to given value.


### GetProjectId

`func (o *GrowthThreadLead) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GrowthThreadLead) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GrowthThreadLead) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetStatus

`func (o *GrowthThreadLead) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthThreadLead) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthThreadLead) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


