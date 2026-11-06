# DeliverablePackageView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptanceCriteria** | Pointer to **[]string** |  | [optional] 
**Approval** | [**DeliverablePackageViewApproval**](DeliverablePackageViewApproval.md) |  | 
**ClientStatus** | Pointer to **string** |  | [optional] [default to "draft"]
**CreatedAt** | **string** |  | 
**Draft** | Pointer to [**DeliverablePackageViewDraft**](DeliverablePackageViewDraft.md) |  | [optional] 
**DueDate** | Pointer to **NullableTime** |  | [optional] 
**EvidenceSource** | **string** |  | 
**EvidenceSummary** | Pointer to **NullableString** |  | [optional] 
**GeneratedVideoUrl** | **NullableString** |  | 
**Id** | **string** |  | 
**Limitations** | Pointer to **NullableString** |  | [optional] 
**PresentationSlides** | Pointer to [**[]CreateDeliverablePackagePresentationSlidesInner**](CreateDeliverablePackagePresentationSlidesInner.md) |  | [optional] 
**PreviewAccessUrl** | **NullableString** |  | 
**PreviewDeploymentId** | Pointer to **NullableString** |  | [optional] 
**PreviewGitSha** | **NullableString** |  | 
**ProjectId** | **string** |  | 
**PublishedAt** | **NullableString** |  | 
**SubmittedRevision** | **NullableInt32** |  | 
**Summary** | Pointer to **NullableString** |  | [optional] 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 
**VerificationTarget** | **NullableString** |  | 
**VideoUrl** | Pointer to **NullableString** |  | [optional] 
**Visibility** | **string** |  | 

## Methods

### NewDeliverablePackageView

`func NewDeliverablePackageView(approval DeliverablePackageViewApproval, createdAt string, evidenceSource string, generatedVideoUrl NullableString, id string, previewAccessUrl NullableString, previewGitSha NullableString, projectId string, publishedAt NullableString, submittedRevision NullableInt32, title string, updatedAt string, verificationTarget NullableString, visibility string, ) *DeliverablePackageView`

NewDeliverablePackageView instantiates a new DeliverablePackageView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverablePackageViewWithDefaults

`func NewDeliverablePackageViewWithDefaults() *DeliverablePackageView`

NewDeliverablePackageViewWithDefaults instantiates a new DeliverablePackageView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptanceCriteria

`func (o *DeliverablePackageView) GetAcceptanceCriteria() []string`

GetAcceptanceCriteria returns the AcceptanceCriteria field if non-nil, zero value otherwise.

### GetAcceptanceCriteriaOk

`func (o *DeliverablePackageView) GetAcceptanceCriteriaOk() (*[]string, bool)`

GetAcceptanceCriteriaOk returns a tuple with the AcceptanceCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptanceCriteria

`func (o *DeliverablePackageView) SetAcceptanceCriteria(v []string)`

SetAcceptanceCriteria sets AcceptanceCriteria field to given value.

### HasAcceptanceCriteria

`func (o *DeliverablePackageView) HasAcceptanceCriteria() bool`

HasAcceptanceCriteria returns a boolean if a field has been set.

### GetApproval

`func (o *DeliverablePackageView) GetApproval() DeliverablePackageViewApproval`

GetApproval returns the Approval field if non-nil, zero value otherwise.

### GetApprovalOk

`func (o *DeliverablePackageView) GetApprovalOk() (*DeliverablePackageViewApproval, bool)`

GetApprovalOk returns a tuple with the Approval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproval

`func (o *DeliverablePackageView) SetApproval(v DeliverablePackageViewApproval)`

SetApproval sets Approval field to given value.


### GetClientStatus

