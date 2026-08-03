# SafePeopleRegistryApiSdk.Api.TrainingApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**TrainingIndex**](TrainingApi.md#trainingindex) | **GET** /api/v1/training | Training@index |
| [**TrainingIndexByRegistryId**](TrainingApi.md#trainingindexbyregistryid) | **GET** /api/v1/training/registry/{id} | Training@show |
| [**TrainingShow**](TrainingApi.md#trainingshow) | **GET** /api/v1/training/{id} | Training@show |
| [**TrainingStore**](TrainingApi.md#trainingstore) | **POST** /api/v1/training | Training@store |
| [**TrainingUpdate**](TrainingApi.md#trainingupdate) | **PUT** /api/v1/training/{id} | Training@update |

<a id="trainingindex"></a>
# **TrainingIndex**
> TrainingShow200Response TrainingIndex ()

Training@index

Return a list of Training entries


### Parameters
This endpoint does not need any parameter.
### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

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

<a id="trainingindexbyregistryid"></a>
# **TrainingIndexByRegistryId**
> TrainingShow200Response TrainingIndexByRegistryId (int id)

Training@show

Return a list of training by registry id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Training registry id |  |

### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

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

<a id="trainingshow"></a>
# **TrainingShow**
> TrainingShow200Response TrainingShow (int id)

Training@show

Return a training record by registry id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Training id |  |

### Return type

[**TrainingShow200Response**](TrainingShow200Response.md)

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

<a id="trainingstore"></a>
# **TrainingStore**
> AccreditationStoreByRegistryId201Response TrainingStore (Training training)

Training@store

Create a Training entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **training** | [**Training**](Training.md) | Training definition |  |

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

<a id="trainingupdate"></a>
# **TrainingUpdate**
> TrainingUpdate200Response TrainingUpdate (int id, Training training)

Training@update

Update a Training entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Training entry ID |  |
| **training** | [**Training**](Training.md) | Training definition |  |

### Return type

[**TrainingUpdate200Response**](TrainingUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

