# ClientBillableRateSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Basis** | **string** |  | 
**CapturedAt** | **string** |  | 
**Note** | **string** |  | 
**CostMicros** | **int64** |  | 
**InputPricePerMTokensMicros** | **int64** |  | 
**MarkupBps** | **float32** |  | 
**ModelIdentifier** | **string** |  | 
**OutputPricePerMTokensMicros** | **int64** |  | 
**TokensIn** | **float32** |  | 
**TokensOut** | **float32** |  | 

## Methods

### NewClientBillableRateSnapshot

`func NewClientBillableRateSnapshot(basis string, capturedAt string, note string, costMicros int64, inputPricePerMTokensMicros int64, markupBps float32, modelIdentifier string, outputPricePerMTokensMicros int64, tokensIn float32, tokensOut float32, ) *ClientBillableRateSnapshot`

NewClientBillableRateSnapshot instantiates a new ClientBillableRateSnapshot object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBillableRateSnapshotWithDefaults

`func NewClientBillableRateSnapshotWithDefaults() *ClientBillableRateSnapshot`

NewClientBillableRateSnapshotWithDefaults instantiates a new ClientBillableRateSnapshot object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBasis

`func (o *ClientBillableRateSnapshot) GetBasis() string`

GetBasis returns the Basis field if non-nil, zero value otherwise.

### GetBasisOk

`func (o *ClientBillableRateSnapshot) GetBasisOk() (*string, bool)`

GetBasisOk returns a tuple with the Basis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasis

`func (o *ClientBillableRateSnapshot) SetBasis(v string)`

SetBasis sets Basis field to given value.


### GetCapturedAt

`func (o *ClientBillableRateSnapshot) GetCapturedAt() string`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *ClientBillableRateSnapshot) GetCapturedAtOk() (*string, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *ClientBillableRateSnapshot) SetCapturedAt(v string)`

SetCapturedAt sets CapturedAt field to given value.


### GetNote

`func (o *ClientBillableRateSnapshot) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ClientBillableRateSnapshot) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ClientBillableRateSnapshot) SetNote(v string)`

SetNote sets Note field to given value.


### GetCostMicros

`func (o *ClientBillableRateSnapshot) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *ClientBillableRateSnapshot) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *ClientBillableRateSnapshot) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### GetInputPricePerMTokensMicros

`func (o *ClientBillableRateSnapshot) GetInputPricePerMTokensMicros() int64`

GetInputPricePerMTokensMicros returns the InputPricePerMTokensMicros field if non-nil, zero value otherwise.

### GetInputPricePerMTokensMicrosOk

`func (o *ClientBillableRateSnapshot) GetInputPricePerMTokensMicrosOk() (*int64, bool)`

GetInputPricePerMTokensMicrosOk returns a tuple with the InputPricePerMTokensMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputPricePerMTokensMicros

`func (o *ClientBillableRateSnapshot) SetInputPricePerMTokensMicros(v int64)`

SetInputPricePerMTokensMicros sets InputPricePerMTokensMicros field to given value.


### GetMarkupBps

`func (o *ClientBillableRateSnapshot) GetMarkupBps() float32`

GetMarkupBps returns the MarkupBps field if non-nil, zero value otherwise.

### GetMarkupBpsOk

`func (o *ClientBillableRateSnapshot) GetMarkupBpsOk() (*float32, bool)`

GetMarkupBpsOk returns a tuple with the MarkupBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkupBps

`func (o *ClientBillableRateSnapshot) SetMarkupBps(v float32)`

SetMarkupBps sets MarkupBps field to given value.


### GetModelIdentifier

`func (o *ClientBillableRateSnapshot) GetModelIdentifier() string`

GetModelIdentifier returns the ModelIdentifier field if non-nil, zero value otherwise.

### GetModelIdentifierOk

`func (o *ClientBillableRateSnapshot) GetModelIdentifierOk() (*string, bool)`

GetModelIdentifierOk returns a tuple with the ModelIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelIdentifier

`func (o *ClientBillableRateSnapshot) SetModelIdentifier(v string)`

SetModelIdentifier sets ModelIdentifier field to given value.


### GetOutputPricePerMTokensMicros

`func (o *ClientBillableRateSnapshot) GetOutputPricePerMTokensMicros() int64`

GetOutputPricePerMTokensMicros returns the OutputPricePerMTokensMicros field if non-nil, zero value otherwise.

### GetOutputPricePerMTokensMicrosOk

`func (o *ClientBillableRateSnapshot) GetOutputPricePerMTokensMicrosOk() (*int64, bool)`

GetOutputPricePerMTokensMicrosOk returns a tuple with the OutputPricePerMTokensMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputPricePerMTokensMicros

`func (o *ClientBillableRateSnapshot) SetOutputPricePerMTokensMicros(v int64)`

SetOutputPricePerMTokensMicros sets OutputPricePerMTokensMicros field to given value.


### GetTokensIn

`func (o *ClientBillableRateSnapshot) GetTokensIn() float32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *ClientBillableRateSnapshot) GetTokensInOk() (*float32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *ClientBillableRateSnapshot) SetTokensIn(v float32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *ClientBillableRateSnapshot) GetTokensOut() float32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *ClientBillableRateSnapshot) GetTokensOutOk() (*float32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *ClientBillableRateSnapshot) SetTokensOut(v float32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


