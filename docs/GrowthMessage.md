# GrowthMessage

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

### NewGrowthMessage

`func NewGrowthMessage(approvedAt NullableString, approvedByUserId NullableString, body string, chargeMicros NullableInt64, claimedAt NullableString, classification NullableString, createdAt string, deliveryUnknown bool, direction string, dueAt NullableString, error_ NullableString, facts []GrowthMessageFactsInner, fromEmail NullableString, heldReason NullableString, id string, internetMessageId NullableString, leadId NullableString, mailboxId NullableString, organizationId string, providerMessageId NullableString, sentAt NullableString, status string, step NullableInt32, subject NullableString, threadRef NullableString, ) *GrowthMessage`

NewGrowthMessage instantiates a new GrowthMessage object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthMessageWithDefaults

`func NewGrowthMessageWithDefaults() *GrowthMessage`

NewGrowthMessageWithDefaults instantiates a new GrowthMessage object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovedAt

`func (o *GrowthMessage) GetApprovedAt() string`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *GrowthMessage) GetApprovedAtOk() (*string, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *GrowthMessage) SetApprovedAt(v string)`

SetApprovedAt sets ApprovedAt field to given value.


### SetApprovedAtNil

`func (o *GrowthMessage) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *GrowthMessage) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedByUserId

`func (o *GrowthMessage) GetApprovedByUserId() string`

GetApprovedByUserId returns the ApprovedByUserId field if non-nil, zero value otherwise.

### GetApprovedByUserIdOk

`func (o *GrowthMessage) GetApprovedByUserIdOk() (*string, bool)`

GetApprovedByUserIdOk returns a tuple with the ApprovedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedByUserId

`func (o *GrowthMessage) SetApprovedByUserId(v string)`

SetApprovedByUserId sets ApprovedByUserId field to given value.


### SetApprovedByUserIdNil

`func (o *GrowthMessage) SetApprovedByUserIdNil(b bool)`

 SetApprovedByUserIdNil sets the value for ApprovedByUserId to be an explicit nil

### UnsetApprovedByUserId
`func (o *GrowthMessage) UnsetApprovedByUserId()`

UnsetApprovedByUserId ensures that no value is present for ApprovedByUserId, not even an explicit nil
### GetBody

`func (o *GrowthMessage) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *GrowthMessage) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *GrowthMessage) SetBody(v string)`

SetBody sets Body field to given value.


### GetChargeMicros

`func (o *GrowthMessage) GetChargeMicros() int64`

GetChargeMicros returns the ChargeMicros field if non-nil, zero value otherwise.

### GetChargeMicrosOk

`func (o *GrowthMessage) GetChargeMicrosOk() (*int64, bool)`

GetChargeMicrosOk returns a tuple with the ChargeMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChargeMicros

`func (o *GrowthMessage) SetChargeMicros(v int64)`

SetChargeMicros sets ChargeMicros field to given value.


### SetChargeMicrosNil

`func (o *GrowthMessage) SetChargeMicrosNil(b bool)`

 SetChargeMicrosNil sets the value for ChargeMicros to be an explicit nil

### UnsetChargeMicros
`func (o *GrowthMessage) UnsetChargeMicros()`

UnsetChargeMicros ensures that no value is present for ChargeMicros, not even an explicit nil
### GetClaimedAt

`func (o *GrowthMessage) GetClaimedAt() string`

GetClaimedAt returns the ClaimedAt field if non-nil, zero value otherwise.

### GetClaimedAtOk

`func (o *GrowthMessage) GetClaimedAtOk() (*string, bool)`

GetClaimedAtOk returns a tuple with the ClaimedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimedAt

`func (o *GrowthMessage) SetClaimedAt(v string)`

SetClaimedAt sets ClaimedAt field to given value.


### SetClaimedAtNil

`func (o *GrowthMessage) SetClaimedAtNil(b bool)`

 SetClaimedAtNil sets the value for ClaimedAt to be an explicit nil

### UnsetClaimedAt
`func (o *GrowthMessage) UnsetClaimedAt()`

UnsetClaimedAt ensures that no value is present for ClaimedAt, not even an explicit nil
### GetClassification

`func (o *GrowthMessage) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *GrowthMessage) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *GrowthMessage) SetClassification(v string)`

SetClassification sets Classification field to given value.


### SetClassificationNil

`func (o *GrowthMessage) SetClassificationNil(b bool)`

 SetClassificationNil sets the value for Classification to be an explicit nil

### UnsetClassification
`func (o *GrowthMessage) UnsetClassification()`

