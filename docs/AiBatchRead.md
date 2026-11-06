# AiBatchRead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]AiBatchReadItemsInner**](AiBatchReadItemsInner.md) |  | 
**Job** | [**AiBatchAcceptedJob**](AiBatchAcceptedJob.md) |  | 
**NextCursor** | **NullableString** |  | 

## Methods

### NewAiBatchRead

`func NewAiBatchRead(items []AiBatchReadItemsInner, job AiBatchAcceptedJob, nextCursor NullableString, ) *AiBatchRead`

NewAiBatchRead instantiates a new AiBatchRead object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiBatchReadWithDefaults

`func NewAiBatchReadWithDefaults() *AiBatchRead`

NewAiBatchReadWithDefaults instantiates a new AiBatchRead object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *AiBatchRead) GetItems() []AiBatchReadItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AiBatchRead) GetItemsOk() (*[]AiBatchReadItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AiBatchRead) SetItems(v []AiBatchReadItemsInner)`

SetItems sets Items field to given value.


### GetJob

`func (o *AiBatchRead) GetJob() AiBatchAcceptedJob`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *AiBatchRead) GetJobOk() (*AiBatchAcceptedJob, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *AiBatchRead) SetJob(v AiBatchAcceptedJob)`

SetJob sets Job field to given value.


### GetNextCursor

`func (o *AiBatchRead) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *AiBatchRead) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *AiBatchRead) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *AiBatchRead) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *AiBatchRead) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


