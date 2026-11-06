# BonusClaim

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**CreditMicros** | **int64** |  | 

## Methods

### NewBonusClaim

`func NewBonusClaim(action string, creditMicros int64, ) *BonusClaim`

NewBonusClaim instantiates a new BonusClaim object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBonusClaimWithDefaults

`func NewBonusClaimWithDefaults() *BonusClaim`

NewBonusClaimWithDefaults instantiates a new BonusClaim object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *BonusClaim) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *BonusClaim) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *BonusClaim) SetAction(v string)`

SetAction sets Action field to given value.


### GetCreditMicros

`func (o *BonusClaim) GetCreditMicros() int64`

GetCreditMicros returns the CreditMicros field if non-nil, zero value otherwise.

### GetCreditMicrosOk

`func (o *BonusClaim) GetCreditMicrosOk() (*int64, bool)`

GetCreditMicrosOk returns a tuple with the CreditMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditMicros

`func (o *BonusClaim) SetCreditMicros(v int64)`

SetCreditMicros sets CreditMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


