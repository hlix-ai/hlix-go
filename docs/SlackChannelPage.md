# SlackChannelPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Channels** | [**[]SlackChannelPageChannelsInner**](SlackChannelPageChannelsInner.md) |  | 
**NextCursor** | **NullableString** |  | 

## Methods

### NewSlackChannelPage

`func NewSlackChannelPage(channels []SlackChannelPageChannelsInner, nextCursor NullableString, ) *SlackChannelPage`

NewSlackChannelPage instantiates a new SlackChannelPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSlackChannelPageWithDefaults

`func NewSlackChannelPageWithDefaults() *SlackChannelPage`

NewSlackChannelPageWithDefaults instantiates a new SlackChannelPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannels

`func (o *SlackChannelPage) GetChannels() []SlackChannelPageChannelsInner`

GetChannels returns the Channels field if non-nil, zero value otherwise.

### GetChannelsOk

`func (o *SlackChannelPage) GetChannelsOk() (*[]SlackChannelPageChannelsInner, bool)`

GetChannelsOk returns a tuple with the Channels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannels

`func (o *SlackChannelPage) SetChannels(v []SlackChannelPageChannelsInner)`

SetChannels sets Channels field to given value.


### GetNextCursor

`func (o *SlackChannelPage) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *SlackChannelPage) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *SlackChannelPage) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *SlackChannelPage) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *SlackChannelPage) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


