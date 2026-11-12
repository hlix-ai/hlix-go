# GrowthMailboxDns

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dkim** | [**GrowthMailboxDnsDkim**](GrowthMailboxDnsDkim.md) |  |
**Dmarc** | [**GrowthMailboxDnsDmarc**](GrowthMailboxDnsDmarc.md) |  |
**Domain** | **string** |  |
**Spf** | [**GrowthMailboxDnsSpf**](GrowthMailboxDnsSpf.md) |  |

## Methods

### NewGrowthMailboxDns

`func NewGrowthMailboxDns(dkim GrowthMailboxDnsDkim, dmarc GrowthMailboxDnsDmarc, domain string, spf GrowthMailboxDnsSpf, ) *GrowthMailboxDns`

NewGrowthMailboxDns instantiates a new GrowthMailboxDns object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthMailboxDnsWithDefaults

`func NewGrowthMailboxDnsWithDefaults() *GrowthMailboxDns`

NewGrowthMailboxDnsWithDefaults instantiates a new GrowthMailboxDns object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDkim

`func (o *GrowthMailboxDns) GetDkim() GrowthMailboxDnsDkim`

GetDkim returns the Dkim field if non-nil, zero value otherwise.

### GetDkimOk

`func (o *GrowthMailboxDns) GetDkimOk() (*GrowthMailboxDnsDkim, bool)`

GetDkimOk returns a tuple with the Dkim field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDkim

`func (o *GrowthMailboxDns) SetDkim(v GrowthMailboxDnsDkim)`

SetDkim sets Dkim field to given value.


### GetDmarc

`func (o *GrowthMailboxDns) GetDmarc() GrowthMailboxDnsDmarc`

GetDmarc returns the Dmarc field if non-nil, zero value otherwise.

### GetDmarcOk

`func (o *GrowthMailboxDns) GetDmarcOk() (*GrowthMailboxDnsDmarc, bool)`

GetDmarcOk returns a tuple with the Dmarc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDmarc

`func (o *GrowthMailboxDns) SetDmarc(v GrowthMailboxDnsDmarc)`

SetDmarc sets Dmarc field to given value.


### GetDomain

`func (o *GrowthMailboxDns) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *GrowthMailboxDns) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *GrowthMailboxDns) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetSpf

`func (o *GrowthMailboxDns) GetSpf() GrowthMailboxDnsSpf`

GetSpf returns the Spf field if non-nil, zero value otherwise.

### GetSpfOk

`func (o *GrowthMailboxDns) GetSpfOk() (*GrowthMailboxDnsSpf, bool)`

GetSpfOk returns a tuple with the Spf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpf

`func (o *GrowthMailboxDns) SetSpf(v GrowthMailboxDnsSpf)`

SetSpf sets Spf field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


