# CrmClientRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | [**CrmClientRecordAccount**](CrmClientRecordAccount.md) |  | 
**Activities** | [**[]CrmClientRecordActivitiesInner**](CrmClientRecordActivitiesInner.md) |  | 
**Contacts** | [**[]CrmClientRecordContactsInner**](CrmClientRecordContactsInner.md) |  | 
**Conversation** | [**[]CrmClientRecordConversationInner**](CrmClientRecordConversationInner.md) |  | 
**Deals** | [**[]CrmClientRecordDealsInner**](CrmClientRecordDealsInner.md) |  | 
**Invoices** | [**CrmClientRecordInvoices**](CrmClientRecordInvoices.md) |  | 
**PipelineStages** | **[]string** |  | 
**Projects** | [**[]CrmClientRecordProjectsInner**](CrmClientRecordProjectsInner.md) |  | 
**Suggestions** | [**[]CrmClientRecordSuggestionsInner**](CrmClientRecordSuggestionsInner.md) |  | 

## Methods

### NewCrmClientRecord

`func NewCrmClientRecord(account CrmClientRecordAccount, activities []CrmClientRecordActivitiesInner, contacts []CrmClientRecordContactsInner, conversation []CrmClientRecordConversationInner, deals []CrmClientRecordDealsInner, invoices CrmClientRecordInvoices, pipelineStages []string, projects []CrmClientRecordProjectsInner, suggestions []CrmClientRecordSuggestionsInner, ) *CrmClientRecord`

NewCrmClientRecord instantiates a new CrmClientRecord object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCrmClientRecordWithDefaults

`func NewCrmClientRecordWithDefaults() *CrmClientRecord`

NewCrmClientRecordWithDefaults instantiates a new CrmClientRecord object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccount

`func (o *CrmClientRecord) GetAccount() CrmClientRecordAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *CrmClientRecord) GetAccountOk() (*CrmClientRecordAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *CrmClientRecord) SetAccount(v CrmClientRecordAccount)`

SetAccount sets Account field to given value.


### GetActivities

`func (o *CrmClientRecord) GetActivities() []CrmClientRecordActivitiesInner`

GetActivities returns the Activities field if non-nil, zero value otherwise.

### GetActivitiesOk

`func (o *CrmClientRecord) GetActivitiesOk() (*[]CrmClientRecordActivitiesInner, bool)`

GetActivitiesOk returns a tuple with the Activities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivities

`func (o *CrmClientRecord) SetActivities(v []CrmClientRecordActivitiesInner)`

SetActivities sets Activities field to given value.


### GetContacts

`func (o *CrmClientRecord) GetContacts() []CrmClientRecordContactsInner`

GetContacts returns the Contacts field if non-nil, zero value otherwise.

### GetContactsOk

`func (o *CrmClientRecord) GetContactsOk() (*[]CrmClientRecordContactsInner, bool)`

GetContactsOk returns a tuple with the Contacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContacts

`func (o *CrmClientRecord) SetContacts(v []CrmClientRecordContactsInner)`

SetContacts sets Contacts field to given value.


### GetConversation

`func (o *CrmClientRecord) GetConversation() []CrmClientRecordConversationInner`

GetConversation returns the Conversation field if non-nil, zero value otherwise.

### GetConversationOk

`func (o *CrmClientRecord) GetConversationOk() (*[]CrmClientRecordConversationInner, bool)`

GetConversationOk returns a tuple with the Conversation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversation

`func (o *CrmClientRecord) SetConversation(v []CrmClientRecordConversationInner)`

SetConversation sets Conversation field to given value.


### GetDeals

`func (o *CrmClientRecord) GetDeals() []CrmClientRecordDealsInner`

GetDeals returns the Deals field if non-nil, zero value otherwise.

### GetDealsOk

`func (o *CrmClientRecord) GetDealsOk() (*[]CrmClientRecordDealsInner, bool)`

GetDealsOk returns a tuple with the Deals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeals

`func (o *CrmClientRecord) SetDeals(v []CrmClientRecordDealsInner)`

SetDeals sets Deals field to given value.


### GetInvoices

`func (o *CrmClientRecord) GetInvoices() CrmClientRecordInvoices`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *CrmClientRecord) GetInvoicesOk() (*CrmClientRecordInvoices, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *CrmClientRecord) SetInvoices(v CrmClientRecordInvoices)`

SetInvoices sets Invoices field to given value.


### GetPipelineStages

`func (o *CrmClientRecord) GetPipelineStages() []string`

GetPipelineStages returns the PipelineStages field if non-nil, zero value otherwise.

### GetPipelineStagesOk

`func (o *CrmClientRecord) GetPipelineStagesOk() (*[]string, bool)`

GetPipelineStagesOk returns a tuple with the PipelineStages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipelineStages

`func (o *CrmClientRecord) SetPipelineStages(v []string)`

SetPipelineStages sets PipelineStages field to given value.


### GetProjects

`func (o *CrmClientRecord) GetProjects() []CrmClientRecordProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *CrmClientRecord) GetProjectsOk() (*[]CrmClientRecordProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *CrmClientRecord) SetProjects(v []CrmClientRecordProjectsInner)`

SetProjects sets Projects field to given value.


### GetSuggestions

`func (o *CrmClientRecord) GetSuggestions() []CrmClientRecordSuggestionsInner`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *CrmClientRecord) GetSuggestionsOk() (*[]CrmClientRecordSuggestionsInner, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *CrmClientRecord) SetSuggestions(v []CrmClientRecordSuggestionsInner)`

SetSuggestions sets Suggestions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


