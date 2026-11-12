# GrowthThreadMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovedAt** | **NullableString** |  |
**ApprovedByUserId** | **NullableString** |  |
**Body** | **string** |  |
**ChargeMicros** | **NullableInt64** |  |
**ClaimedAt** | **NullableString** |  |
**Classification** | **NullableString** |  |
**CreatedAt** | **string** |  |
**DeliveryUnknown** | **bool** |  |
**Direction** | **string** |  |
**DueAt** | **NullableString** |  |
**Error** | **NullableString** |  |
**Facts** | [**[]GrowthMessageFactsInner**](GrowthMessageFactsInner.md) |  |
**FromEmail** | **NullableString** |  |
**HeldReason** | **NullableString** |  |
**Id** | **string** |  |
**InternetMessageId** | **NullableString** |  |
**LeadId** | **NullableString** |  |
**MailboxId** | **NullableString** |  |
**OrganizationId** | **string** |  |
**ProviderMessageId** | **NullableString** |  |
**SentAt** | **NullableString** |  |
**Status** | **string** |  |
**Step** | **NullableInt32** |  |
**Subject** | **NullableString** |  |
**ThreadRef** | **NullableString** |  |

## Methods

### NewGrowthThreadMessagesInner

`func NewGrowthThreadMessagesInner(approvedAt NullableString, approvedByUserId NullableString, body string, chargeMicros NullableInt64, claimedAt NullableString, classification NullableString, createdAt string, deliveryUnknown bool, direction string, dueAt NullableString, error_ NullableString, facts []GrowthMessageFactsInner, fromEmail NullableString, heldReason NullableString, id string, internetMessageId NullableString, leadId NullableString, mailboxId NullableString, organizationId string, providerMessageId NullableString, sentAt NullableString, status string, step NullableInt32, subject NullableString, threadRef NullableString, ) *GrowthThreadMessagesInner`

NewGrowthThreadMessagesInner instantiates a new GrowthThreadMessagesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthThreadMessagesInnerWithDefaults

`func NewGrowthThreadMessagesInnerWithDefaults() *GrowthThreadMessagesInner`

NewGrowthThreadMessagesInnerWithDefaults instantiates a new GrowthThreadMessagesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovedAt

`func (o *GrowthThreadMessagesInner) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *GrowthThreadMessagesInner) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *GrowthThreadMessagesInner) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.


### SetApprovedAtNil

`func (o *GrowthThreadMessagesInner) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *GrowthThreadMessagesInner) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedByUserId

`func (o *GrowthThreadMessagesInner) GetApprovedByUserId() string`

GetApprovedByUserId returns the ApprovedByUserId field if non-nil, zero value otherwise.

### GetApprovedByUserIdOk

`func (o *GrowthThreadMessagesInner) GetApprovedByUserIdOk() (*string, bool)`

GetApprovedByUserIdOk returns a tuple with the ApprovedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedByUserId

`func (o *GrowthThreadMessagesInner) SetApprovedByUserId(v string)`

SetApprovedByUserId sets ApprovedByUserId field to given value.


### SetApprovedByUserIdNil

`func (o *GrowthThreadMessagesInner) SetApprovedByUserIdNil(b bool)`

 SetApprovedByUserIdNil sets the value for ApprovedByUserId to be an explicit nil

### UnsetApprovedByUserId
`func (o *GrowthThreadMessagesInner) UnsetApprovedByUserId()`

UnsetApprovedByUserId ensures that no value is present for ApprovedByUserId, not even an explicit nil
### GetBody

`func (o *GrowthThreadMessagesInner) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *GrowthThreadMessagesInner) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *GrowthThreadMessagesInner) SetBody(v string)`

SetBody sets Body field to given value.


### GetChargeMicros

`func (o *GrowthThreadMessagesInner) GetChargeMicros() int64`

GetChargeMicros returns the ChargeMicros field if non-nil, zero value otherwise.

### GetChargeMicrosOk

