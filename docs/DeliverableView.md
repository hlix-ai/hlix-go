# DeliverableView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Approval** | [**DeliverablePackageViewApproval**](DeliverablePackageViewApproval.md) |  | 
**ClientStatus** | **string** |  | 
**CreatedAt** | **string** |  | 
**CycleId** | **string** |  | 
**DueDate** | **NullableString** |  | 
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**Progress** | [**DeliverableViewProgress**](DeliverableViewProgress.md) |  | 
**PublishedAt** | **NullableString** |  | 
**SubmittedRevision** | **NullableInt32** |  | 
**Summary** | **NullableString** |  | 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 
**Visibility** | **string** |  | 

## Methods

### NewDeliverableView

`func NewDeliverableView(approval DeliverablePackageViewApproval, clientStatus string, createdAt string, cycleId string, dueDate NullableString, id string, organizationId string, progress DeliverableViewProgress, publishedAt NullableString, submittedRevision NullableInt32, summary NullableString, title string, updatedAt string, visibility string, ) *DeliverableView`

NewDeliverableView instantiates a new DeliverableView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverableViewWithDefaults

`func NewDeliverableViewWithDefaults() *DeliverableView`

NewDeliverableViewWithDefaults instantiates a new DeliverableView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApproval

`func (o *DeliverableView) GetApproval() DeliverablePackageViewApproval`

GetApproval returns the Approval field if non-nil, zero value otherwise.

### GetApprovalOk

`func (o *DeliverableView) GetApprovalOk() (*DeliverablePackageViewApproval, bool)`

GetApprovalOk returns a tuple with the Approval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproval

`func (o *DeliverableView) SetApproval(v DeliverablePackageViewApproval)`

SetApproval sets Approval field to given value.


### GetClientStatus

`func (o *DeliverableView) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *DeliverableView) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *DeliverableView) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.


### GetCreatedAt

`func (o *DeliverableView) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DeliverableView) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DeliverableView) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *DeliverableView) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *DeliverableView) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *DeliverableView) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetDueDate

`func (o *DeliverableView) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *DeliverableView) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *DeliverableView) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.


### SetDueDateNil

`func (o *DeliverableView) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *DeliverableView) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetId

`func (o *DeliverableView) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliverableView) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliverableView) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *DeliverableView) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DeliverableView) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DeliverableView) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProgress

`func (o *DeliverableView) GetProgress() DeliverableViewProgress`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *DeliverableView) GetProgressOk() (*DeliverableViewProgress, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *DeliverableView) SetProgress(v DeliverableViewProgress)`

SetProgress sets Progress field to given value.


### GetPublishedAt

`func (o *DeliverableView) GetPublishedAt() string`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *DeliverableView) GetPublishedAtOk() (*string, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *DeliverableView) SetPublishedAt(v string)`

SetPublishedAt sets PublishedAt field to given value.


### SetPublishedAtNil

`func (o *DeliverableView) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *DeliverableView) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetSubmittedRevision

`func (o *DeliverableView) GetSubmittedRevision() int32`

GetSubmittedRevision returns the SubmittedRevision field if non-nil, zero value otherwise.

### GetSubmittedRevisionOk

`func (o *DeliverableView) GetSubmittedRevisionOk() (*int32, bool)`

GetSubmittedRevisionOk returns a tuple with the SubmittedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedRevision

`func (o *DeliverableView) SetSubmittedRevision(v int32)`

SetSubmittedRevision sets SubmittedRevision field to given value.


### SetSubmittedRevisionNil

`func (o *DeliverableView) SetSubmittedRevisionNil(b bool)`

 SetSubmittedRevisionNil sets the value for SubmittedRevision to be an explicit nil

### UnsetSubmittedRevision
`func (o *DeliverableView) UnsetSubmittedRevision()`

UnsetSubmittedRevision ensures that no value is present for SubmittedRevision, not even an explicit nil
### GetSummary

`func (o *DeliverableView) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *DeliverableView) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *DeliverableView) SetSummary(v string)`

SetSummary sets Summary field to given value.


### SetSummaryNil

`func (o *DeliverableView) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *DeliverableView) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *DeliverableView) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DeliverableView) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DeliverableView) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *DeliverableView) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DeliverableView) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DeliverableView) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVisibility

`func (o *DeliverableView) GetVisibility() string`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *DeliverableView) GetVisibilityOk() (*string, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *DeliverableView) SetVisibility(v string)`

SetVisibility sets Visibility field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


