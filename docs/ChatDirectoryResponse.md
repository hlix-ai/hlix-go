# ChatDirectoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ChatDirectoryResponseItemsInner**](ChatDirectoryResponseItemsInner.md) |  | 
**Page** | **float32** |  | 
**PageSize** | **float32** |  | 
**Projects** | [**[]ChatDirectoryResponseProjectsInner**](ChatDirectoryResponseProjectsInner.md) |  | 
**Total** | **float32** |  | 

## Methods

### NewChatDirectoryResponse

`func NewChatDirectoryResponse(items []ChatDirectoryResponseItemsInner, page float32, pageSize float32, projects []ChatDirectoryResponseProjectsInner, total float32, ) *ChatDirectoryResponse`

NewChatDirectoryResponse instantiates a new ChatDirectoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatDirectoryResponseWithDefaults

`func NewChatDirectoryResponseWithDefaults() *ChatDirectoryResponse`

NewChatDirectoryResponseWithDefaults instantiates a new ChatDirectoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ChatDirectoryResponse) GetItems() []ChatDirectoryResponseItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ChatDirectoryResponse) GetItemsOk() (*[]ChatDirectoryResponseItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ChatDirectoryResponse) SetItems(v []ChatDirectoryResponseItemsInner)`

SetItems sets Items field to given value.


### GetPage

`func (o *ChatDirectoryResponse) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ChatDirectoryResponse) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ChatDirectoryResponse) SetPage(v float32)`

SetPage sets Page field to given value.


### GetPageSize

`func (o *ChatDirectoryResponse) GetPageSize() float32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *ChatDirectoryResponse) GetPageSizeOk() (*float32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *ChatDirectoryResponse) SetPageSize(v float32)`

SetPageSize sets PageSize field to given value.


### GetProjects

`func (o *ChatDirectoryResponse) GetProjects() []ChatDirectoryResponseProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ChatDirectoryResponse) GetProjectsOk() (*[]ChatDirectoryResponseProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ChatDirectoryResponse) SetProjects(v []ChatDirectoryResponseProjectsInner)`

SetProjects sets Projects field to given value.


### GetTotal

`func (o *ChatDirectoryResponse) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ChatDirectoryResponse) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ChatDirectoryResponse) SetTotal(v float32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