`func (o *GrowthThreadMessagesInner) GetChargeMicrosOk() (*int64, bool)`

GetChargeMicrosOk returns a tuple with the ChargeMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChargeMicros

`func (o *GrowthThreadMessagesInner) SetChargeMicros(v int64)`

SetChargeMicros sets ChargeMicros field to given value.


### SetChargeMicrosNil

`func (o *GrowthThreadMessagesInner) SetChargeMicrosNil(b bool)`

 SetChargeMicrosNil sets the value for ChargeMicros to be an explicit nil

### UnsetChargeMicros
`func (o *GrowthThreadMessagesInner) UnsetChargeMicros()`

UnsetChargeMicros ensures that no value is present for ChargeMicros, not even an explicit nil
### GetClaimedAt

`func (o *GrowthThreadMessagesInner) GetClaimedAt() string`

GetClaimedAt returns the ClaimedAt field if non-nil, zero value otherwise.

### GetClaimedAtOk

`func (o *GrowthThreadMessagesInner) GetClaimedAtOk() (*string, bool)`

GetClaimedAtOk returns a tuple with the ClaimedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedAt

`func (o *GrowthThreadMessagesInner) SetClaimedAt(v string)`

SetClaimedAt sets ClaimedAt field to given value.


### SetClaimedAtNil

`func (o *GrowthThreadMessagesInner) SetClaimedAtNil(b bool)`

 SetClaimedAtNil sets the value for ClaimedAt to be an explicit nil

### UnsetClaimedAt
`func (o *GrowthThreadMessagesInner) UnsetClaimedAt()`

UnsetClaimedAt ensures that no value is present for ClaimedAt, not even an explicit nil
### GetClassification

`func (o *GrowthThreadMessagesInner) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *GrowthThreadMessagesInner) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *GrowthThreadMessagesInner) SetClassification(v string)`

SetClassification sets Classification field to given value.


### SetClassificationNil

`func (o *GrowthThreadMessagesInner) SetClassificationNil(b bool)`

 SetClassificationNil sets the value for Classification to be an explicit nil

### UnsetClassification
`func (o *GrowthThreadMessagesInner) UnsetClassification()`

UnsetClassification ensures that no value is present for Classification, not even an explicit nil
### GetCreatedAt

`func (o *GrowthThreadMessagesInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthThreadMessagesInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthThreadMessagesInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeliveryUnknown

`func (o *GrowthThreadMessagesInner) GetDeliveryUnknown() bool`

GetDeliveryUnknown returns the DeliveryUnknown field if non-nil, zero value otherwise.

### GetDeliveryUnknownOk

`func (o *GrowthThreadMessagesInner) GetDeliveryUnknownOk() (*bool, bool)`

GetDeliveryUnknownOk returns a tuple with the DeliveryUnknown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryUnknown

`func (o *GrowthThreadMessagesInner) SetDeliveryUnknown(v bool)`

SetDeliveryUnknown sets DeliveryUnknown field to given value.


### GetDirection

`func (o *GrowthThreadMessagesInner) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *GrowthThreadMessagesInner) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *GrowthThreadMessagesInner) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetDueAt

`func (o *GrowthThreadMessagesInner) GetDueAt() string`

GetDueAt returns the DueAt field if non-nil, zero value otherwise.

### GetDueAtOk

`func (o *GrowthThreadMessagesInner) GetDueAtOk() (*string, bool)`

GetDueAtOk returns a tuple with the DueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueAt

`func (o *GrowthThreadMessagesInner) SetDueAt(v string)`

SetDueAt sets DueAt field to given value.


### SetDueAtNil

`func (o *GrowthThreadMessagesInner) SetDueAtNil(b bool)`

 SetDueAtNil sets the value for DueAt to be an explicit nil

### UnsetDueAt
`func (o *GrowthThreadMessagesInner) UnsetDueAt()`

UnsetDueAt ensures that no value is present for DueAt, not even an explicit nil
### GetError

