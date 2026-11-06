# DeliverablePackageDraft

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

### NewDeliverablePackageDraft

`func NewDeliverablePackageDraft(title string, ) *DeliverablePackageDraft`

NewDeliverablePackageDraft instantiates a new DeliverablePackageDraft object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverablePackageDraftWithDefaults

`func NewDeliverablePackageDraftWithDefaults() *DeliverablePackageDraft`

NewDeliverablePackageDraftWithDefaults instantiates a new DeliverablePackageDraft object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptanceCriteria

`func (o *DeliverablePackageDraft) GetAcceptanceCriteria() []string`

GetAcceptanceCriteria returns the AcceptanceCriteria field if non-nil, zero value otherwise.

### GetAcceptanceCriteriaOk

`func (o *DeliverablePackageDraft) GetAcceptanceCriteriaOk() (*[]string, bool)`

GetAcceptanceCriteriaOk returns a tuple with the AcceptanceCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptanceCriteria

`func (o *DeliverablePackageDraft) SetAcceptanceCriteria(v []string)`

SetAcceptanceCriteria sets AcceptanceCriteria field to given value.

### HasAcceptanceCriteria

`func (o *DeliverablePackageDraft) HasAcceptanceCriteria() bool`

HasAcceptanceCriteria returns a boolean if a field has been set.

### GetClientStatus

`func (o *DeliverablePackageDraft) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *DeliverablePackageDraft) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *DeliverablePackageDraft) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.

### HasClientStatus

`func (o *DeliverablePackageDraft) HasClientStatus() bool`

HasClientStatus returns a boolean if a field has been set.

### GetCycleIds

`func (o *DeliverablePackageDraft) GetCycleIds() []string`

GetCycleIds returns the CycleIds field if non-nil, zero value otherwise.

### GetCycleIdsOk

`func (o *DeliverablePackageDraft) GetCycleIdsOk() (*[]string, bool)`

GetCycleIdsOk returns a tuple with the CycleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleIds

`func (o *DeliverablePackageDraft) SetCycleIds(v []string)`

SetCycleIds sets CycleIds field to given value.

### HasCycleIds

`func (o *DeliverablePackageDraft) HasCycleIds() bool`

HasCycleIds returns a boolean if a field has been set.

### GetDueDate

`func (o *DeliverablePackageDraft) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *DeliverablePackageDraft) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *DeliverablePackageDraft) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *DeliverablePackageDraft) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *DeliverablePackageDraft) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *DeliverablePackageDraft) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEvidenceSummary

`func (o *DeliverablePackageDraft) GetEvidenceSummary() string`

GetEvidenceSummary returns the EvidenceSummary field if non-nil, zero value otherwise.

### GetEvidenceSummaryOk

`func (o *DeliverablePackageDraft) GetEvidenceSummaryOk() (*string, bool)`

GetEvidenceSummaryOk returns a tuple with the EvidenceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceSummary

`func (o *DeliverablePackageDraft) SetEvidenceSummary(v string)`

SetEvidenceSummary sets EvidenceSummary field to given value.

### HasEvidenceSummary

`func (o *DeliverablePackageDraft) HasEvidenceSummary() bool`

HasEvidenceSummary returns a boolean if a field has been set.

### SetEvidenceSummaryNil

`func (o *DeliverablePackageDraft) SetEvidenceSummaryNil(b bool)`

 SetEvidenceSummaryNil sets the value for EvidenceSummary to be an explicit nil

### UnsetEvidenceSummary
`func (o *DeliverablePackageDraft) UnsetEvidenceSummary()`

UnsetEvidenceSummary ensures that no value is present for EvidenceSummary, not even an explicit nil
### GetLimitations

`func (o *DeliverablePackageDraft) GetLimitations() string`

GetLimitations returns the Limitations field if non-nil, zero value otherwise.

### GetLimitationsOk

`func (o *DeliverablePackageDraft) GetLimitationsOk() (*string, bool)`

GetLimitationsOk returns a tuple with the Limitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitations

`func (o *DeliverablePackageDraft) SetLimitations(v string)`

SetLimitations sets Limitations field to given value.

### HasLimitations

`func (o *DeliverablePackageDraft) HasLimitations() bool`

HasLimitations returns a boolean if a field has been set.

### SetLimitationsNil

`func (o *DeliverablePackageDraft) SetLimitationsNil(b bool)`

 SetLimitationsNil sets the value for Limitations to be an explicit nil

