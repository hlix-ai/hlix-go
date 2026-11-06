# OrgBillingStateEntitlement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** |  | 
**Subscription** | [**OrgBillingStateEntitlementAnyOf1Subscription**](OrgBillingStateEntitlementAnyOf1Subscription.md) |  | 
**Credit** | [**OrgBillingStateEntitlementAnyOf2Credit**](OrgBillingStateEntitlementAnyOf2Credit.md) |  | 
**OrgCapOnlyMillicents** | **float32** |  | 
**Reason** | **string** |  | 

## Methods

### NewOrgBillingStateEntitlement

`func NewOrgBillingStateEntitlement(kind string, subscription OrgBillingStateEntitlementAnyOf1Subscription, credit OrgBillingStateEntitlementAnyOf2Credit, orgCapOnlyMillicents float32, reason string, ) *OrgBillingStateEntitlement`

NewOrgBillingStateEntitlement instantiates a new OrgBillingStateEntitlement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgBillingStateEntitlementWithDefaults

`func NewOrgBillingStateEntitlementWithDefaults() *OrgBillingStateEntitlement`

NewOrgBillingStateEntitlementWithDefaults instantiates a new OrgBillingStateEntitlement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *OrgBillingStateEntitlement) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *OrgBillingStateEntitlement) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *OrgBillingStateEntitlement) SetKind(v string)`

SetKind sets Kind field to given value.


### GetSubscription

`func (o *OrgBillingStateEntitlement) GetSubscription() OrgBillingStateEntitlementAnyOf1Subscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *OrgBillingStateEntitlement) GetSubscriptionOk() (*OrgBillingStateEntitlementAnyOf1Subscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *OrgBillingStateEntitlement) SetSubscription(v OrgBillingStateEntitlementAnyOf1Subscription)`

SetSubscription sets Subscription field to given value.


### GetCredit

`func (o *OrgBillingStateEntitlement) GetCredit() OrgBillingStateEntitlementAnyOf2Credit`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *OrgBillingStateEntitlement) GetCreditOk() (*OrgBillingStateEntitlementAnyOf2Credit, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *OrgBillingStateEntitlement) SetCredit(v OrgBillingStateEntitlementAnyOf2Credit)`

SetCredit sets Credit field to given value.


### GetOrgCapOnlyMillicents

`func (o *OrgBillingStateEntitlement) GetOrgCapOnlyMillicents() float32`

GetOrgCapOnlyMillicents returns the OrgCapOnlyMillicents field if non-nil, zero value otherwise.

### GetOrgCapOnlyMillicentsOk

`func (o *OrgBillingStateEntitlement) GetOrgCapOnlyMillicentsOk() (*float32, bool)`

GetOrgCapOnlyMillicentsOk returns a tuple with the OrgCapOnlyMillicents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrgCapOnlyMillicents

`func (o *OrgBillingStateEntitlement) SetOrgCapOnlyMillicents(v float32)`

SetOrgCapOnlyMillicents sets OrgCapOnlyMillicents field to given value.


### GetReason

`func (o *OrgBillingStateEntitlement) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *OrgBillingStateEntitlement) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *OrgBillingStateEntitlement) SetReason(v string)`

SetReason sets Reason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


