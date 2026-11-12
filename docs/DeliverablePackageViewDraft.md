# DeliverablePackageViewDraft

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
**Summary** | Pointer to **NullableString** |  | [optional]
**Title** | **string** |  |
**VideoUrl** | Pointer to **NullableString** |  | [optional]

## Methods

### NewDeliverablePackageViewDraft

`func NewDeliverablePackageViewDraft(title string, ) *DeliverablePackageViewDraft`

NewDeliverablePackageViewDraft instantiates a new DeliverablePackageViewDraft object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeliverablePackageViewDraftWithDefaults

`func NewDeliverablePackageViewDraftWithDefaults() *DeliverablePackageViewDraft`

NewDeliverablePackageViewDraftWithDefaults instantiates a new DeliverablePackageViewDraft object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAcceptanceCriteria

`func (o *DeliverablePackageViewDraft) GetAcceptanceCriteria() []string`

GetAcceptanceCriteria returns the AcceptanceCriteria field if non-nil, zero value otherwise.

### GetAcceptanceCriteriaOk

`func (o *DeliverablePackageViewDraft) GetAcceptanceCriteriaOk() (*[]string, bool)`

GetAcceptanceCriteriaOk returns a tuple with the AcceptanceCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptanceCriteria

`func (o *DeliverablePackageViewDraft) SetAcceptanceCriteria(v []string)`

SetAcceptanceCriteria sets AcceptanceCriteria field to given value.

### HasAcceptanceCriteria

`func (o *DeliverablePackageViewDraft) HasAcceptanceCriteria() bool`

HasAcceptanceCriteria returns a boolean if a field has been set.

### GetClientStatus

`func (o *DeliverablePackageViewDraft) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *DeliverablePackageViewDraft) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *DeliverablePackageViewDraft) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.

### HasClientStatus

`func (o *DeliverablePackageViewDraft) HasClientStatus() bool`

HasClientStatus returns a boolean if a field has been set.

### GetCycleIds

`func (o *DeliverablePackageViewDraft) GetCycleIds() []string`

GetCycleIds returns the CycleIds field if non-nil, zero value otherwise.

### GetCycleIdsOk

`func (o *DeliverablePackageViewDraft) GetCycleIdsOk() (*[]string, bool)`

GetCycleIdsOk returns a tuple with the CycleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleIds

`func (o *DeliverablePackageViewDraft) SetCycleIds(v []string)`

SetCycleIds sets CycleIds field to given value.

### HasCycleIds

`func (o *DeliverablePackageViewDraft) HasCycleIds() bool`

HasCycleIds returns a boolean if a field has been set.

### GetDueDate

`func (o *DeliverablePackageViewDraft) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *DeliverablePackageViewDraft) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *DeliverablePackageViewDraft) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *DeliverablePackageViewDraft) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *DeliverablePackageViewDraft) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *DeliverablePackageViewDraft) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEvidenceSummary

`func (o *DeliverablePackageViewDraft) GetEvidenceSummary() string`

GetEvidenceSummary returns the EvidenceSummary field if non-nil, zero value otherwise.

### GetEvidenceSummaryOk

`func (o *DeliverablePackageViewDraft) GetEvidenceSummaryOk() (*string, bool)`

GetEvidenceSummaryOk returns a tuple with the EvidenceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceSummary

`func (o *DeliverablePackageViewDraft) SetEvidenceSummary(v string)`

SetEvidenceSummary sets EvidenceSummary field to given value.

### HasEvidenceSummary

`func (o *DeliverablePackageViewDraft) HasEvidenceSummary() bool`

HasEvidenceSummary returns a boolean if a field has been set.

### SetEvidenceSummaryNil

`func (o *DeliverablePackageViewDraft) SetEvidenceSummaryNil(b bool)`

 SetEvidenceSummaryNil sets the value for EvidenceSummary to be an explicit nil

### UnsetEvidenceSummary
`func (o *DeliverablePackageViewDraft) UnsetEvidenceSummary()`

UnsetEvidenceSummary ensures that no value is present for EvidenceSummary, not even an explicit nil
### GetLimitations

`func (o *DeliverablePackageViewDraft) GetLimitations() string`

GetLimitations returns the Limitations field if non-nil, zero value otherwise.

### GetLimitationsOk

`func (o *DeliverablePackageViewDraft) GetLimitationsOk() (*string, bool)`

GetLimitationsOk returns a tuple with the Limitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitations

`func (o *DeliverablePackageViewDraft) SetLimitations(v string)`

SetLimitations sets Limitations field to given value.

### HasLimitations

`func (o *DeliverablePackageViewDraft) HasLimitations() bool`

HasLimitations returns a boolean if a field has been set.

### SetLimitationsNil

