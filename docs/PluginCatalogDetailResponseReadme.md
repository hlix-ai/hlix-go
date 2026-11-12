# PluginCatalogDetailResponseReadme

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [PluginCatalogDetailResponseReadmeAnyOf](PluginCatalogDetailResponseReadmeAnyOf.md) | `baseUrl`, `content`, `imageBaseUrl`, `status`, `url` |
| [PluginCatalogDetailResponseReadmeAnyOf1](PluginCatalogDetailResponseReadmeAnyOf1.md) | `status` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `PluginCatalogDetailResponseReadmeAnyOf` | `*PluginCatalogDetailResponseReadmeAnyOf` |
| `PluginCatalogDetailResponseReadmeAnyOf1` | `*PluginCatalogDetailResponseReadmeAnyOf1` |

## Methods

### UnmarshalJSON

`func (dst *PluginCatalogDetailResponseReadme) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src PluginCatalogDetailResponseReadme) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


