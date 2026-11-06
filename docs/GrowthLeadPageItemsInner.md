# GrowthLeadPageItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Company** | [**GrowthLeadPageItemsInnerCompany**](GrowthLeadPageItemsInnerCompany.md) |  | 
**CreatedAt** | **string** |  | 
**Evidence** | [**[]GrowthLeadPageItemsInnerEvidenceInner**](GrowthLeadPageItemsInnerEvidenceInner.md) |  | 
**FitScore** | **NullableInt32** |  | 
**Id** | **string** |  | 
**Person** | [**GrowthLeadPageItemsInnerPerson**](GrowthLeadPageItemsInnerPerson.md) |  | 
**PlayId** | **string** |  | 
**Provenance** | [**GrowthLeadPageItemsInnerProvenance**](GrowthLeadPageItemsInnerProvenance.md) |  | 
**Status** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewGrowthLeadPageItemsInner

`func NewGrowthLeadPageItemsInner(company GrowthLeadPageItemsInnerCompany, createdAt string, evidence []GrowthLeadPageItemsInnerEvidenceInner, fitScore NullableInt32, id string, person GrowthLeadPageItemsInnerPerson, playId string, provenance GrowthLeadPageItemsInnerProvenance, status string, updatedAt string, ) *GrowthLeadPageItemsInner`

NewGrowthLeadPageItemsInner instantiates a new GrowthLeadPageItemsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthLeadPageItemsInnerWithDefaults

`func NewGrowthLeadPageItemsInnerWithDefaults() *GrowthLeadPageItemsInner`

NewGrowthLeadPageItemsInnerWithDefaults instantiates a new GrowthLeadPageItemsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompany

`func (o *GrowthLeadPageItemsInner) GetCompany() GrowthLeadPageItemsInnerCompany`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *GrowthLeadPageItemsInner) GetCompanyOk() (*GrowthLeadPageItemsInnerCompany, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *GrowthLeadPageItemsInner) SetCompany(v GrowthLeadPageItemsInnerCompany)`

SetCompany sets Company field to given value.


### GetCreatedAt

`func (o *GrowthLeadPageItemsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthLeadPageItemsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthLeadPageItemsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEvidence

`func (o *GrowthLeadPageItemsInner) GetEvidence() []GrowthLeadPageItemsInnerEvidenceInner`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *GrowthLeadPageItemsInner) GetEvidenceOk() (*[]GrowthLeadPageItemsInnerEvidenceInner, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *GrowthLeadPageItemsInner) SetEvidence(v []GrowthLeadPageItemsInnerEvidenceInner)`

SetEvidence sets Evidence field to given value.


### GetFitScore

`func (o *GrowthLeadPageItemsInner) GetFitScore() int32`

GetFitScore returns the FitScore field if non-nil, zero value otherwise.

### GetFitScoreOk

`func (o *GrowthLeadPageItemsInner) GetFitScoreOk() (*int32, bool)`

GetFitScoreOk returns a tuple with the FitScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFitScore

`func (o *GrowthLeadPageItemsInner) SetFitScore(v int32)`

SetFitScore sets FitScore field to given value.


### SetFitScoreNil

`func (o *GrowthLeadPageItemsInner) SetFitScoreNil(b bool)`

 SetFitScoreNil sets the value for FitScore to be an explicit nil

### UnsetFitScore
`func (o *GrowthLeadPageItemsInner) UnsetFitScore()`

UnsetFitScore ensures that no value is present for FitScore, not even an explicit nil
### GetId

`func (o *GrowthLeadPageItemsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthLeadPageItemsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthLeadPageItemsInner) SetId(v string)`

SetId sets Id field to given value.


### GetPerson

`func (o *GrowthLeadPageItemsInner) GetPerson() GrowthLeadPageItemsInnerPerson`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *GrowthLeadPageItemsInner) GetPersonOk() (*GrowthLeadPageItemsInnerPerson, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *GrowthLeadPageItemsInner) SetPerson(v GrowthLeadPageItemsInnerPerson)`

SetPerson sets Person field to given value.


### GetPlayId

`func (o *GrowthLeadPageItemsInner) GetPlayId() string`

GetPlayId returns the PlayId field if non-nil, zero value otherwise.

### GetPlayIdOk

`func (o *GrowthLeadPageItemsInner) GetPlayIdOk() (*string, bool)`

GetPlayIdOk returns a tuple with the PlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayId

`func (o *GrowthLeadPageItemsInner) SetPlayId(v string)`

SetPlayId sets PlayId field to given value.


### GetProvenance

`func (o *GrowthLeadPageItemsInner) GetProvenance() GrowthLeadPageItemsInnerProvenance`

GetProvenance returns the Provenance field if non-nil, zero value otherwise.

### GetProvenanceOk

`func (o *GrowthLeadPageItemsInner) GetProvenanceOk() (*GrowthLeadPageItemsInnerProvenance, bool)`

GetProvenanceOk returns a tuple with the Provenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenance

`func (o *GrowthLeadPageItemsInner) SetProvenance(v GrowthLeadPageItemsInnerProvenance)`

SetProvenance sets Provenance field to given value.


### GetStatus

`func (o *GrowthLeadPageItemsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthLeadPageItemsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthLeadPageItemsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *GrowthLeadPageItemsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GrowthLeadPageItemsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GrowthLeadPageItemsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