`func (o *DeliverablePackageViewDraft) SetLimitationsNil(b bool)`

 SetLimitationsNil sets the value for Limitations to be an explicit nil

### UnsetLimitations
`func (o *DeliverablePackageViewDraft) UnsetLimitations()`

UnsetLimitations ensures that no value is present for Limitations, not even an explicit nil
### GetPresentationSlides

`func (o *DeliverablePackageViewDraft) GetPresentationSlides() []CreateDeliverablePackagePresentationSlidesInner`

GetPresentationSlides returns the PresentationSlides field if non-nil, zero value otherwise.

### GetPresentationSlidesOk

`func (o *DeliverablePackageViewDraft) GetPresentationSlidesOk() (*[]CreateDeliverablePackagePresentationSlidesInner, bool)`

GetPresentationSlidesOk returns a tuple with the PresentationSlides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresentationSlides

`func (o *DeliverablePackageViewDraft) SetPresentationSlides(v []CreateDeliverablePackagePresentationSlidesInner)`

SetPresentationSlides sets PresentationSlides field to given value.

### HasPresentationSlides

`func (o *DeliverablePackageViewDraft) HasPresentationSlides() bool`

HasPresentationSlides returns a boolean if a field has been set.

### GetPreviewDeploymentId

`func (o *DeliverablePackageViewDraft) GetPreviewDeploymentId() string`

GetPreviewDeploymentId returns the PreviewDeploymentId field if non-nil, zero value otherwise.

### GetPreviewDeploymentIdOk

`func (o *DeliverablePackageViewDraft) GetPreviewDeploymentIdOk() (*string, bool)`

GetPreviewDeploymentIdOk returns a tuple with the PreviewDeploymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewDeploymentId

`func (o *DeliverablePackageViewDraft) SetPreviewDeploymentId(v string)`

SetPreviewDeploymentId sets PreviewDeploymentId field to given value.

### HasPreviewDeploymentId

`func (o *DeliverablePackageViewDraft) HasPreviewDeploymentId() bool`

HasPreviewDeploymentId returns a boolean if a field has been set.

### SetPreviewDeploymentIdNil

`func (o *DeliverablePackageViewDraft) SetPreviewDeploymentIdNil(b bool)`

 SetPreviewDeploymentIdNil sets the value for PreviewDeploymentId to be an explicit nil

### UnsetPreviewDeploymentId
`func (o *DeliverablePackageViewDraft) UnsetPreviewDeploymentId()`

UnsetPreviewDeploymentId ensures that no value is present for PreviewDeploymentId, not even an explicit nil
### GetPreviewExpectedSha

`func (o *DeliverablePackageViewDraft) GetPreviewExpectedSha() string`

GetPreviewExpectedSha returns the PreviewExpectedSha field if non-nil, zero value otherwise.

### GetPreviewExpectedShaOk

`func (o *DeliverablePackageViewDraft) GetPreviewExpectedShaOk() (*string, bool)`

GetPreviewExpectedShaOk returns a tuple with the PreviewExpectedSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewExpectedSha

`func (o *DeliverablePackageViewDraft) SetPreviewExpectedSha(v string)`

SetPreviewExpectedSha sets PreviewExpectedSha field to given value.

### HasPreviewExpectedSha

`func (o *DeliverablePackageViewDraft) HasPreviewExpectedSha() bool`

HasPreviewExpectedSha returns a boolean if a field has been set.

### SetPreviewExpectedShaNil

`func (o *DeliverablePackageViewDraft) SetPreviewExpectedShaNil(b bool)`

 SetPreviewExpectedShaNil sets the value for PreviewExpectedSha to be an explicit nil

### UnsetPreviewExpectedSha
`func (o *DeliverablePackageViewDraft) UnsetPreviewExpectedSha()`

UnsetPreviewExpectedSha ensures that no value is present for PreviewExpectedSha, not even an explicit nil
### GetSummary

`func (o *DeliverablePackageViewDraft) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DeliverablePackageViewDraft) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DeliverablePackageViewDraft) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *DeliverablePackageViewDraft) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *DeliverablePackageViewDraft) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *DeliverablePackageViewDraft) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *DeliverablePackageViewDraft) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliverablePackageViewDraft) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliverablePackageViewDraft) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetVideoUrl

`func (o *DeliverablePackageViewDraft) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *DeliverablePackageViewDraft) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *DeliverablePackageViewDraft) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *DeliverablePackageViewDraft) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### SetVideoUrlNil

`func (o *DeliverablePackageViewDraft) SetVideoUrlNil(b bool)`

 SetVideoUrlNil sets the value for VideoUrl to be an explicit nil

### UnsetVideoUrl
`func (o *DeliverablePackageViewDraft) UnsetVideoUrl()`

UnsetVideoUrl ensures that no value is present for VideoUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