UnsetClassification ensures that no value is present for Classification, not even an explicit nil
### GetCreatedAt

`func (o *GrowthMessage) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthMessage) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthMessage) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeliveryUnknown

`func (o *GrowthMessage) GetDeliveryUnknown() bool`

GetDeliveryUnknown returns the DeliveryUnknown field if non-nil, zero value otherwise.

### GetDeliveryUnknownOk

`func (o *GrowthMessage) GetDeliveryUnknownOk() (*bool, bool)`

GetDeliveryUnknownOk returns a tuple with the DeliveryUnknown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryUnknown

`func (o *GrowthMessage) SetDeliveryUnknown(v bool)`

SetDeliveryUnknown sets DeliveryUnknown field to given value.


### GetDirection

`func (o *GrowthMessage) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *GrowthMessage) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *GrowthMessage) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetDueAt

`func (o *GrowthMessage) GetDueAt() string`

GetDueAt returns the DueAt field if non-nil, zero value otherwise.

### GetDueAtOk

`func (o *GrowthMessage) GetDueAtOk() (*string, bool)`

GetDueAtOk returns a tuple with the DueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueAt

`func (o *GrowthMessage) SetDueAt(v string)`

SetDueAt sets DueAt field to given value.


### SetDueAtNil

`func (o *GrowthMessage) SetDueAtNil(b bool)`

 SetDueAtNil sets the value for DueAt to be an explicit nil

### UnsetDueAt
`func (o *GrowthMessage) UnsetDueAt()`

UnsetDueAt ensures that no value is present for DueAt, not even an explicit nil
### GetError

`func (o *GrowthMessage) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GrowthMessage) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GrowthMessage) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *GrowthMessage) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *GrowthMessage) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFacts

`func (o *GrowthMessage) GetFacts() []GrowthMessageFactsInner`

GetFacts returns the Facts field if non-nil, zero value otherwise.

### GetFactsOk

`func (o *GrowthMessage) GetFactsOk() (*[]GrowthMessageFactsInner, bool)`

GetFactsOk returns a tuple with the Facts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacts

`func (o *GrowthMessage) SetFacts(v []GrowthMessageFactsInner)`

SetFacts sets Facts field to given value.


### GetFromEmail

`func (o *GrowthMessage) GetFromEmail() string`

GetFromEmail returns the FromEmail field if non-nil, zero value otherwise.

### GetFromEmailOk

`func (o *GrowthMessage) GetFromEmailOk() (*string, bool)`

GetFromEmailOk returns a tuple with the FromEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromEmail

`func (o *GrowthMessage) SetFromEmail(v string)`

SetFromEmail sets FromEmail field to given value.


### SetFromEmailNil

`func (o *GrowthMessage) SetFromEmailNil(b bool)`

 SetFromEmailNil sets the value for FromEmail to be an explicit nil

### UnsetFromEmail
`func (o *GrowthMessage) UnsetFromEmail()`

UnsetFromEmail ensures that no value is present for FromEmail, not even an explicit nil
### GetHeldReason

`func (o *GrowthMessage) GetHeldReason() string`

GetHeldReason returns the HeldReason field if non-nil, zero value otherwise.

### GetHeldReasonOk

`func (o *GrowthMessage) GetHeldReasonOk() (*string, bool)`

GetHeldReasonOk returns a tuple with the HeldReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeldReason

`func (o *GrowthMessage) SetHeldReason(v string)`

SetHeldReason sets HeldReason field to given value.


### SetHeldReasonNil

`func (o *GrowthMessage) SetHeldReasonNil(b bool)`

 SetHeldReasonNil sets the value for HeldReason to be an explicit nil

### UnsetHeldReason
`func (o *GrowthMessage) UnsetHeldReason()`

UnsetHeldReason ensures that no value is present for HeldReason, not even an explicit nil
### GetId

`func (o *GrowthMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthMessage) SetId(v string)`

SetId sets Id field to given value.


### GetInternetMessageId

`func (o *GrowthMessage) GetInternetMessageId() string`

GetInternetMessageId returns the InternetMessageId field if non-nil, zero value otherwise.

### GetInternetMessageIdOk

`func (o *GrowthMessage) GetInternetMessageIdOk() (*string, bool)`

GetInternetMessageIdOk returns a tuple with the InternetMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternetMessageId

`func (o *GrowthMessage) SetInternetMessageId(v string)`

SetInternetMessageId sets InternetMessageId field to given value.


### SetInternetMessageIdNil

`func (o *GrowthMessage) SetInternetMessageIdNil(b bool)`

 SetInternetMessageIdNil sets the value for InternetMessageId to be an explicit nil

### UnsetInternetMessageId
`func (o *GrowthMessage) UnsetInternetMessageId()`

UnsetInternetMessageId ensures that no value is present for InternetMessageId, not even an explicit nil
### GetLeadId

`func (o *GrowthMessage) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *GrowthMessage) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *GrowthMessage) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.


