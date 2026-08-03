# SafePeopleRegistryApiSdk.Api.AccreditationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**AccreditationIndexByRegistryId**](AccreditationApi.md#accreditationindexbyregistryid) | **GET** /api/v1/accreditations/{registryId} | Get accreditations by registry ID |
| [**AccreditationStoreByRegistryId**](AccreditationApi.md#accreditationstorebyregistryid) | **POST** /api/v1/accreditations/{registryId} | Create accreditation for a registry |
| [**AccreditationUpdateByRegistryId**](AccreditationApi.md#accreditationupdatebyregistryid) | **PUT** /api/v1/accreditations/{id}/registries/{registryId} | Update accreditation for a registry |

<a id="accreditationindexbyregistryid"></a>
# **AccreditationIndexByRegistryId**
> AccreditationIndexByRegistryId200Response AccreditationIndexByRegistryId (int registryId)

Get accreditations by registry ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |

### Return type

[**AccreditationIndexByRegistryId200Response**](AccreditationIndexByRegistryId200Response.md)

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

<a id="accreditationstorebyregistryid"></a>
# **AccreditationStoreByRegistryId**
> AccreditationStoreByRegistryId201Response AccreditationStoreByRegistryId (int registryId, Accreditation accreditation)

Create accreditation for a registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **accreditation** | [**Accreditation**](Accreditation.md) |  |  |

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

<a id="accreditationupdatebyregistryid"></a>
# **AccreditationUpdateByRegistryId**
> AccreditationUpdateByRegistryId200Response AccreditationUpdateByRegistryId (int registryId, int id, Accreditation accreditation)

Update accreditation for a registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **id** | **int** | ID of the accreditation |  |
| **accreditation** | [**Accreditation**](Accreditation.md) |  |  |

### Return type

[**AccreditationUpdateByRegistryId200Response**](AccreditationUpdateByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **400** | Invalid argument(s) |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