`func (o *GrowthThreadMessagesInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GrowthThreadMessagesInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GrowthThreadMessagesInner) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *GrowthThreadMessagesInner) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GrowthThreadMessagesInner) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFacts

`func (o *GrowthThreadMessagesInner) GetFacts() []GrowthMessageFactsInner`

GetFacts returns the Facts field if non-nil, zero value otherwise.

### GetFactsOk

`func (o *GrowthThreadMessagesInner) GetFactsOk() (*[]GrowthMessageFactsInner, bool)`

GetFactsOk returns a tuple with the Facts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacts

`func (o *GrowthThreadMessagesInner) SetFacts(v []GrowthMessageFactsInner)`

SetFacts sets Facts field to given value.


### GetFromEmail

`func (o *GrowthThreadMessagesInner) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *GrowthThreadMessagesInner) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *GrowthThreadMessagesInner) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### SetFromEmailNil

`func (o *GrowthThreadMessagesInner) SetFromEmailNil(b bool)`

 SetFromEmailNil sets the value for FromEmail to be an explicit nil

### UnsetFromEmail
`func (o *GrowthThreadMessagesInner) UnsetFromEmail()`

UnsetFromEmail ensures that no value is present for FromEmail, not even an explicit nil
### GetHeldReason

`func (o *GrowthThreadMessagesInner) GetHeldReason() string`

GetHeldReason returns the HeldReason field if non-nil, zero value otherwise.

### GetHeldReasonOk

`func (o *GrowthThreadMessagesInner) GetHeldReasonOk() (*string, bool)`

GetHeldReasonOk returns a tuple with the HeldReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeldReason

`func (o *GrowthThreadMessagesInner) SetHeldReason(v string)`

SetHeldReason sets HeldReason field to given value.


### SetHeldReasonNil

`func (o *GrowthThreadMessagesInner) SetHeldReasonNil(b bool)`

 SetHeldReasonNil sets the value for HeldReason to be an explicit nil

### UnsetHeldReason
`func (o *GrowthThreadMessagesInner) UnsetHeldReason()`

UnsetHeldReason ensures that no value is present for HeldReason, not even an explicit nil
### GetId

`func (o *GrowthThreadMessagesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthThreadMessagesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthThreadMessagesInner) SetId(v string)`

SetId sets Id field to given value.


### GetInternetMessageId

`func (o *GrowthThreadMessagesInner) GetInternetMessageId() string`

GetInternetMessageId returns the InternetMessageId field if non-nil, zero value otherwise.

### GetInternetMessageIdOk

`func (o *GrowthThreadMessagesInner) GetInternetMessageIdOk() (*string, bool)`

GetInternetMessageIdOk returns a tuple with the InternetMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternetMessageId

`func (o *GrowthThreadMessagesInner) SetInternetMessageId(v string)`

SetInternetMessageId sets InternetMessageId field to given value.


### SetInternetMessageIdNil

`func (o *GrowthThreadMessagesInner) SetInternetMessageIdNil(b bool)`

 SetInternetMessageIdNil sets the value for InternetMessageId to be an explicit nil

### UnsetInternetMessageId
`func (o *GrowthThreadMessagesInner) UnsetInternetMessageId()`

UnsetInternetMessageId ensures that no value is present for InternetMessageId, not even an explicit nil
### GetLeadId

`func (o *GrowthThreadMessagesInner) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *GrowthThreadMessagesInner) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *GrowthThreadMessagesInner) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.


### SetLeadIdNil

`func (o *GrowthThreadMessagesInner) SetLeadIdNil(b bool)`

 SetLeadIdNil sets the value for LeadId to be an explicit nil

### UnsetLeadId
`func (o *GrowthThreadMessagesInner) UnsetLeadId()`

UnsetLeadId ensures that no value is present for LeadId, not even an explicit nil
### GetMailboxId

`func (o *GrowthThreadMessagesInner) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *GrowthThreadMessagesInner) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *GrowthThreadMessagesInner) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.


