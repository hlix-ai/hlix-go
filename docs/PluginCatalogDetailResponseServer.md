# PluginCatalogDetailResponseServer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**IconUrl** | Pointer to **string** |  | [optional] 
**Name** | **string** |  | 
**Recipes** | [**[]PluginCatalogDetailResponseServerRecipesInner**](PluginCatalogDetailResponseServerRecipesInner.md) |  | 
**RepositoryUrl** | Pointer to **string** |  | [optional] 
**Title** | **string** |  | 
**UnsupportedReason** | Pointer to **string** |  | [optional] 
**Version** | **string** |  | 
**WebsiteUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewPluginCatalogDetailResponseServer

`func NewPluginCatalogDetailResponseServer(description string, name string, recipes []PluginCatalogDetailResponseServerRecipesInner, title string, version string, ) *PluginCatalogDetailResponseServer`

NewPluginCatalogDetailResponseServer instantiates a new PluginCatalogDetailResponseServer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginCatalogDetailResponseServerWithDefaults

`func NewPluginCatalogDetailResponseServerWithDefaults() *PluginCatalogDetailResponseServer`

NewPluginCatalogDetailResponseServerWithDefaults instantiates a new PluginCatalogDetailResponseServer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PluginCatalogDetailResponseServer) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginCatalogDetailResponseServer) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginCatalogDetailResponseServer) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetIconUrl

`func (o *PluginCatalogDetailResponseServer) GetIconUrl() string`

GetIconUrl returns the IconUrl field if non-nil, zero value otherwise.

### GetIconUrlOk

`func (o *PluginCatalogDetailResponseServer) GetIconUrlOk() (*string, bool)`

GetIconUrlOk returns a tuple with the IconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconUrl

`func (o *PluginCatalogDetailResponseServer) SetIconUrl(v string)`

SetIconUrl sets IconUrl field to given value.

### HasIconUrl

`func (o *PluginCatalogDetailResponseServer) HasIconUrl() bool`

HasIconUrl returns a boolean if a field has been set.

### GetName

`func (o *PluginCatalogDetailResponseServer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PluginCatalogDetailResponseServer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PluginCatalogDetailResponseServer) SetName(v string)`

SetName sets Name field to given value.


### GetRecipes

`func (o *PluginCatalogDetailResponseServer) GetRecipes() []PluginCatalogDetailResponseServerRecipesInner`

GetRecipes returns the Recipes field if non-nil, zero value otherwise.

### GetRecipesOk

`func (o *PluginCatalogDetailResponseServer) GetRecipesOk() (*[]PluginCatalogDetailResponseServerRecipesInner, bool)`

GetRecipesOk returns a tuple with the Recipes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipes

`func (o *PluginCatalogDetailResponseServer) SetRecipes(v []PluginCatalogDetailResponseServerRecipesInner)`

SetRecipes sets Recipes field to given value.


### GetRepositoryUrl

`func (o *PluginCatalogDetailResponseServer) GetRepositoryUrl() string`

GetRepositoryUrl returns the RepositoryUrl field if non-nil, zero value otherwise.

### GetRepositoryUrlOk

`func (o *PluginCatalogDetailResponseServer) GetRepositoryUrlOk() (*string, bool)`

GetRepositoryUrlOk returns a tuple with the RepositoryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepositoryUrl

`func (o *PluginCatalogDetailResponseServer) SetRepositoryUrl(v string)`

SetRepositoryUrl sets RepositoryUrl field to given value.

### HasRepositoryUrl

`func (o *PluginCatalogDetailResponseServer) HasRepositoryUrl() bool`

HasRepositoryUrl returns a boolean if a field has been set.

### GetTitle

`func (o *PluginCatalogDetailResponseServer) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginCatalogDetailResponseServer) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginCatalogDetailResponseServer) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUnsupportedReason

`func (o *PluginCatalogDetailResponseServer) GetUnsupportedReason() string`

GetUnsupportedReason returns the UnsupportedReason field if non-nil, zero value otherwise.

### GetUnsupportedReasonOk

`func (o *PluginCatalogDetailResponseServer) GetUnsupportedReasonOk() (*string, bool)`

GetUnsupportedReasonOk returns a tuple with the UnsupportedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsupportedReason

`func (o *PluginCatalogDetailResponseServer) SetUnsupportedReason(v string)`

SetUnsupportedReason sets UnsupportedReason field to given value.

### HasUnsupportedReason

`func (o *PluginCatalogDetailResponseServer) HasUnsupportedReason() bool`

HasUnsupportedReason returns a boolean if a field has been set.

### GetVersion

`func (o *PluginCatalogDetailResponseServer) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PluginCatalogDetailResponseServer) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PluginCatalogDetailResponseServer) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetWebsiteUrl

`func (o *PluginCatalogDetailResponseServer) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *PluginCatalogDetailResponseServer) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *PluginCatalogDetailResponseServer) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.

### HasWebsiteUrl

`func (o *PluginCatalogDetailResponseServer) HasWebsiteUrl() bool`

HasWebsiteUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


