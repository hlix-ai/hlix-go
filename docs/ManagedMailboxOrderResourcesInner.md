# ManagedMailboxOrderResourcesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **NullableString** |  |
**AuthorizationStatus** | **string** |  |
**CancellationRequested** | **bool** |  |
**ConnectionStatus** | **string** |  |
**Domain** | **string** |  |
**HostingStatus** | **string** |  |
**Id** | **string** |  |
**IssueCode** | **NullableString** |  |
**Kind** | **string** |  |
**MailboxId** | **NullableString** |  |
**OrderId** | **string** |  |
**RenewalCycle** | **NullableString** |  |
**RenewalDate** | **NullableString** |  |
**SendEligible** | **bool** |  |
**WarmupStatus** | **string** |  |

## Methods

### NewManagedMailboxOrderResourcesInner

`func NewManagedMailboxOrderResourcesInner(address NullableString, authorizationStatus string, cancellationRequested bool, connectionStatus string, domain string, hostingStatus string, id string, issueCode NullableString, kind string, mailboxId NullableString, orderId string, renewalCycle NullableString, renewalDate NullableString, sendEligible bool, warmupStatus string, ) *ManagedMailboxOrderResourcesInner`

NewManagedMailboxOrderResourcesInner instantiates a new ManagedMailboxOrderResourcesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewManagedMailboxOrderResourcesInnerWithDefaults

`func NewManagedMailboxOrderResourcesInnerWithDefaults() *ManagedMailboxOrderResourcesInner`

NewManagedMailboxOrderResourcesInnerWithDefaults instantiates a new ManagedMailboxOrderResourcesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAddress

`func (o *ManagedMailboxOrderResourcesInner) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ManagedMailboxOrderResourcesInner) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ManagedMailboxOrderResourcesInner) SetAddress(v string)`

SetAddress sets Address field to given value.


### SetAddressNil

`func (o *ManagedMailboxOrderResourcesInner) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ManagedMailboxOrderResourcesInner) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetAuthorizationStatus

`func (o *ManagedMailboxOrderResourcesInner) GetAuthorizationStatus() string`

GetAuthorizationStatus returns the AuthorizationStatus field if non-nil, zero value otherwise.

### GetAuthorizationStatusOk

`func (o *ManagedMailboxOrderResourcesInner) GetAuthorizationStatusOk() (*string, bool)`

GetAuthorizationStatusOk returns a tuple with the AuthorizationStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationStatus

`func (o *ManagedMailboxOrderResourcesInner) SetAuthorizationStatus(v string)`

SetAuthorizationStatus sets AuthorizationStatus field to given value.


### GetCancellationRequested

`func (o *ManagedMailboxOrderResourcesInner) GetCancellationRequested() bool`

GetCancellationRequested returns the CancellationRequested field if non-nil, zero value otherwise.

### GetCancellationRequestedOk

`func (o *ManagedMailboxOrderResourcesInner) GetCancellationRequestedOk() (*bool, bool)`

GetCancellationRequestedOk returns a tuple with the CancellationRequested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancellationRequested

`func (o *ManagedMailboxOrderResourcesInner) SetCancellationRequested(v bool)`

SetCancellationRequested sets CancellationRequested field to given value.


### GetConnectionStatus

`func (o *ManagedMailboxOrderResourcesInner) GetConnectionStatus() string`

GetConnectionStatus returns the ConnectionStatus field if non-nil, zero value otherwise.

### GetConnectionStatusOk

`func (o *ManagedMailboxOrderResourcesInner) GetConnectionStatusOk() (*string, bool)`

GetConnectionStatusOk returns a tuple with the ConnectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatus

`func (o *ManagedMailboxOrderResourcesInner) SetConnectionStatus(v string)`

SetConnectionStatus sets ConnectionStatus field to given value.


### GetDomain

`func (o *ManagedMailboxOrderResourcesInner) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ManagedMailboxOrderResourcesInner) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ManagedMailboxOrderResourcesInner) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetHostingStatus

`func (o *ManagedMailboxOrderResourcesInner) GetHostingStatus() string`

GetHostingStatus returns the HostingStatus field if non-nil, zero value otherwise.

### GetHostingStatusOk

`func (o *ManagedMailboxOrderResourcesInner) GetHostingStatusOk() (*string, bool)`

GetHostingStatusOk returns a tuple with the HostingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostingStatus

`func (o *ManagedMailboxOrderResourcesInner) SetHostingStatus(v string)`

SetHostingStatus sets HostingStatus field to given value.


### GetId

`func (o *ManagedMailboxOrderResourcesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedMailboxOrderResourcesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedMailboxOrderResourcesInner) SetId(v string)`

SetId sets Id field to given value.


### GetIssueCode

`func (o *ManagedMailboxOrderResourcesInner) GetIssueCode() string`

GetIssueCode returns the IssueCode field if non-nil, zero value otherwise.

