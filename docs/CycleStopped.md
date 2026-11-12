# CycleStopped

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectManagerNotified** | **bool** |  |
**Status** | **string** |  |
**Stopped** | **bool** |  | [default to true]

## Methods

### NewCycleStopped

`func NewCycleStopped(projectManagerNotified bool, status string, stopped bool, ) *CycleStopped`

NewCycleStopped instantiates a new CycleStopped object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleStoppedWithDefaults

`func NewCycleStoppedWithDefaults() *CycleStopped`

NewCycleStoppedWithDefaults instantiates a new CycleStopped object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetProjectManagerNotified

`func (o *CycleStopped) GetProjectManagerNotified() bool`

GetProjectManagerNotified returns the ProjectManagerNotified field if non-nil, zero value otherwise.

### GetProjectManagerNotifiedOk

`func (o *CycleStopped) GetProjectManagerNotifiedOk() (*bool, bool)`

GetProjectManagerNotifiedOk returns a tuple with the ProjectManagerNotified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectManagerNotified

`func (o *CycleStopped) SetProjectManagerNotified(v bool)`

SetProjectManagerNotified sets ProjectManagerNotified field to given value.


### GetStatus

`func (o *CycleStopped) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleStopped) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleStopped) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopped

`func (o *CycleStopped) GetStopped() bool`

GetStopped returns the Stopped field if non-nil, zero value otherwise.

### GetStoppedOk

`func (o *CycleStopped) GetStoppedOk() (*bool, bool)`

GetStoppedOk returns a tuple with the Stopped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopped

`func (o *CycleStopped) SetStopped(v bool)`

SetStopped sets Stopped field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


