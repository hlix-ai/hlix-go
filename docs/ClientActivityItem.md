# ClientActivityItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Detail** | **NullableString** |  |
**Id** | **string** |  |
**OccurredAt** | **string** |  |
**ProjectId** | **string** |  |
**Source** | [**ClientActivityItemSource**](ClientActivityItemSource.md) |  |
**Title** | **string** |  |
**Type** | **string** |  |

## Methods

### NewClientActivityItem

`func NewClientActivityItem(detail NullableString, id string, occurredAt string, projectId string, source ClientActivityItemSource, title string, type_ string, ) *ClientActivityItem`

NewClientActivityItem instantiates a new ClientActivityItem object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientActivityItemWithDefaults

`func NewClientActivityItemWithDefaults() *ClientActivityItem`

NewClientActivityItemWithDefaults instantiates a new ClientActivityItem object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDetail

`func (o *ClientActivityItem) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *ClientActivityItem) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *ClientActivityItem) SetDetail(v string)`

SetDetail sets Detail field to given value.


### SetDetailNil

`func (o *ClientActivityItem) SetDetailNil(b bool)`

 SetDetailNil sets the value for Detail to be an explicit nil

### UnsetDetail
`func (o *ClientActivityItem) UnsetDetail()`

UnsetDetail ensures that no value is present for Detail, not even an explicit nil
### GetId

`func (o *ClientActivityItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientActivityItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientActivityItem) SetId(v string)`

SetId sets Id field to given value.


### GetOccurredAt

`func (o *ClientActivityItem) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *ClientActivityItem) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *ClientActivityItem) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetProjectId

`func (o *ClientActivityItem) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ClientActivityItem) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ClientActivityItem) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetSource

`func (o *ClientActivityItem) GetSource() ClientActivityItemSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ClientActivityItem) GetSourceOk() (*ClientActivityItemSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ClientActivityItem) SetSource(v ClientActivityItemSource)`

SetSource sets Source field to given value.


### GetTitle

`func (o *ClientActivityItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ClientActivityItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ClientActivityItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetType

`func (o *ClientActivityItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ClientActivityItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ClientActivityItem) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


