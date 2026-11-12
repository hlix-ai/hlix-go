# AuditChainVerification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checked** | **int32** |  |
**FirstBadId** | **NullableString** |  |
**Ok** | **bool** |  |
**Total** | **int32** |  |

## Methods

### NewAuditChainVerification

`func NewAuditChainVerification(checked int32, firstBadId NullableString, ok bool, total int32, ) *AuditChainVerification`

NewAuditChainVerification instantiates a new AuditChainVerification object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAuditChainVerificationWithDefaults

`func NewAuditChainVerificationWithDefaults() *AuditChainVerification`

NewAuditChainVerificationWithDefaults instantiates a new AuditChainVerification object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChecked

`func (o *AuditChainVerification) GetChecked() int32`

GetChecked returns the Checked field if non-nil, zero value otherwise.

### GetCheckedOk

`func (o *AuditChainVerification) GetCheckedOk() (*int32, bool)`

GetCheckedOk returns a tuple with the Checked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecked

`func (o *AuditChainVerification) SetChecked(v int32)`

SetChecked sets Checked field to given value.


### GetFirstBadId

`func (o *AuditChainVerification) GetFirstBadId() string`

GetFirstBadId returns the FirstBadId field if non-nil, zero value otherwise.

### GetFirstBadIdOk

`func (o *AuditChainVerification) GetFirstBadIdOk() (*string, bool)`

GetFirstBadIdOk returns a tuple with the FirstBadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstBadId

`func (o *AuditChainVerification) SetFirstBadId(v string)`

SetFirstBadId sets FirstBadId field to given value.


### SetFirstBadIdNil

`func (o *AuditChainVerification) SetFirstBadIdNil(b bool)`

 SetFirstBadIdNil sets the value for FirstBadId to be an explicit nil

### UnsetFirstBadId
`func (o *AuditChainVerification) UnsetFirstBadId()`

UnsetFirstBadId ensures that no value is present for FirstBadId, not even an explicit nil
### GetOk

`func (o *AuditChainVerification) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *AuditChainVerification) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *AuditChainVerification) SetOk(v bool)`

SetOk sets Ok field to given value.


### GetTotal

`func (o *AuditChainVerification) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AuditChainVerification) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AuditChainVerification) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


