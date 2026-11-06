# CrmClientRecordConversationInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Campaign** | [**CrmClientRecordConversationInnerCampaign**](CrmClientRecordConversationInnerCampaign.md) |  | 
**ContactId** | **string** |  | 
**ContactName** | **string** |  | 
**LeadId** | **string** |  | 
**Messages** | [**[]CrmClientRecordConversationInnerMessagesInner**](CrmClientRecordConversationInnerMessagesInner.md) |  | 

## Methods

### NewCrmClientRecordConversationInner

`func NewCrmClientRecordConversationInner(campaign CrmClientRecordConversationInnerCampaign, contactId string, contactName string, leadId string, messages []CrmClientRecordConversationInnerMessagesInner, ) *CrmClientRecordConversationInner`

NewCrmClientRecordConversationInner instantiates a new CrmClientRecordConversationInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCrmClientRecordConversationInnerWithDefaults

`func NewCrmClientRecordConversationInnerWithDefaults() *CrmClientRecordConversationInner`

NewCrmClientRecordConversationInnerWithDefaults instantiates a new CrmClientRecordConversationInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCampaign

`func (o *CrmClientRecordConversationInner) GetCampaign() CrmClientRecordConversationInnerCampaign`

GetCampaign returns the Campaign field if non-nil, zero value otherwise.

### GetCampaignOk

`func (o *CrmClientRecordConversationInner) GetCampaignOk() (*CrmClientRecordConversationInnerCampaign, bool)`

GetCampaignOk returns a tuple with the Campaign field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaign

`func (o *CrmClientRecordConversationInner) SetCampaign(v CrmClientRecordConversationInnerCampaign)`

SetCampaign sets Campaign field to given value.


### GetContactId

`func (o *CrmClientRecordConversationInner) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *CrmClientRecordConversationInner) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *CrmClientRecordConversationInner) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetContactName

`func (o *CrmClientRecordConversationInner) GetContactName() string`

GetContactName returns the ContactName field if non-nil, zero value otherwise.

### GetContactNameOk

`func (o *CrmClientRecordConversationInner) GetContactNameOk() (*string, bool)`

GetContactNameOk returns a tuple with the ContactName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactName

`func (o *CrmClientRecordConversationInner) SetContactName(v string)`

SetContactName sets ContactName field to given value.


### GetLeadId

`func (o *CrmClientRecordConversationInner) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *CrmClientRecordConversationInner) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *CrmClientRecordConversationInner) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.


### GetMessages

`func (o *CrmClientRecordConversationInner) GetMessages() []CrmClientRecordConversationInnerMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *CrmClientRecordConversationInner) GetMessagesOk() (*[]CrmClientRecordConversationInnerMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *CrmClientRecordConversationInner) SetMessages(v []CrmClientRecordConversationInnerMessagesInner)`

SetMessages sets Messages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


