# ProjectTaskCharges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingMode** | **string** |  | 
**Charges** | [**[]ProjectTaskChargesChargesInner**](ProjectTaskChargesChargesInner.md) |  | 
**CreditsBySize** | [**NullableProjectTaskChargesCreditsBySize**](ProjectTaskChargesCreditsBySize.md) |  | 
**CreditsPerTask** | **float32** |  | 
**FreeReworkRounds** | **int32** |  | 
**ReviewRounds** | [**[]ProjectTaskChargesReviewRoundsInner**](ProjectTaskChargesReviewRoundsInner.md) |  | 
**TaskSizes** | [**[]ProjectTaskChargesTaskSizesInner**](ProjectTaskChargesTaskSizesInner.md) |  | 
**Tier** | **string** |  | 

## Methods

### NewProjectTaskCharges

`func NewProjectTaskCharges(billingMode string, charges []ProjectTaskChargesChargesInner, creditsBySize NullableProjectTaskChargesCreditsBySize, creditsPerTask float32, freeReworkRounds int32, reviewRounds []ProjectTaskChargesReviewRoundsInner, taskSizes []ProjectTaskChargesTaskSizesInner, tier string, ) *ProjectTaskCharges`

NewProjectTaskCharges instantiates a new ProjectTaskCharges object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectTaskChargesWithDefaults

`func NewProjectTaskChargesWithDefaults() *ProjectTaskCharges`

NewProjectTaskChargesWithDefaults instantiates a new ProjectTaskCharges object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillingMode

`func (o *ProjectTaskCharges) GetBillingMode() string`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *ProjectTaskCharges) GetBillingModeOk() (*string, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *ProjectTaskCharges) SetBillingMode(v string)`

SetBillingMode sets BillingMode field to given value.


### GetCharges

`func (o *ProjectTaskCharges) GetCharges() []ProjectTaskChargesChargesInner`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *ProjectTaskCharges) GetChargesOk() (*[]ProjectTaskChargesChargesInner, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *ProjectTaskCharges) SetCharges(v []ProjectTaskChargesChargesInner)`

SetCharges sets Charges field to given value.


### GetCreditsBySize

`func (o *ProjectTaskCharges) GetCreditsBySize() ProjectTaskChargesCreditsBySize`

GetCreditsBySize returns the CreditsBySize field if non-nil, zero value otherwise.

### GetCreditsBySizeOk

`func (o *ProjectTaskCharges) GetCreditsBySizeOk() (*ProjectTaskChargesCreditsBySize, bool)`

GetCreditsBySizeOk returns a tuple with the CreditsBySize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsBySize

`func (o *ProjectTaskCharges) SetCreditsBySize(v ProjectTaskChargesCreditsBySize)`

SetCreditsBySize sets CreditsBySize field to given value.


### SetCreditsBySizeNil

`func (o *ProjectTaskCharges) SetCreditsBySizeNil(b bool)`

 SetCreditsBySizeNil sets the value for CreditsBySize to be an explicit nil

### UnsetCreditsBySize
`func (o *ProjectTaskCharges) UnsetCreditsBySize()`

UnsetCreditsBySize ensures that no value is present for CreditsBySize, not even an explicit nil
### GetCreditsPerTask

`func (o *ProjectTaskCharges) GetCreditsPerTask() float32`

GetCreditsPerTask returns the CreditsPerTask field if non-nil, zero value otherwise.

### GetCreditsPerTaskOk

`func (o *ProjectTaskCharges) GetCreditsPerTaskOk() (*float32, bool)`

GetCreditsPerTaskOk returns a tuple with the CreditsPerTask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsPerTask

`func (o *ProjectTaskCharges) SetCreditsPerTask(v float32)`

SetCreditsPerTask sets CreditsPerTask field to given value.


### GetFreeReworkRounds

`func (o *ProjectTaskCharges) GetFreeReworkRounds() int32`

GetFreeReworkRounds returns the FreeReworkRounds field if non-nil, zero value otherwise.

### GetFreeReworkRoundsOk

`func (o *ProjectTaskCharges) GetFreeReworkRoundsOk() (*int32, bool)`

GetFreeReworkRoundsOk returns a tuple with the FreeReworkRounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeReworkRounds

`func (o *ProjectTaskCharges) SetFreeReworkRounds(v int32)`

SetFreeReworkRounds sets FreeReworkRounds field to given value.


### GetReviewRounds

`func (o *ProjectTaskCharges) GetReviewRounds() []ProjectTaskChargesReviewRoundsInner`

GetReviewRounds returns the ReviewRounds field if non-nil, zero value otherwise.

### GetReviewRoundsOk

`func (o *ProjectTaskCharges) GetReviewRoundsOk() (*[]ProjectTaskChargesReviewRoundsInner, bool)`

GetReviewRoundsOk returns a tuple with the ReviewRounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewRounds

`func (o *ProjectTaskCharges) SetReviewRounds(v []ProjectTaskChargesReviewRoundsInner)`

SetReviewRounds sets ReviewRounds field to given value.


### GetTaskSizes

`func (o *ProjectTaskCharges) GetTaskSizes() []ProjectTaskChargesTaskSizesInner`

GetTaskSizes returns the TaskSizes field if non-nil, zero value otherwise.

### GetTaskSizesOk

`func (o *ProjectTaskCharges) GetTaskSizesOk() (*[]ProjectTaskChargesTaskSizesInner, bool)`

GetTaskSizesOk returns a tuple with the TaskSizes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskSizes

`func (o *ProjectTaskCharges) SetTaskSizes(v []ProjectTaskChargesTaskSizesInner)`

SetTaskSizes sets TaskSizes field to given value.


### GetTier

`func (o *ProjectTaskCharges) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *ProjectTaskCharges) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *ProjectTaskCharges) SetTier(v string)`

SetTier sets Tier field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


