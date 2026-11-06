# CycleStageHistoryInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actor** | [**CycleStageHistoryInnerActor**](CycleStageHistoryInnerActor.md) |  | 
**At** | **string** |  | 
**From** | **NullableString** |  | 
**Intake** | Pointer to [**CycleStageHistoryInnerIntake**](CycleStageHistoryInnerIntake.md) |  | [optional] 
**Reason** | Pointer to **string** |  | [optional] 
**RuleSetVersion** | **string** |  | 
**To** | **string** |  | 

## Methods

### NewCycleStageHistoryInner

`func NewCycleStageHistoryInner(actor CycleStageHistoryInnerActor, at string, from NullableString, ruleSetVersion string, to string, ) *CycleStageHistoryInner`

NewCycleStageHistoryInner instantiates a new CycleStageHistoryInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleStageHistoryInnerWithDefaults

`func NewCycleStageHistoryInnerWithDefaults() *CycleStageHistoryInner`

NewCycleStageHistoryInnerWithDefaults instantiates a new CycleStageHistoryInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActor

`func (o *CycleStageHistoryInner) GetActor() CycleStageHistoryInnerActor`

GetActor returns the Actor field if non-nil, zero value otherwise.

### GetActorOk

`func (o *CycleStageHistoryInner) GetActorOk() (*CycleStageHistoryInnerActor, bool)`

GetActorOk returns a tuple with the Actor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActor

`func (o *CycleStageHistoryInner) SetActor(v CycleStageHistoryInnerActor)`

SetActor sets Actor field to given value.


### GetAt

`func (o *CycleStageHistoryInner) GetAt() string`

GetAt returns the At field if non-nil, zero value otherwise.

### GetAtOk

`func (o *CycleStageHistoryInner) GetAtOk() (*string, bool)`

GetAtOk returns a tuple with the At field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAt

`func (o *CycleStageHistoryInner) SetAt(v string)`

SetAt sets At field to given value.


### GetFrom

`func (o *CycleStageHistoryInner) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CycleStageHistoryInner) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CycleStageHistoryInner) SetFrom(v string)`

SetFrom sets From field to given value.


### SetFromNil

`func (o *CycleStageHistoryInner) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *CycleStageHistoryInner) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil
### GetIntake

`func (o *CycleStageHistoryInner) GetIntake() CycleStageHistoryInnerIntake`

GetIntake returns the Intake field if non-nil, zero value otherwise.

### GetIntakeOk

`func (o *CycleStageHistoryInner) GetIntakeOk() (*CycleStageHistoryInnerIntake, bool)`

GetIntakeOk returns a tuple with the Intake field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntake

`func (o *CycleStageHistoryInner) SetIntake(v CycleStageHistoryInnerIntake)`

SetIntake sets Intake field to given value.

### HasIntake

`func (o *CycleStageHistoryInner) HasIntake() bool`

HasIntake returns a boolean if a field has been set.

### GetReason

`func (o *CycleStageHistoryInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CycleStageHistoryInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CycleStageHistoryInner) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CycleStageHistoryInner) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetRuleSetVersion

`func (o *CycleStageHistoryInner) GetRuleSetVersion() string`

GetRuleSetVersion returns the RuleSetVersion field if non-nil, zero value otherwise.

### GetRuleSetVersionOk

`func (o *CycleStageHistoryInner) GetRuleSetVersionOk() (*string, bool)`

GetRuleSetVersionOk returns a tuple with the RuleSetVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuleSetVersion

`func (o *CycleStageHistoryInner) SetRuleSetVersion(v string)`

SetRuleSetVersion sets RuleSetVersion field to given value.


### GetTo

`func (o *CycleStageHistoryInner) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CycleStageHistoryInner) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CycleStageHistoryInner) SetTo(v string)`

SetTo sets To field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


