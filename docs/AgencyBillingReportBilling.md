# AgencyBillingReportBilling

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AverageDaysToPayment** | **NullableFloat32** |  | 
**Collected** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Drafts** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Issued** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Outstanding** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Overdue** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**OverdueAging** | [**AgencyBillingReportBillingOverdueAging**](AgencyBillingReportBillingOverdueAging.md) |  | 
**Unbilled** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 

## Methods

### NewAgencyBillingReportBilling

`func NewAgencyBillingReportBilling(averageDaysToPayment NullableFloat32, collected []AgencyBillingReportBillingCollectedInner, drafts []AgencyBillingReportBillingCollectedInner, issued []AgencyBillingReportBillingCollectedInner, outstanding []AgencyBillingReportBillingCollectedInner, overdue []AgencyBillingReportBillingCollectedInner, overdueAging AgencyBillingReportBillingOverdueAging, unbilled []AgencyBillingReportBillingCollectedInner, ) *AgencyBillingReportBilling`

NewAgencyBillingReportBilling instantiates a new AgencyBillingReportBilling object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgencyBillingReportBillingWithDefaults

`func NewAgencyBillingReportBillingWithDefaults() *AgencyBillingReportBilling`

NewAgencyBillingReportBillingWithDefaults instantiates a new AgencyBillingReportBilling object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAverageDaysToPayment

`func (o *AgencyBillingReportBilling) GetAverageDaysToPayment() float32`

GetAverageDaysToPayment returns the AverageDaysToPayment field if non-nil, zero value otherwise.

### GetAverageDaysToPaymentOk

`func (o *AgencyBillingReportBilling) GetAverageDaysToPaymentOk() (*float32, bool)`

GetAverageDaysToPaymentOk returns a tuple with the AverageDaysToPayment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageDaysToPayment

`func (o *AgencyBillingReportBilling) SetAverageDaysToPayment(v float32)`

SetAverageDaysToPayment sets AverageDaysToPayment field to given value.


### SetAverageDaysToPaymentNil

`func (o *AgencyBillingReportBilling) SetAverageDaysToPaymentNil(b bool)`

 SetAverageDaysToPaymentNil sets the value for AverageDaysToPayment to be an explicit nil

### UnsetAverageDaysToPayment
`func (o *AgencyBillingReportBilling) UnsetAverageDaysToPayment()`

UnsetAverageDaysToPayment ensures that no value is present for AverageDaysToPayment, not even an explicit nil
### GetCollected

`func (o *AgencyBillingReportBilling) GetCollected() []AgencyBillingReportBillingCollectedInner`

GetCollected returns the Collected field if non-nil, zero value otherwise.

### GetCollectedOk

`func (o *AgencyBillingReportBilling) GetCollectedOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetCollectedOk returns a tuple with the Collected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollected

`func (o *AgencyBillingReportBilling) SetCollected(v []AgencyBillingReportBillingCollectedInner)`

SetCollected sets Collected field to given value.


### GetDrafts

`func (o *AgencyBillingReportBilling) GetDrafts() []AgencyBillingReportBillingCollectedInner`

GetDrafts returns the Drafts field if non-nil, zero value otherwise.

### GetDraftsOk

`func (o *AgencyBillingReportBilling) GetDraftsOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetDraftsOk returns a tuple with the Drafts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDrafts

`func (o *AgencyBillingReportBilling) SetDrafts(v []AgencyBillingReportBillingCollectedInner)`

SetDrafts sets Drafts field to given value.


### GetIssued

`func (o *AgencyBillingReportBilling) GetIssued() []AgencyBillingReportBillingCollectedInner`

GetIssued returns the Issued field if non-nil, zero value otherwise.

### GetIssuedOk

`func (o *AgencyBillingReportBilling) GetIssuedOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetIssuedOk returns a tuple with the Issued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssued

`func (o *AgencyBillingReportBilling) SetIssued(v []AgencyBillingReportBillingCollectedInner)`

SetIssued sets Issued field to given value.


### GetOutstanding

`func (o *AgencyBillingReportBilling) GetOutstanding() []AgencyBillingReportBillingCollectedInner`

GetOutstanding returns the Outstanding field if non-nil, zero value otherwise.

### GetOutstandingOk

`func (o *AgencyBillingReportBilling) GetOutstandingOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetOutstandingOk returns a tuple with the Outstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutstanding

`func (o *AgencyBillingReportBilling) SetOutstanding(v []AgencyBillingReportBillingCollectedInner)`

SetOutstanding sets Outstanding field to given value.


### GetOverdue

`func (o *AgencyBillingReportBilling) GetOverdue() []AgencyBillingReportBillingCollectedInner`

GetOverdue returns the Overdue field if non-nil, zero value otherwise.

### GetOverdueOk

`func (o *AgencyBillingReportBilling) GetOverdueOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetOverdueOk returns a tuple with the Overdue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverdue

`func (o *AgencyBillingReportBilling) SetOverdue(v []AgencyBillingReportBillingCollectedInner)`

SetOverdue sets Overdue field to given value.


### GetOverdueAging

`func (o *AgencyBillingReportBilling) GetOverdueAging() AgencyBillingReportBillingOverdueAging`

GetOverdueAging returns the OverdueAging field if non-nil, zero value otherwise.

### GetOverdueAgingOk

`func (o *AgencyBillingReportBilling) GetOverdueAgingOk() (*AgencyBillingReportBillingOverdueAging, bool)`

GetOverdueAgingOk returns a tuple with the OverdueAging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverdueAging

`func (o *AgencyBillingReportBilling) SetOverdueAging(v AgencyBillingReportBillingOverdueAging)`

SetOverdueAging sets OverdueAging field to given value.


### GetUnbilled

`func (o *AgencyBillingReportBilling) GetUnbilled() []AgencyBillingReportBillingCollectedInner`

GetUnbilled returns the Unbilled field if non-nil, zero value otherwise.

### GetUnbilledOk

`func (o *AgencyBillingReportBilling) GetUnbilledOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetUnbilledOk returns a tuple with the Unbilled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbilled

`func (o *AgencyBillingReportBilling) SetUnbilled(v []AgencyBillingReportBillingCollectedInner)`

SetUnbilled sets Unbilled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


