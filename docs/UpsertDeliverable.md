# UpsertDeliverable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientStatus** | Pointer to **string** |  | [optional]
**DueDate** | Pointer to **NullableTime** |  | [optional]
**Summary** | Pointer to **NullableString** |  | [optional]
**Title** | **string** |  |

## Methods

### NewUpsertDeliverable

`func NewUpsertDeliverable(title string, ) *UpsertDeliverable`

NewUpsertDeliverable instantiates a new UpsertDeliverable object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpsertDeliverableWithDefaults

`func NewUpsertDeliverableWithDefaults() *UpsertDeliverable`

NewUpsertDeliverableWithDefaults instantiates a new UpsertDeliverable object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetClientStatus

`func (o *UpsertDeliverable) GetClientStatus() string`

GetClientStatus returns the ClientStatus field if non-nil, zero value otherwise.

### GetClientStatusOk

`func (o *UpsertDeliverable) GetClientStatusOk() (*string, bool)`

GetClientStatusOk returns a tuple with the ClientStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientStatus

`func (o *UpsertDeliverable) SetClientStatus(v string)`

SetClientStatus sets ClientStatus field to given value.

### HasClientStatus

`func (o *UpsertDeliverable) HasClientStatus() bool`

HasClientStatus returns a boolean if a field has been set.

### GetDueDate

`func (o *UpsertDeliverable) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *UpsertDeliverable) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *UpsertDeliverable) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *UpsertDeliverable) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *UpsertDeliverable) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *UpsertDeliverable) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetSummary

`func (o *UpsertDeliverable) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *UpsertDeliverable) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *UpsertDeliverable) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *UpsertDeliverable) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *UpsertDeliverable) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *UpsertDeliverable) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetTitle

`func (o *UpsertDeliverable) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpsertDeliverable) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpsertDeliverable) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