`func (o *DeliverablePackageView) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *DeliverablePackageView) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *DeliverablePackageView) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.

### HasClientStatus

`func (o *DeliverablePackageView) HasClientStatus() bool`

HasClientStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DeliverablePackageView) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DeliverablePackageView) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DeliverablePackageView) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDraft

`func (o *DeliverablePackageView) GetDraft() DeliverablePackageViewDraft`

GetDraft returns the Draft field if non-nil, zero value otherwise.

### GetDraftOk

`func (o *DeliverablePackageView) GetDraftOk() (*DeliverablePackageViewDraft, bool)`

GetDraftOk returns a tuple with the Draft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDraft

`func (o *DeliverablePackageView) SetDraft(v DeliverablePackageViewDraft)`

SetDraft sets Draft field to given value.

### HasDraft

`func (o *DeliverablePackageView) HasDraft() bool`

HasDraft returns a boolean if a field has been set.

### GetDueDate

`func (o *DeliverablePackageView) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *DeliverablePackageView) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *DeliverablePackageView) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *DeliverablePackageView) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *DeliverablePackageView) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *DeliverablePackageView) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetEvidenceSource

`func (o *DeliverablePackageView) GetEvidenceSource() string`

GetEvidenceSource returns the EvidenceSource field if non-nil, zero value otherwise.

### GetEvidenceSourceOk

`func (o *DeliverablePackageView) GetEvidenceSourceOk() (*string, bool)`

GetEvidenceSourceOk returns a tuple with the EvidenceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceSource

`func (o *DeliverablePackageView) SetEvidenceSource(v string)`

SetEvidenceSource sets EvidenceSource field to given value.


### GetEvidenceSummary

`func (o *DeliverablePackageView) GetEvidenceSummary() string`

GetEvidenceSummary returns the EvidenceSummary field if non-nil, zero value otherwise.

### GetEvidenceSummaryOk

`func (o *DeliverablePackageView) GetEvidenceSummaryOk() (*string, bool)`

GetEvidenceSummaryOk returns a tuple with the EvidenceSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceSummary

`func (o *DeliverablePackageView) SetEvidenceSummary(v string)`

SetEvidenceSummary sets EvidenceSummary field to given value.

### HasEvidenceSummary

`func (o *DeliverablePackageView) HasEvidenceSummary() bool`

HasEvidenceSummary returns a boolean if a field has been set.

### SetEvidenceSummaryNil

`func (o *DeliverablePackageView) SetEvidenceSummaryNil(b bool)`

 SetEvidenceSummaryNil sets the value for EvidenceSummary to be an explicit nil

### UnsetEvidenceSummary
`func (o *DeliverablePackageView) UnsetEvidenceSummary()`

UnsetEvidenceSummary ensures that no value is present for EvidenceSummary, not even an explicit nil
### GetGeneratedVideoUrl

`func (o *DeliverablePackageView) GetGeneratedVideoUrl() string`

GetGeneratedVideoUrl returns the GeneratedVideoUrl field if non-nil, zero value otherwise.

### GetGeneratedVideoUrlOk

`func (o *DeliverablePackageView) GetGeneratedVideoUrlOk() (*string, bool)`

GetGeneratedVideoUrlOk returns a tuple with the GeneratedVideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedVideoUrl

`func (o *DeliverablePackageView) SetGeneratedVideoUrl(v string)`

SetGeneratedVideoUrl sets GeneratedVideoUrl field to given value.


### SetGeneratedVideoUrlNil

`func (o *DeliverablePackageView) SetGeneratedVideoUrlNil(b bool)`

 SetGeneratedVideoUrlNil sets the value for GeneratedVideoUrl to be an explicit nil

### UnsetGeneratedVideoUrl
`func (o *DeliverablePackageView) UnsetGeneratedVideoUrl()`

UnsetGeneratedVideoUrl ensures that no value is present for GeneratedVideoUrl, not even an explicit nil
### GetId

`func (o *DeliverablePackageView) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliverablePackageView) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliverablePackageView) SetId(v string)`

SetId sets Id field to given value.


### GetLimitations

`func (o *DeliverablePackageView) GetLimitations() string`

GetLimitations returns the Limitations field if non-nil, zero value otherwise.

### GetLimitationsOk

`func (o *DeliverablePackageView) GetLimitationsOk() (*string, bool)`

GetLimitationsOk returns a tuple with the Limitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitations

`func (o *DeliverablePackageView) SetLimitations(v string)`

SetLimitations sets Limitations field to given value.

