# SafePeopleRegistryApiSdk.Api.EducationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**EducationDestroyByRegistryId**](EducationApi.md#educationdestroybyregistryid) | **DELETE** /api/v1/registries/{registryId}/educations/{id} | Delete an education record |
| [**EducationIndexByRegistryId**](EducationApi.md#educationindexbyregistryid) | **GET** /api/v1/educations/registries/{registryId} | Get education records by registry ID |
| [**EducationShowByRegistryId**](EducationApi.md#educationshowbyregistryid) | **GET** /api/v1/educations/{id}/registries/{registryId} | Get a specific education record by ID and registry ID |
| [**EducationStoreByRegistryId**](EducationApi.md#educationstorebyregistryid) | **POST** /api/v1/registries/{registryId}/educations | Create a new education record for a registry |
| [**EducationUpdateByRegistryId**](EducationApi.md#educationupdatebyregistryid) | **PUT** /api/v1/registries/{registryId}/educations/{id} | Update an existing education record |

<a id="educationdestroybyregistryid"></a>
# **EducationDestroyByRegistryId**
> EducationDestroyByRegistryId200Response EducationDestroyByRegistryId (int registryId, int id)

Delete an education record


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **id** | **int** | ID of the education record |  |

### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Deleted |  -  |
| **400** | Invalid argument(s) |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="educationindexbyregistryid"></a>
# **EducationIndexByRegistryId**
> List&lt;Education&gt; EducationIndexByRegistryId (int registryId)

Get education records by registry ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |

### Return type

[**List&lt;Education&gt;**](Education.md)

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

<a id="educationshowbyregistryid"></a>
# **EducationShowByRegistryId**
> Education EducationShowByRegistryId (int registryId, int id)

Get a specific education record by ID and registry ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **id** | **int** | ID of the education record |  |

### Return type

[**Education**](Education.md)

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
| **404** | Education record not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="educationstorebyregistryid"></a>
# **EducationStoreByRegistryId**
> AccreditationStoreByRegistryId201Response EducationStoreByRegistryId (int registryId, Education education)

Create a new education record for a registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **education** | [**Education**](Education.md) |  |  |

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

<a id="educationupdatebyregistryid"></a>
# **EducationUpdateByRegistryId**
> Education EducationUpdateByRegistryId (int registryId, int id, Education education)

Update an existing education record


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | ID of the registry |  |
| **id** | **int** | ID of the education record |  |
| **education** | [**Education**](Education.md) |  |  |

### Return type

[**Education**](Education.md)

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