### SetLeadIdNil

`func (o *GrowthMessage) SetLeadIdNil(b bool)`

 SetLeadIdNil sets the value for LeadId to be an explicit nil

### UnsetLeadId
`func (o *GrowthMessage) UnsetLeadId()`

UnsetLeadId ensures that no value is present for LeadId, not even an explicit nil
### GetMailboxId

`func (o *GrowthMessage) GetMailboxId() string`

GetMailboxId returns the MailboxId field if non-nil, zero value otherwise.

### GetMailboxIdOk

`func (o *GrowthMessage) GetMailboxIdOk() (*string, bool)`

GetMailboxIdOk returns a tuple with the MailboxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxId

`func (o *GrowthMessage) SetMailboxId(v string)`

SetMailboxId sets MailboxId field to given value.


### SetMailboxIdNil

`func (o *GrowthMessage) SetMailboxIdNil(b bool)`

 SetMailboxIdNil sets the value for MailboxId to be an explicit nil

### UnsetMailboxId
`func (o *GrowthMessage) UnsetMailboxId()`

UnsetMailboxId ensures that no value is present for MailboxId, not even an explicit nil
### GetOrganizationId

`func (o *GrowthMessage) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthMessage) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthMessage) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProviderMessageId

`func (o *GrowthMessage) GetProviderMessageId() string`

GetProviderMessageId returns the ProviderMessageId field if non-nil, zero value otherwise.

### GetProviderMessageIdOk

`func (o *GrowthMessage) GetProviderMessageIdOk() (*string, bool)`

GetProviderMessageIdOk returns a tuple with the ProviderMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderMessageId

`func (o *GrowthMessage) SetProviderMessageId(v string)`

SetProviderMessageId sets ProviderMessageId field to given value.


### SetProviderMessageIdNil

`func (o *GrowthMessage) SetProviderMessageIdNil(b bool)`

 SetProviderMessageIdNil sets the value for ProviderMessageId to be an explicit nil

### UnsetProviderMessageId
`func (o *GrowthMessage) UnsetProviderMessageId()`

UnsetProviderMessageId ensures that no value is present for ProviderMessageId, not even an explicit nil
### GetSentAt

`func (o *GrowthMessage) GetSentAt() string`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *GrowthMessage) GetSentAtOk() (*string, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *GrowthMessage) SetSentAt(v string)`

SetSentAt sets SentAt field to given value.


### SetSentAtNil

`func (o *GrowthMessage) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *GrowthMessage) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetStatus

`func (o *GrowthMessage) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthMessage) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthMessage) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStep

`func (o *GrowthMessage) GetStep() int32`

GetStep returns the Step field if non-nil, zero value otherwise.

### GetStepOk

`func (o *GrowthMessage) GetStepOk() (*int32, bool)`

GetStepOk returns a tuple with the Step field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStep

`func (o *GrowthMessage) SetStep(v int32)`

SetStep sets Step field to given value.


### SetStepNil

`func (o *GrowthMessage) SetStepNil(b bool)`

 SetStepNil sets the value for Step to be an explicit nil

### UnsetStep
`func (o *GrowthMessage) UnsetStep()`

UnsetStep ensures that no value is present for Step, not even an explicit nil
### GetSubject

`func (o *GrowthMessage) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *GrowthMessage) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *GrowthMessage) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *GrowthMessage) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *GrowthMessage) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetThreadRef

`func (o *GrowthMessage) GetThreadRef() string`

GetThreadRef returns the ThreadRef field if non-nil, zero value otherwise.

### GetThreadRefOk

`func (o *GrowthMessage) GetThreadRefOk() (*string, bool)`

GetThreadRefOk returns a tuple with the ThreadRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadRef

`func (o *GrowthMessage) SetThreadRef(v string)`

SetThreadRef sets ThreadRef field to given value.


### SetThreadRefNil

`func (o *GrowthMessage) SetThreadRefNil(b bool)`

 SetThreadRefNil sets the value for ThreadRef to be an explicit nil

### UnsetThreadRef
`func (o *GrowthMessage) UnsetThreadRef()`

UnsetThreadRef ensures that no value is present for ThreadRef, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


