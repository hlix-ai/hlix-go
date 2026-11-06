# Deliverable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientStatus** | **string** |  | 
**CreatedAt** | **string** |  | 
**CycleId** | **string** |  | 
**DueDate** | **NullableString** |  | 
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**PublishedAt** | **NullableString** |  | 
**SubmittedRevision** | **NullableInt32** |  | 
**Summary** | **NullableString** |  | 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 
**Visibility** | **string** |  | 

## Methods

### NewDeliverable

`func NewDeliverable(clientStatus string, createdAt string, cycleId string, dueDate NullableString, id string, organizationId string, publishedAt NullableString, submittedRevision NullableInt32, summary NullableString, title string, updatedAt string, visibility string, ) *Deliverable`

NewDeliverable instantiates a new Deliverable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverableWithDefaults

`func NewDeliverableWithDefaults() *Deliverable`

NewDeliverableWithDefaults instantiates a new Deliverable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientStatus

`func (o *Deliverable) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *Deliverable) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *Deliverable) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.


### GetCreatedAt

`func (o *Deliverable) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Deliverable) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Deliverable) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *Deliverable) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *Deliverable) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *Deliverable) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetDueDate

`func (o *Deliverable) GetDueDate() string`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *Deliverable) GetDueDateOk() (*string, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *Deliverable) SetDueDate(v string)`

SetDueDate sets DueDate field to given value.


### SetDueDateNil

`func (o *Deliverable) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *Deliverable) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetId

`func (o *Deliverable) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Deliverable) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Deliverable) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *Deliverable) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Deliverable) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Deliverable) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPublishedAt

`func (o *Deliverable) GetPublishedAt() string`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *Deliverable) GetPublishedAtOk() (*string, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *Deliverable) SetPublishedAt(v string)`

SetPublishedAt sets PublishedAt field to given value.


### SetPublishedAtNil

`func (o *Deliverable) SetPublishedAtNil(b bool)`

 SetPublishedAtNil sets the value for PublishedAt to be an explicit nil

### UnsetPublishedAt
`func (o *Deliverable) UnsetPublishedAt()`

UnsetPublishedAt ensures that no value is present for PublishedAt, not even an explicit nil
### GetSubmittedRevision

`func (o *Deliverable) GetSubmittedRevision() int32`

GetSubmittedRevision returns the SubmittedRevision field if non-nil, zero value otherwise.

### GetSubmittedRevisionOk

`func (o *Deliverable) GetSubmittedRevisionOk() (*int32, bool)`

GetSubmittedRevisionOk returns a tuple with the SubmittedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedRevision

`func (o *Deliverable) SetSubmittedRevision(v int32)`

SetSubmittedRevision sets SubmittedRevision field to given value.


### SetSubmittedRevisionNil

`func (o *Deliverable) SetSubmittedRevisionNil(b bool)`

 SetSubmittedRevisionNil sets the value for SubmittedRevision to be an explicit nil

### UnsetSubmittedRevision
`func (o *Deliverable) UnsetSubmittedRevision()`

UnsetSubmittedRevision ensures that no value is present for SubmittedRevision, not even an explicit nil
### GetSummary

`func (o *Deliverable) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *Deliverable) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *Deliverable) SetSummary(v string)`

SetSummary sets Summary field to given value.


### SetSummaryNil

`func (o *Deliverable) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *Deliverable) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *Deliverable) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Deliverable) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Deliverable) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *Deliverable) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Deliverable) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Deliverable) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVisibility

`func (o *Deliverable) GetVisibility() string`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *Deliverable) GetVisibilityOk() (*string, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *Deliverable) SetVisibility(v string)`

SetVisibility sets Visibility field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


