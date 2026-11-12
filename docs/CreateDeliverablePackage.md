# CreateDeliverablePackage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptanceCriteria** | Pointer to **[]string** |  | [optional]
**ClientStatus** | Pointer to **string** |  | [optional] [default to "draft"]
**CycleIds** | Pointer to **[]string** |  | [optional]
**DueDate** | Pointer to **NullableTime** |  | [optional]
**EvidenceSummary** | Pointer to **NullableString** |  | [optional]
**Limitations** | Pointer to **NullableString** |  | [optional]
**PresentationSlides** | Pointer to [**[]CreateDeliverablePackagePresentationSlidesInner**](CreateDeliverablePackagePresentationSlidesInner.md) |  | [optional]
**PreviewDeploymentId** | Pointer to **NullableString** |  | [optional]
**PreviewExpectedSha** | Pointer to **NullableString** |  | [optional]
**ProjectId** | **string** |  |
**Summary** | Pointer to **NullableString** |  | [optional]
**Title** | **string** |  |
**VideoUrl** | Pointer to **NullableString** |  | [optional]

## Methods

### NewCreateDeliverablePackage

`func NewCreateDeliverablePackage(projectId string, title string, ) *CreateDeliverablePackage`

NewCreateDeliverablePackage instantiates a new CreateDeliverablePackage object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateDeliverablePackageWithDefaults

`func NewCreateDeliverablePackageWithDefaults() *CreateDeliverablePackage`

NewCreateDeliverablePackageWithDefaults instantiates a new CreateDeliverablePackage object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAcceptanceCriteria

`func (o *CreateDeliverablePackage) GetAcceptanceCriteria() []string`

GetAcceptanceCriteria returns the AcceptanceCriteria field if non-nil, zero value otherwise.

### GetAcceptanceCriteriaOk

`func (o *CreateDeliverablePackage) GetAcceptanceCriteriaOk() (*[]string, bool)`

GetAcceptanceCriteriaOk returns a tuple with the AcceptanceCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptanceCriteria

`func (o *CreateDeliverablePackage) SetAcceptanceCriteria(v []string)`

SetAcceptanceCriteria sets AcceptanceCriteria field to given value.

### HasAcceptanceCriteria

`func (o *CreateDeliverablePackage) HasAcceptanceCriteria() bool`

HasAcceptanceCriteria returns a boolean if a field has been set.

### GetClientStatus

`func (o *CreateDeliverablePackage) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *CreateDeliverablePackage) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *CreateDeliverablePackage) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.

### HasClientStatus

`func (o *CreateDeliverablePackage) HasClientStatus() bool`

HasClientStatus returns a boolean if a field has been set.

### GetCycleIds

`func (o *CreateDeliverablePackage) GetCycleIds() []string`

GetCycleIds returns the CycleIds field if non-nil, zero value otherwise.

### GetCycleIdsOk

`func (o *CreateDeliverablePackage) GetCycleIdsOk() (*[]string, bool)`

GetCycleIdsOk returns a tuple with the CycleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleIds

`func (o *CreateDeliverablePackage) SetCycleIds(v []string)`

SetCycleIds sets CycleIds field to given value.

### HasCycleIds

`func (o *CreateDeliverablePackage) HasCycleIds() bool`

HasCycleIds returns a boolean if a field has been set.

### GetDueDate

`func (o *CreateDeliverablePackage) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *CreateDeliverablePackage) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *CreateDeliverablePackage) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *CreateDeliverablePackage) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *CreateDeliverablePackage) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *CreateDeliverablePackage) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEvidenceSummary

`func (o *CreateDeliverablePackage) GetEvidenceSummary() string`

GetEvidenceSummary returns the EvidenceSummary field if non-nil, zero value otherwise.

### GetEvidenceSummaryOk

`func (o *CreateDeliverablePackage) GetEvidenceSummaryOk() (*string, bool)`

GetEvidenceSummaryOk returns a tuple with the EvidenceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceSummary

`func (o *CreateDeliverablePackage) SetEvidenceSummary(v string)`

SetEvidenceSummary sets EvidenceSummary field to given value.

### HasEvidenceSummary

`func (o *CreateDeliverablePackage) HasEvidenceSummary() bool`

HasEvidenceSummary returns a boolean if a field has been set.

### SetEvidenceSummaryNil

`func (o *CreateDeliverablePackage) SetEvidenceSummaryNil(b bool)`

 SetEvidenceSummaryNil sets the value for EvidenceSummary to be an explicit nil

### UnsetEvidenceSummary
`func (o *CreateDeliverablePackage) UnsetEvidenceSummary()`

UnsetEvidenceSummary ensures that no value is present for EvidenceSummary, not even an explicit nil
### GetLimitations

`func (o *CreateDeliverablePackage) GetLimitations() string`

GetLimitations returns the Limitations field if non-nil, zero value otherwise.

### GetLimitationsOk

`func (o *CreateDeliverablePackage) GetLimitationsOk() (*string, bool)`

GetLimitationsOk returns a tuple with the Limitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitations

`func (o *CreateDeliverablePackage) SetLimitations(v string)`

SetLimitations sets Limitations field to given value.

### HasLimitations

`func (o *CreateDeliverablePackage) HasLimitations() bool`

HasLimitations returns a boolean if a field has been set.

### SetLimitationsNil

`func (o *CreateDeliverablePackage) SetLimitationsNil(b bool)`

 SetLimitationsNil sets the value for Limitations to be an explicit nil

### UnsetLimitations
`func (o *CreateDeliverablePackage) UnsetLimitations()`

UnsetLimitations ensures that no value is present for Limitations, not even an explicit nil
### GetPresentationSlides

`func (o *CreateDeliverablePackage) GetPresentationSlides() []CreateDeliverablePackagePresentationSlidesInner`

GetPresentationSlides returns the PresentationSlides field if non-nil, zero value otherwise.

### GetPresentationSlidesOk

`func (o *CreateDeliverablePackage) GetPresentationSlidesOk() (*[]CreateDeliverablePackagePresentationSlidesInner, bool)`

GetPresentationSlidesOk returns a tuple with the PresentationSlides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresentationSlides

`func (o *CreateDeliverablePackage) SetPresentationSlides(v []CreateDeliverablePackagePresentationSlidesInner)`

SetPresentationSlides sets PresentationSlides field to given value.

### HasPresentationSlides

`func (o *CreateDeliverablePackage) HasPresentationSlides() bool`

HasPresentationSlides returns a boolean if a field has been set.

### GetPreviewDeploymentId

`func (o *CreateDeliverablePackage) GetPreviewDeploymentId() string`

GetPreviewDeploymentId returns the PreviewDeploymentId field if non-nil, zero value otherwise.

### GetPreviewDeploymentIdOk

`func (o *CreateDeliverablePackage) GetPreviewDeploymentIdOk() (*string, bool)`

GetPreviewDeploymentIdOk returns a tuple with the PreviewDeploymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewDeploymentId

`func (o *CreateDeliverablePackage) SetPreviewDeploymentId(v string)`

SetPreviewDeploymentId sets PreviewDeploymentId field to given value.

### HasPreviewDeploymentId

`func (o *CreateDeliverablePackage) HasPreviewDeploymentId() bool`

HasPreviewDeploymentId returns a boolean if a field has been set.

### SetPreviewDeploymentIdNil

`func (o *CreateDeliverablePackage) SetPreviewDeploymentIdNil(b bool)`

 SetPreviewDeploymentIdNil sets the value for PreviewDeploymentId to be an explicit nil

### UnsetPreviewDeploymentId
`func (o *CreateDeliverablePackage) UnsetPreviewDeploymentId()`

UnsetPreviewDeploymentId ensures that no value is present for PreviewDeploymentId, not even an explicit nil
### GetPreviewExpectedSha

`func (o *CreateDeliverablePackage) GetPreviewExpectedSha() string`

GetPreviewExpectedSha returns the PreviewExpectedSha field if non-nil, zero value otherwise.

### GetPreviewExpectedShaOk

`func (o *CreateDeliverablePackage) GetPreviewExpectedShaOk() (*string, bool)`

GetPreviewExpectedShaOk returns a tuple with the PreviewExpectedSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewExpectedSha

`func (o *CreateDeliverablePackage) SetPreviewExpectedSha(v string)`

SetPreviewExpectedSha sets PreviewExpectedSha field to given value.

### HasPreviewExpectedSha

`func (o *CreateDeliverablePackage) HasPreviewExpectedSha() bool`

HasPreviewExpectedSha returns a boolean if a field has been set.

### SetPreviewExpectedShaNil

`func (o *CreateDeliverablePackage) SetPreviewExpectedShaNil(b bool)`

 SetPreviewExpectedShaNil sets the value for PreviewExpectedSha to be an explicit nil

### UnsetPreviewExpectedSha
`func (o *CreateDeliverablePackage) UnsetPreviewExpectedSha()`

UnsetPreviewExpectedSha ensures that no value is present for PreviewExpectedSha, not even an explicit nil
### GetProjectId

`func (o *CreateDeliverablePackage) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateDeliverablePackage) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateDeliverablePackage) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetSummary

`func (o *CreateDeliverablePackage) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *CreateDeliverablePackage) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *CreateDeliverablePackage) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *CreateDeliverablePackage) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *CreateDeliverablePackage) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *CreateDeliverablePackage) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *CreateDeliverablePackage) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateDeliverablePackage) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateDeliverablePackage) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetVideoUrl

`func (o *CreateDeliverablePackage) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *CreateDeliverablePackage) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *CreateDeliverablePackage) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *CreateDeliverablePackage) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### SetVideoUrlNil

`func (o *CreateDeliverablePackage) SetVideoUrlNil(b bool)`

 SetVideoUrlNil sets the value for VideoUrl to be an explicit nil

### UnsetVideoUrl
`func (o *CreateDeliverablePackage) UnsetVideoUrl()`

UnsetVideoUrl ensures that no value is present for VideoUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