### HasLimitations

`func (o *DeliverablePackageView) HasLimitations() bool`

HasLimitations returns a boolean if a field has been set.

### SetLimitationsNil

`func (o *DeliverablePackageView) SetLimitationsNil(b bool)`

 SetLimitationsNil sets the value for Limitations to be an explicit nil

### UnsetLimitations
`func (o *DeliverablePackageView) UnsetLimitations()`

UnsetLimitations ensures that no value is present for Limitations, not even an explicit nil
### GetPresentationSlides

`func (o *DeliverablePackageView) GetPresentationSlides() []CreateDeliverablePackagePresentationSlidesInner`

GetPresentationSlides returns the PresentationSlides field if non-nil, zero value otherwise.

### GetPresentationSlidesOk

`func (o *DeliverablePackageView) GetPresentationSlidesOk() (*[]CreateDeliverablePackagePresentationSlidesInner, bool)`

GetPresentationSlidesOk returns a tuple with the PresentationSlides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresentationSlides

`func (o *DeliverablePackageView) SetPresentationSlides(v []CreateDeliverablePackagePresentationSlidesInner)`

SetPresentationSlides sets PresentationSlides field to given value.

### HasPresentationSlides

`func (o *DeliverablePackageView) HasPresentationSlides() bool`

HasPresentationSlides returns a boolean if a field has been set.

### GetPreviewAccessUrl

`func (o *DeliverablePackageView) GetPreviewAccessUrl() string`

GetPreviewAccessUrl returns the PreviewAccessUrl field if non-nil, zero value otherwise.

### GetPreviewAccessUrlOk

`func (o *DeliverablePackageView) GetPreviewAccessUrlOk() (*string, bool)`

GetPreviewAccessUrlOk returns a tuple with the PreviewAccessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewAccessUrl

`func (o *DeliverablePackageView) SetPreviewAccessUrl(v string)`

SetPreviewAccessUrl sets PreviewAccessUrl field to given value.


### SetPreviewAccessUrlNil

`func (o *DeliverablePackageView) SetPreviewAccessUrlNil(b bool)`

 SetPreviewAccessUrlNil sets the value for PreviewAccessUrl to be an explicit nil

### UnsetPreviewAccessUrl
`func (o *DeliverablePackageView) UnsetPreviewAccessUrl()`

UnsetPreviewAccessUrl ensures that no value is present for PreviewAccessUrl, not even an explicit nil
### GetPreviewDeploymentId

`func (o *DeliverablePackageView) GetPreviewDeploymentId() string`

GetPreviewDeploymentId returns the PreviewDeploymentId field if non-nil, zero value otherwise.

### GetPreviewDeploymentIdOk

`func (o *DeliverablePackageView) GetPreviewDeploymentIdOk() (*string, bool)`

GetPreviewDeploymentIdOk returns a tuple with the PreviewDeploymentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewDeploymentId

`func (o *DeliverablePackageView) SetPreviewDeploymentId(v string)`

SetPreviewDeploymentId sets PreviewDeploymentId field to given value.

### HasPreviewDeploymentId

`func (o *DeliverablePackageView) HasPreviewDeploymentId() bool`

HasPreviewDeploymentId returns a boolean if a field has been set.

### SetPreviewDeploymentIdNil

`func (o *DeliverablePackageView) SetPreviewDeploymentIdNil(b bool)`

 SetPreviewDeploymentIdNil sets the value for PreviewDeploymentId to be an explicit nil

### UnsetPreviewDeploymentId
`func (o *DeliverablePackageView) UnsetPreviewDeploymentId()`

UnsetPreviewDeploymentId ensures that no value is present for PreviewDeploymentId, not even an explicit nil
### GetPreviewGitSha

`func (o *DeliverablePackageView) GetPreviewGitSha() string`

GetPreviewGitSha returns the PreviewGitSha field if non-nil, zero value otherwise.

### GetPreviewGitShaOk

`func (o *DeliverablePackageView) GetPreviewGitShaOk() (*string, bool)`

GetPreviewGitShaOk returns a tuple with the PreviewGitSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewGitSha

`func (o *DeliverablePackageView) SetPreviewGitSha(v string)`

SetPreviewGitSha sets PreviewGitSha field to given value.


### SetPreviewGitShaNil

`func (o *DeliverablePackageView) SetPreviewGitShaNil(b bool)`

 SetPreviewGitShaNil sets the value for PreviewGitSha to be an explicit nil

### UnsetPreviewGitSha
`func (o *DeliverablePackageView) UnsetPreviewGitSha()`

UnsetPreviewGitSha ensures that no value is present for PreviewGitSha, not even an explicit nil
### GetProjectId

`func (o *DeliverablePackageView) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *DeliverablePackageView) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *DeliverablePackageView) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetPublishedAt

`func (o *DeliverablePackageView) GetPublishedAt() string`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *DeliverablePackageView) GetPublishedAtOk() (*string, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *DeliverablePackageView) SetPublishedAt(v string)`

SetPublishedAt sets PublishedAt field to given value.


### SetPublishedAtNil

`func (o *DeliverablePackageView) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *DeliverablePackageView) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetSubmittedRevision

`func (o *DeliverablePackageView) GetSubmittedRevision() int32`

GetSubmittedRevision returns the SubmittedRevision field if non-nil, zero value otherwise.

### GetSubmittedRevisionOk

`func (o *DeliverablePackageView) GetSubmittedRevisionOk() (*int32, bool)`

GetSubmittedRevisionOk returns a tuple with the SubmittedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedRevision

`func (o *DeliverablePackageView) SetSubmittedRevision(v int32)`

SetSubmittedRevision sets SubmittedRevision field to given value.


### SetSubmittedRevisionNil

`func (o *DeliverablePackageView) SetSubmittedRevisionNil(b bool)`

 SetSubmittedRevisionNil sets the value for SubmittedRevision to be an explicit nil

### UnsetSubmittedRevision
`func (o *DeliverablePackageView) UnsetSubmittedRevision()`

UnsetSubmittedRevision ensures that no value is present for SubmittedRevision, not even an explicit nil
### GetSummary

`func (o *DeliverablePackageView) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DeliverablePackageView) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DeliverablePackageView) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *DeliverablePackageView) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *DeliverablePackageView) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *DeliverablePackageView) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *DeliverablePackageView) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliverablePackageView) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliverablePackageView) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *DeliverablePackageView) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DeliverablePackageView) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DeliverablePackageView) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVerificationTarget

`func (o *DeliverablePackageView) GetVerificationTarget() string`

GetVerificationTarget returns the VerificationTarget field if non-nil, zero value otherwise.

### GetVerificationTargetOk

`func (o *DeliverablePackageView) GetVerificationTargetOk() (*string, bool)`

GetVerificationTargetOk returns a tuple with the VerificationTarget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationTarget

`func (o *DeliverablePackageView) SetVerificationTarget(v string)`

SetVerificationTarget sets VerificationTarget field to given value.


### SetVerificationTargetNil

`func (o *DeliverablePackageView) SetVerificationTargetNil(b bool)`

 SetVerificationTargetNil sets the value for VerificationTarget to be an explicit nil

### UnsetVerificationTarget
`func (o *DeliverablePackageView) UnsetVerificationTarget()`

UnsetVerificationTarget ensures that no value is present for VerificationTarget, not even an explicit nil
### GetVideoUrl

`func (o *DeliverablePackageView) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *DeliverablePackageView) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *DeliverablePackageView) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *DeliverablePackageView) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### SetVideoUrlNil

`func (o *DeliverablePackageView) SetVideoUrlNil(b bool)`

 SetVideoUrlNil sets the value for VideoUrl to be an explicit nil

### UnsetVideoUrl
`func (o *DeliverablePackageView) UnsetVideoUrl()`

UnsetVideoUrl ensures that no value is present for VideoUrl, not even an explicit nil
### GetVisibility

`func (o *DeliverablePackageView) GetVisibility() string`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *DeliverablePackageView) GetVisibilityOk() (*string, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *DeliverablePackageView) SetVisibility(v string)`

SetVisibility sets Visibility field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


