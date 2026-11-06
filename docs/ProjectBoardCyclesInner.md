# ProjectBoardCyclesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveRun** | [**NullableProjectBoardCyclesInnerActiveRun**](ProjectBoardCyclesInnerActiveRun.md) |  | 
**DependsOn** | **[]string** |  | 
**Id** | **string** |  | 
**Persona** | **NullableString** |  | 
**Stage** | **string** |  | 
**Status** | **string** |  | 
**Steps** | [**[]ProjectBoardCyclesInnerStepsInner**](ProjectBoardCyclesInnerStepsInner.md) |  | 
**Title** | **string** |  | 

## Methods

### NewProjectBoardCyclesInner

`func NewProjectBoardCyclesInner(activeRun NullableProjectBoardCyclesInnerActiveRun, dependsOn []string, id string, persona NullableString, stage string, status string, steps []ProjectBoardCyclesInnerStepsInner, title string, ) *ProjectBoardCyclesInner`

NewProjectBoardCyclesInner instantiates a new ProjectBoardCyclesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectBoardCyclesInnerWithDefaults

`func NewProjectBoardCyclesInnerWithDefaults() *ProjectBoardCyclesInner`

NewProjectBoardCyclesInnerWithDefaults instantiates a new ProjectBoardCyclesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveRun

`func (o *ProjectBoardCyclesInner) GetActiveRun() ProjectBoardCyclesInnerActiveRun`

GetActiveRun returns the ActiveRun field if non-nil, zero value otherwise.

### GetActiveRunOk

`func (o *ProjectBoardCyclesInner) GetActiveRunOk() (*ProjectBoardCyclesInnerActiveRun, bool)`

GetActiveRunOk returns a tuple with the ActiveRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveRun

`func (o *ProjectBoardCyclesInner) SetActiveRun(v ProjectBoardCyclesInnerActiveRun)`

SetActiveRun sets ActiveRun field to given value.


### SetActiveRunNil

`func (o *ProjectBoardCyclesInner) SetActiveRunNil(b bool)`

 SetActiveRunNil sets the value for ActiveRun to be an explicit nil

### UnsetActiveRun
`func (o *ProjectBoardCyclesInner) UnsetActiveRun()`

UnsetActiveRun ensures that no value is present for ActiveRun, not even an explicit nil
### GetDependsOn

`func (o *ProjectBoardCyclesInner) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *ProjectBoardCyclesInner) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *ProjectBoardCyclesInner) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.


### GetId

`func (o *ProjectBoardCyclesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectBoardCyclesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectBoardCyclesInner) SetId(v string)`

SetId sets Id field to given value.


### GetPersona

`func (o *ProjectBoardCyclesInner) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *ProjectBoardCyclesInner) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *ProjectBoardCyclesInner) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *ProjectBoardCyclesInner) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *ProjectBoardCyclesInner) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetStage

`func (o *ProjectBoardCyclesInner) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *ProjectBoardCyclesInner) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *ProjectBoardCyclesInner) SetStage(v string)`

SetStage sets Stage field to given value.


### GetStatus

`func (o *ProjectBoardCyclesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectBoardCyclesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectBoardCyclesInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSteps

`func (o *ProjectBoardCyclesInner) GetSteps() []ProjectBoardCyclesInnerStepsInner`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *ProjectBoardCyclesInner) GetStepsOk() (*[]ProjectBoardCyclesInnerStepsInner, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *ProjectBoardCyclesInner) SetSteps(v []ProjectBoardCyclesInnerStepsInner)`

SetSteps sets Steps field to given value.


### GetTitle

`func (o *ProjectBoardCyclesInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProjectBoardCyclesInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProjectBoardCyclesInner) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


