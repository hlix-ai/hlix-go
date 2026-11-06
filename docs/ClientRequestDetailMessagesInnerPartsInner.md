# ClientRequestDetailMessagesInnerPartsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Type** | **string** |  | 
**Producer** | **string** |  | 
**Spec** | [**ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec**](ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec.md) |  | 
**Error** | Pointer to **string** |  | [optional] 
**Input** | Pointer to **interface{}** |  | [optional] 
**Output** | Pointer to **interface{}** |  | [optional] 
**State** | **string** |  | 
**ToolCallId** | **string** |  | 
**ToolName** | **string** |  | 

## Methods

### NewClientRequestDetailMessagesInnerPartsInner

`func NewClientRequestDetailMessagesInnerPartsInner(text string, type_ string, producer string, spec ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec, state string, toolCallId string, toolName string, ) *ClientRequestDetailMessagesInnerPartsInner`

NewClientRequestDetailMessagesInnerPartsInner instantiates a new ClientRequestDetailMessagesInnerPartsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientRequestDetailMessagesInnerPartsInnerWithDefaults

`func NewClientRequestDetailMessagesInnerPartsInnerWithDefaults() *ClientRequestDetailMessagesInnerPartsInner`

NewClientRequestDetailMessagesInnerPartsInnerWithDefaults instantiates a new ClientRequestDetailMessagesInnerPartsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetText(v string)`

SetText sets Text field to given value.


### GetType

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetType(v string)`

SetType sets Type field to given value.


### GetProducer

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetProducer() string`

GetProducer returns the Producer field if non-nil, zero value otherwise.

### GetProducerOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetProducerOk() (*string, bool)`

GetProducerOk returns a tuple with the Producer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProducer

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetProducer(v string)`

SetProducer sets Producer field to given value.


### GetSpec

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetSpec() ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec`

GetSpec returns the Spec field if non-nil, zero value otherwise.

### GetSpecOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetSpecOk() (*ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec, bool)`

GetSpecOk returns a tuple with the Spec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpec

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetSpec(v ClientRequestDetailMessagesInnerPartsInnerOneOf2Spec)`

SetSpec sets Spec field to given value.


### GetError

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ClientRequestDetailMessagesInnerPartsInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetInput

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetInput() interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetInputOk() (*interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetInput(v interface{})`

SetInput sets Input field to given value.

### HasInput

`func (o *ClientRequestDetailMessagesInnerPartsInner) HasInput() bool`

HasInput returns a boolean if a field has been set.

### SetInputNil

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetInputNil(b bool)`

 SetInputNil sets the value for Input to be an explicit nil

### UnsetInput
`func (o *ClientRequestDetailMessagesInnerPartsInner) UnsetInput()`

UnsetInput ensures that no value is present for Input, not even an explicit nil
### GetOutput

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetOutput() interface{}`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetOutputOk() (*interface{}, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetOutput(v interface{})`

SetOutput sets Output field to given value.

### HasOutput

`func (o *ClientRequestDetailMessagesInnerPartsInner) HasOutput() bool`

HasOutput returns a boolean if a field has been set.

### SetOutputNil

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetOutputNil(b bool)`

 SetOutputNil sets the value for Output to be an explicit nil

### UnsetOutput
`func (o *ClientRequestDetailMessagesInnerPartsInner) UnsetOutput()`

UnsetOutput ensures that no value is present for Output, not even an explicit nil
### GetState

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetState(v string)`

SetState sets State field to given value.


### GetToolCallId

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.


### GetToolName

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetToolName() string`

GetToolName returns the ToolName field if non-nil, zero value otherwise.

### GetToolNameOk

`func (o *ClientRequestDetailMessagesInnerPartsInner) GetToolNameOk() (*string, bool)`

GetToolNameOk returns a tuple with the ToolName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolName

`func (o *ClientRequestDetailMessagesInnerPartsInner) SetToolName(v string)`

SetToolName sets ToolName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