### SetMailboxIdNil

`func (o *GrowthThreadMessagesInner) SetMailboxIdNil(b bool)`

 SetMailboxIdNil sets the value for MailboxId to be an explicit nil

### UnsetMailboxId
`func (o *GrowthThreadMessagesInner) UnsetMailboxId()`

UnsetMailboxId ensures that no value is present for MailboxId, not even an explicit nil
### GetOrganizationId

`func (o *GrowthThreadMessagesInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthThreadMessagesInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthThreadMessagesInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProviderMessageId

`func (o *GrowthThreadMessagesInner) GetProviderMessageId() string`

GetProviderMessageId returns the ProviderMessageId field if non-nil, zero value otherwise.

### GetProviderMessageIdOk

`func (o *GrowthThreadMessagesInner) GetProviderMessageIdOk() (*string, bool)`

GetProviderMessageIdOk returns a tuple with the ProviderMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderMessageId

`func (o *GrowthThreadMessagesInner) SetProviderMessageId(v string)`

SetProviderMessageId sets ProviderMessageId field to given value.


### SetProviderMessageIdNil

`func (o *GrowthThreadMessagesInner) SetProviderMessageIdNil(b bool)`

 SetProviderMessageIdNil sets the value for ProviderMessageId to be an explicit nil

### UnsetProviderMessageId
`func (o *GrowthThreadMessagesInner) UnsetProviderMessageId()`

UnsetProviderMessageId ensures that no value is present for ProviderMessageId, not even an explicit nil
### GetSentAt

`func (o *GrowthThreadMessagesInner) GetSentAt() string`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *GrowthThreadMessagesInner) GetSentAtOk() (*string, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *GrowthThreadMessagesInner) SetSentAt(v string)`

SetSentAt sets SentAt field to given value.


### SetSentAtNil

`func (o *GrowthThreadMessagesInner) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *GrowthThreadMessagesInner) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetStatus

`func (o *GrowthThreadMessagesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthThreadMessagesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthThreadMessagesInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStep

`func (o *GrowthThreadMessagesInner) GetStep() int32`

GetStep returns the Step field if non-nil, zero value otherwise.

### GetStepOk

`func (o *GrowthThreadMessagesInner) GetStepOk() (*int32, bool)`

GetStepOk returns a tuple with the Step field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStep

`func (o *GrowthThreadMessagesInner) SetStep(v int32)`

SetStep sets Step field to given value.


### SetStepNil

`func (o *GrowthThreadMessagesInner) SetStepNil(b bool)`

 SetStepNil sets the value for Step to be an explicit nil

### UnsetStep
`func (o *GrowthThreadMessagesInner) UnsetStep()`

UnsetStep ensures that no value is present for Step, not even an explicit nil
### GetSubject

`func (o *GrowthThreadMessagesInner) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *GrowthThreadMessagesInner) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *GrowthThreadMessagesInner) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *GrowthThreadMessagesInner) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *GrowthThreadMessagesInner) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetThreadRef

`func (o *GrowthThreadMessagesInner) GetThreadRef() string`

GetThreadRef returns the ThreadRef field if non-nil, zero value otherwise.

### GetThreadRefOk

`func (o *GrowthThreadMessagesInner) GetThreadRefOk() (*string, bool)`

GetThreadRefOk returns a tuple with the ThreadRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadRef

`func (o *GrowthThreadMessagesInner) SetThreadRef(v string)`

SetThreadRef sets ThreadRef field to given value.


### SetThreadRefNil

`func (o *GrowthThreadMessagesInner) SetThreadRefNil(b bool)`

 SetThreadRefNil sets the value for ThreadRef to be an explicit nil

### UnsetThreadRef
`func (o *GrowthThreadMessagesInner) UnsetThreadRef()`

UnsetThreadRef ensures that no value is present for ThreadRef, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


