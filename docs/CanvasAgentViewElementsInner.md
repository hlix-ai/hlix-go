# CanvasAgentViewElementsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BoxType** | Pointer to **string** |  | [optional] 
**Color** | Pointer to **string** |  | [optional] 
**Context** | Pointer to **bool** |  | [optional] 
**From** | Pointer to [**CanvasAgentOpsOpsInnerOneOfElementFrom**](CanvasAgentOpsOpsInnerOneOfElementFrom.md) |  | [optional] 
**H** | **float32** |  | 
**Heads** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**Kind** | **string** |  | 
**Origin** | Pointer to **string** |  | [optional] 
**ParentId** | Pointer to **NullableString** |  | [optional] 
**Route** | Pointer to **string** |  | [optional] 
**Shape** | Pointer to **string** |  | [optional] 
**Template** | Pointer to **string** |  | [optional] 
**Text** | Pointer to **string** |  | [optional] 
**To** | Pointer to [**CanvasAgentOpsOpsInnerOneOfElementFrom**](CanvasAgentOpsOpsInnerOneOfElementFrom.md) |  | [optional] 
**W** | **float32** |  | 
**Widget** | Pointer to **string** |  | [optional] 
**X** | **float32** |  | 
**Y** | **float32** |  | 
**Z** | **float32** |  | 

## Methods

### NewCanvasAgentViewElementsInner

`func NewCanvasAgentViewElementsInner(h float32, id string, kind string, w float32, x float32, y float32, z float32, ) *CanvasAgentViewElementsInner`

NewCanvasAgentViewElementsInner instantiates a new CanvasAgentViewElementsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanvasAgentViewElementsInnerWithDefaults

`func NewCanvasAgentViewElementsInnerWithDefaults() *CanvasAgentViewElementsInner`

NewCanvasAgentViewElementsInnerWithDefaults instantiates a new CanvasAgentViewElementsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBoxType

`func (o *CanvasAgentViewElementsInner) GetBoxType() string`

GetBoxType returns the BoxType field if non-nil, zero value otherwise.

### GetBoxTypeOk

`func (o *CanvasAgentViewElementsInner) GetBoxTypeOk() (*string, bool)`

GetBoxTypeOk returns a tuple with the BoxType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoxType

`func (o *CanvasAgentViewElementsInner) SetBoxType(v string)`

SetBoxType sets BoxType field to given value.

### HasBoxType

`func (o *CanvasAgentViewElementsInner) HasBoxType() bool`

HasBoxType returns a boolean if a field has been set.

### GetColor

`func (o *CanvasAgentViewElementsInner) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CanvasAgentViewElementsInner) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CanvasAgentViewElementsInner) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *CanvasAgentViewElementsInner) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetContext

`func (o *CanvasAgentViewElementsInner) GetContext() bool`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *CanvasAgentViewElementsInner) GetContextOk() (*bool, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *CanvasAgentViewElementsInner) SetContext(v bool)`

SetContext sets Context field to given value.

### HasContext

`func (o *CanvasAgentViewElementsInner) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetFrom

`func (o *CanvasAgentViewElementsInner) GetFrom() CanvasAgentOpsOpsInnerOneOfElementFrom`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *CanvasAgentViewElementsInner) GetFromOk() (*CanvasAgentOpsOpsInnerOneOfElementFrom, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *CanvasAgentViewElementsInner) SetFrom(v CanvasAgentOpsOpsInnerOneOfElementFrom)`

SetFrom sets From field to given value.

### HasFrom

`func (o *CanvasAgentViewElementsInner) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetH

`func (o *CanvasAgentViewElementsInner) GetH() float32`

GetH returns the H field if non-nil, zero value otherwise.

### GetHOk

`func (o *CanvasAgentViewElementsInner) GetHOk() (*float32, bool)`

GetHOk returns a tuple with the H field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetH

`func (o *CanvasAgentViewElementsInner) SetH(v float32)`

SetH sets H field to given value.


### GetHeads

`func (o *CanvasAgentViewElementsInner) GetHeads() string`

GetHeads returns the Heads field if non-nil, zero value otherwise.

### GetHeadsOk

`func (o *CanvasAgentViewElementsInner) GetHeadsOk() (*string, bool)`

GetHeadsOk returns a tuple with the Heads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeads

`func (o *CanvasAgentViewElementsInner) SetHeads(v string)`

SetHeads sets Heads field to given value.

### HasHeads

`func (o *CanvasAgentViewElementsInner) HasHeads() bool`

HasHeads returns a boolean if a field has been set.

### GetId

`func (o *CanvasAgentViewElementsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CanvasAgentViewElementsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CanvasAgentViewElementsInner) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *CanvasAgentViewElementsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CanvasAgentViewElementsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CanvasAgentViewElementsInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetOrigin

`func (o *CanvasAgentViewElementsInner) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *CanvasAgentViewElementsInner) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *CanvasAgentViewElementsInner) SetOrigin(v string)`

SetOrigin sets Origin field to given value.

### HasOrigin

`func (o *CanvasAgentViewElementsInner) HasOrigin() bool`

HasOrigin returns a boolean if a field has been set.

### GetParentId

`func (o *CanvasAgentViewElementsInner) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *CanvasAgentViewElementsInner) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *CanvasAgentViewElementsInner) SetParentId(v string)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *CanvasAgentViewElementsInner) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### SetParentIdNil

`func (o *CanvasAgentViewElementsInner) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *CanvasAgentViewElementsInner) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil
### GetRoute

`func (o *CanvasAgentViewElementsInner) GetRoute() string`

GetRoute returns the Route field if non-nil, zero value otherwise.

### GetRouteOk

`func (o *CanvasAgentViewElementsInner) GetRouteOk() (*string, bool)`

GetRouteOk returns a tuple with the Route field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoute

`func (o *CanvasAgentViewElementsInner) SetRoute(v string)`

SetRoute sets Route field to given value.

### HasRoute

`func (o *CanvasAgentViewElementsInner) HasRoute() bool`

HasRoute returns a boolean if a field has been set.

### GetShape

`func (o *CanvasAgentViewElementsInner) GetShape() string`

GetShape returns the Shape field if non-nil, zero value otherwise.

### GetShapeOk

`func (o *CanvasAgentViewElementsInner) GetShapeOk() (*string, bool)`

GetShapeOk returns a tuple with the Shape field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShape

`func (o *CanvasAgentViewElementsInner) SetShape(v string)`

SetShape sets Shape field to given value.

### HasShape

`func (o *CanvasAgentViewElementsInner) HasShape() bool`

HasShape returns a boolean if a field has been set.

### GetTemplate

`func (o *CanvasAgentViewElementsInner) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *CanvasAgentViewElementsInner) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *CanvasAgentViewElementsInner) SetTemplate(v string)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *CanvasAgentViewElementsInner) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetText

`func (o *CanvasAgentViewElementsInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *CanvasAgentViewElementsInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *CanvasAgentViewElementsInner) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *CanvasAgentViewElementsInner) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTo

`func (o *CanvasAgentViewElementsInner) GetTo() CanvasAgentOpsOpsInnerOneOfElementFrom`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *CanvasAgentViewElementsInner) GetToOk() (*CanvasAgentOpsOpsInnerOneOfElementFrom, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *CanvasAgentViewElementsInner) SetTo(v CanvasAgentOpsOpsInnerOneOfElementFrom)`

SetTo sets To field to given value.

### HasTo

`func (o *CanvasAgentViewElementsInner) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetW

`func (o *CanvasAgentViewElementsInner) GetW() float32`

GetW returns the W field if non-nil, zero value otherwise.

### GetWOk

`func (o *CanvasAgentViewElementsInner) GetWOk() (*float32, bool)`

GetWOk returns a tuple with the W field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetW

`func (o *CanvasAgentViewElementsInner) SetW(v float32)`

SetW sets W field to given value.


### GetWidget

`func (o *CanvasAgentViewElementsInner) GetWidget() string`

GetWidget returns the Widget field if non-nil, zero value otherwise.

### GetWidgetOk

`func (o *CanvasAgentViewElementsInner) GetWidgetOk() (*string, bool)`

GetWidgetOk returns a tuple with the Widget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidget

`func (o *CanvasAgentViewElementsInner) SetWidget(v string)`

SetWidget sets Widget field to given value.

### HasWidget

`func (o *CanvasAgentViewElementsInner) HasWidget() bool`

HasWidget returns a boolean if a field has been set.

### GetX

`func (o *CanvasAgentViewElementsInner) GetX() float32`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *CanvasAgentViewElementsInner) GetXOk() (*float32, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *CanvasAgentViewElementsInner) SetX(v float32)`

SetX sets X field to given value.


### GetY

`func (o *CanvasAgentViewElementsInner) GetY() float32`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *CanvasAgentViewElementsInner) GetYOk() (*float32, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *CanvasAgentViewElementsInner) SetY(v float32)`

SetY sets Y field to given value.


### GetZ

`func (o *CanvasAgentViewElementsInner) GetZ() float32`

GetZ returns the Z field if non-nil, zero value otherwise.

### GetZOk

`func (o *CanvasAgentViewElementsInner) GetZOk() (*float32, bool)`

GetZOk returns a tuple with the Z field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZ

`func (o *CanvasAgentViewElementsInner) SetZ(v float32)`

SetZ sets Z field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