### UnsetLimitations
`func (o *DeliverablePackageDraft) UnsetLimitations()`

UnsetLimitations ensures that no value is present for Limitations, not even an explicit nil
### GetPresentationSlides

`func (o *DeliverablePackageDraft) GetPresentationSlides() []CreateDeliverablePackagePresentationSlidesInner`

GetPresentationSlides returns the PresentationSlides field if non-nil, zero value otherwise.

### GetPresentationSlidesOk

`func (o *DeliverablePackageDraft) GetPresentationSlidesOk() (*[]CreateDeliverablePackagePresentationSlidesInner, bool)`

GetPresentationSlidesOk returns a tuple with the PresentationSlides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresentationSlides

`func (o *DeliverablePackageDraft) SetPresentationSlides(v []CreateDeliverablePackagePresentationSlidesInner)`

SetPresentationSlides sets PresentationSlides field to given value.

### HasPresentationSlides

`func (o *DeliverablePackageDraft) HasPresentationSlides() bool`

HasPresentationSlides returns a boolean if a field has been set.

### GetPreviewDeploymentId

`func (o *DeliverablePackageDraft) GetPreviewDeploymentId() string`

GetPreviewDeploymentId returns the PreviewDeploymentId field if non-nil, zero value otherwise.

### GetPreviewDeploymentIdOk

`func (o *DeliverablePackageDraft) GetPreviewDeploymentIdOk() (*string, bool)`

GetPreviewDeploymentIdOk returns a tuple with the PreviewDeploymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewDeploymentId

`func (o *DeliverablePackageDraft) SetPreviewDeploymentId(v string)`

SetPreviewDeploymentId sets PreviewDeploymentId field to given value.

### HasPreviewDeploymentId

`func (o *DeliverablePackageDraft) HasPreviewDeploymentId() bool`

HasPreviewDeploymentId returns a boolean if a field has been set.

### SetPreviewDeploymentIdNil

`func (o *DeliverablePackageDraft) SetPreviewDeploymentIdNil(b bool)`

 SetPreviewDeploymentIdNil sets the value for PreviewDeploymentId to be an explicit nil

### UnsetPreviewDeploymentId
`func (o *DeliverablePackageDraft) UnsetPreviewDeploymentId()`

UnsetPreviewDeploymentId ensures that no value is present for PreviewDeploymentId, not even an explicit nil
### GetPreviewExpectedSha

`func (o *DeliverablePackageDraft) GetPreviewExpectedSha() string`

GetPreviewExpectedSha returns the PreviewExpectedSha field if non-nil, zero value otherwise.

### GetPreviewExpectedShaOk

`func (o *DeliverablePackageDraft) GetPreviewExpectedShaOk() (*string, bool)`

GetPreviewExpectedShaOk returns a tuple with the PreviewExpectedSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewExpectedSha

`func (o *DeliverablePackageDraft) SetPreviewExpectedSha(v string)`

SetPreviewExpectedSha sets PreviewExpectedSha field to given value.

### HasPreviewExpectedSha

`func (o *DeliverablePackageDraft) HasPreviewExpectedSha() bool`

HasPreviewExpectedSha returns a boolean if a field has been set.

### SetPreviewExpectedShaNil

`func (o *DeliverablePackageDraft) SetPreviewExpectedShaNil(b bool)`

 SetPreviewExpectedShaNil sets the value for PreviewExpectedSha to be an explicit nil

### UnsetPreviewExpectedSha
`func (o *DeliverablePackageDraft) UnsetPreviewExpectedSha()`

UnsetPreviewExpectedSha ensures that no value is present for PreviewExpectedSha, not even an explicit nil
### GetSummary

`func (o *DeliverablePackageDraft) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DeliverablePackageDraft) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DeliverablePackageDraft) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *DeliverablePackageDraft) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *DeliverablePackageDraft) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *DeliverablePackageDraft) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *DeliverablePackageDraft) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliverablePackageDraft) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliverablePackageDraft) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetVideoUrl

`func (o *DeliverablePackageDraft) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *DeliverablePackageDraft) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *DeliverablePackageDraft) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *DeliverablePackageDraft) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### SetVideoUrlNil

`func (o *DeliverablePackageDraft) SetVideoUrlNil(b bool)`

 SetVideoUrlNil sets the value for VideoUrl to be an explicit nil

### UnsetVideoUrl
`func (o *DeliverablePackageDraft) UnsetVideoUrl()`

UnsetVideoUrl ensures that no value is present for VideoUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


