# SafePeopleRegistryApiSdk.Api.ResolutionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ResolutionIndexByRegistryId**](ResolutionApi.md#resolutionindexbyregistryid) | **GET** /api/v1/registries/{registryId}/resolutions | Get resolutions by registry ID |
| [**ResolutionStoreByRegistryId**](ResolutionApi.md#resolutionstorebyregistryid) | **POST** /api/v1/registries/{registryId}/resolutions | Create a new resolution for a registry |

<a id="resolutionindexbyregistryid"></a>
# **ResolutionIndexByRegistryId**
> List&lt;Resolution&gt; ResolutionIndexByRegistryId (int registryId)

Get resolutions by registry ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |

### Return type

[**List&lt;Resolution&gt;**](Resolution.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | Invalid argument(s) |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="resolutionstorebyregistryid"></a>
# **ResolutionStoreByRegistryId**
> AccreditationStoreByRegistryId201Response ResolutionStoreByRegistryId (int registryId, Resolution resolution)

Create a new resolution for a registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **resolution** | [**Resolution**](Resolution.md) |  |  |

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Created |  -  |
| **400** | Invalid argument(s) |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