### GetIssueCodeOk

`func (o *ManagedMailboxOrderResourcesInner) GetIssueCodeOk() (*string, bool)`

GetIssueCodeOk returns a tuple with the IssueCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueCode

`func (o *ManagedMailboxOrderResourcesInner) SetIssueCode(v string)`

SetIssueCode sets IssueCode field to given value.


### SetIssueCodeNil

`func (o *ManagedMailboxOrderResourcesInner) SetIssueCodeNil(b bool)`

 SetIssueCodeNil sets the value for IssueCode to be an explicit nil

### UnsetIssueCode
`func (o *ManagedMailboxOrderResourcesInner) UnsetIssueCode()`

UnsetIssueCode ensures that no value is present for IssueCode, not even an explicit nil
### GetKind

`func (o *ManagedMailboxOrderResourcesInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ManagedMailboxOrderResourcesInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ManagedMailboxOrderResourcesInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetMailboxId

`func (o *ManagedMailboxOrderResourcesInner) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *ManagedMailboxOrderResourcesInner) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *ManagedMailboxOrderResourcesInner) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.


### SetMailboxIdNil

`func (o *ManagedMailboxOrderResourcesInner) SetMailboxIdNil(b bool)`

 SetMailboxIdNil sets the value for MailboxId to be an explicit nil

### UnsetMailboxId
`func (o *ManagedMailboxOrderResourcesInner) UnsetMailboxId()`

UnsetMailboxId ensures that no value is present for MailboxId, not even an explicit nil
### GetOrderId

`func (o *ManagedMailboxOrderResourcesInner) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *ManagedMailboxOrderResourcesInner) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *ManagedMailboxOrderResourcesInner) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.


### GetRenewalCycle

`func (o *ManagedMailboxOrderResourcesInner) GetRenewalCycle() string`

GetRenewalCycle returns the RenewalCycle field if non-nil, zero value otherwise.

### GetRenewalCycleOk

`func (o *ManagedMailboxOrderResourcesInner) GetRenewalCycleOk() (*string, bool)`

GetRenewalCycleOk returns a tuple with the RenewalCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalCycle

`func (o *ManagedMailboxOrderResourcesInner) SetRenewalCycle(v string)`

SetRenewalCycle sets RenewalCycle field to given value.


### SetRenewalCycleNil

`func (o *ManagedMailboxOrderResourcesInner) SetRenewalCycleNil(b bool)`

 SetRenewalCycleNil sets the value for RenewalCycle to be an explicit nil

### UnsetRenewalCycle
`func (o *ManagedMailboxOrderResourcesInner) UnsetRenewalCycle()`

UnsetRenewalCycle ensures that no value is present for RenewalCycle, not even an explicit nil
### GetRenewalDate

`func (o *ManagedMailboxOrderResourcesInner) GetRenewalDate() string`

GetRenewalDate returns the RenewalDate field if non-nil, zero value otherwise.

### GetRenewalDateOk

`func (o *ManagedMailboxOrderResourcesInner) GetRenewalDateOk() (*string, bool)`

GetRenewalDateOk returns a tuple with the RenewalDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalDate

`func (o *ManagedMailboxOrderResourcesInner) SetRenewalDate(v string)`

SetRenewalDate sets RenewalDate field to given value.


### SetRenewalDateNil

`func (o *ManagedMailboxOrderResourcesInner) SetRenewalDateNil(b bool)`

 SetRenewalDateNil sets the value for RenewalDate to be an explicit nil

### UnsetRenewalDate
`func (o *ManagedMailboxOrderResourcesInner) UnsetRenewalDate()`

UnsetRenewalDate ensures that no value is present for RenewalDate, not even an explicit nil
### GetSendEligible

`func (o *ManagedMailboxOrderResourcesInner) GetSendEligible() bool`

GetSendEligible returns the SendEligible field if non-nil, zero value otherwise.

### GetSendEligibleOk

`func (o *ManagedMailboxOrderResourcesInner) GetSendEligibleOk() (*bool, bool)`

GetSendEligibleOk returns a tuple with the SendEligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendEligible

`func (o *ManagedMailboxOrderResourcesInner) SetSendEligible(v bool)`

SetSendEligible sets SendEligible field to given value.


### GetWarmupStatus

`func (o *ManagedMailboxOrderResourcesInner) GetWarmupStatus() string`

GetWarmupStatus returns the WarmupStatus field if non-nil, zero value otherwise.

### GetWarmupStatusOk

`func (o *ManagedMailboxOrderResourcesInner) GetWarmupStatusOk() (*string, bool)`

GetWarmupStatusOk returns a tuple with the WarmupStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmupStatus

`func (o *ManagedMailboxOrderResourcesInner) SetWarmupStatus(v string)`

SetWarmupStatus sets WarmupStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


