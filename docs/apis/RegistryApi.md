# SafePeopleRegistryApiSdk.Api.RegistryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**RegistryDestroy**](RegistryApi.md#registrydestroy) | **DELETE** /api/v1/registry/{id} | Registry@destroy |
| [**RegistryIndex**](RegistryApi.md#registryindex) | **GET** /api/v1/registry | Registry@index |
| [**RegistryShow**](RegistryApi.md#registryshow) | **GET** /api/v1/registry/{id} | Registry@show |
| [**RegistryStore**](RegistryApi.md#registrystore) | **POST** /api/v1/registry | Registry@store |
| [**RegistryUpdate**](RegistryApi.md#registryupdate) | **PUT** /api/v1/registry/{id} | Registry@update |

<a id="registrydestroy"></a>
# **RegistryDestroy**
> AffiliationDestroy200Response RegistryDestroy (int id)

Registry@destroy

Delete a Registry entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Registry entry ID |  |

### Return type

[**AffiliationDestroy200Response**](AffiliationDestroy200Response.md)

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
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="registryindex"></a>
# **RegistryIndex**
> RegistryIndex200Response RegistryIndex ()

Registry@index

Return a list of Registry entries


### Parameters
This endpoint does not need any parameter.
### Return type

[**RegistryIndex200Response**](RegistryIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="registryshow"></a>
# **RegistryShow**
> RegistryIndex200Response RegistryShow (int id)

Registry@show

Return a Registry entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Registry entry ID |  |

### Return type

[**RegistryIndex200Response**](RegistryIndex200Response.md)

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
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="registrystore"></a>
# **RegistryStore**
> AccreditationStoreByRegistryId201Response RegistryStore (Registry registry)

Registry@store

Create a Registry entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registry** | [**Registry**](Registry.md) | Registry definition |  |

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
| **404** | Not found response |  -  |
| **201** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="registryupdate"></a>
# **RegistryUpdate**
> RegistryUpdate200Response RegistryUpdate (int id, Registry registry)

Registry@update

Update a Registry entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Registry entry ID |  |
| **registry** | [**Registry**](Registry.md) | Registry definition |  |

### Return type

[**RegistryUpdate200Response**](RegistryUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

