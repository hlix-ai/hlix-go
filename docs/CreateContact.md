# CreateContact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccountId** | **string** |  | 
**Email** | Pointer to **string** |  | [optional] 
**LinkedinUrl** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**SourceNote** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateContact

`func NewCreateContact(clientAccountId string, name string, ) *CreateContact`

NewCreateContact instantiates a new CreateContact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateContactWithDefaults

`func NewCreateContactWithDefaults() *CreateContact`

NewCreateContactWithDefaults instantiates a new CreateContact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientAccountId

`func (o *CreateContact) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CreateContact) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CreateContact) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetEmail

`func (o *CreateContact) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateContact) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateContact) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CreateContact) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetLinkedinUrl

`func (o *CreateContact) GetLinkedinUrl() string`

GetLinkedinUrl returns the LinkedinUrl field if non-nil, zero value otherwise.

### GetLinkedinUrlOk

`func (o *CreateContact) GetLinkedinUrlOk() (*string, bool)`

GetLinkedinUrlOk returns a tuple with the LinkedinUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedinUrl

`func (o *CreateContact) SetLinkedinUrl(v string)`

SetLinkedinUrl sets LinkedinUrl field to given value.

### HasLinkedinUrl

`func (o *CreateContact) HasLinkedinUrl() bool`

HasLinkedinUrl returns a boolean if a field has been set.

### GetName

`func (o *CreateContact) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateContact) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateContact) SetName(v string)`

SetName sets Name field to given value.


### GetSourceNote

`func (o *CreateContact) GetSourceNote() string`

GetSourceNote returns the SourceNote field if non-nil, zero value otherwise.

### GetSourceNoteOk

`func (o *CreateContact) GetSourceNoteOk() (*string, bool)`

GetSourceNoteOk returns a tuple with the SourceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceNote

`func (o *CreateContact) SetSourceNote(v string)`

SetSourceNote sets SourceNote field to given value.

### HasSourceNote

`func (o *CreateContact) HasSourceNote() bool`

HasSourceNote returns a boolean if a field has been set.

### GetTitle

`func (o *CreateContact) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateContact) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateContact) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateContact) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


