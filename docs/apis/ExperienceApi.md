# SafePeopleRegistryApiSdk.Api.ExperienceApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ExperienceDestroy**](ExperienceApi.md#experiencedestroy) | **DELETE** /api/v1/experiences/{id} | Experience@destroy |
| [**ExperienceIndex**](ExperienceApi.md#experienceindex) | **GET** /api/v1/experiences | Experience@index |
| [**ExperienceShow**](ExperienceApi.md#experienceshow) | **GET** /api/v1/experiences/{id} | Experience@show |
| [**ExperienceStore**](ExperienceApi.md#experiencestore) | **POST** /api/v1/experiences | Experience@store |
| [**ExperienceUpdate**](ExperienceApi.md#experienceupdate) | **PUT** /api/v1/experiences/{id} | Experience@update |

<a id="experiencedestroy"></a>
# **ExperienceDestroy**
> AffiliationDestroy200Response ExperienceDestroy (int id)

Experience@destroy

Delete a Experience entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Experience entry ID |  |

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

<a id="experienceindex"></a>
# **ExperienceIndex**
> ExperienceIndex200Response ExperienceIndex ()

Experience@index

Return a list of Experience entries


### Parameters
This endpoint does not need any parameter.
### Return type

[**ExperienceIndex200Response**](ExperienceIndex200Response.md)

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

<a id="experienceshow"></a>
# **ExperienceShow**
> ExperienceShow200Response ExperienceShow (int id)

Experience@show

Return an Experience entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Experience entry ID |  |

### Return type

[**ExperienceShow200Response**](ExperienceShow200Response.md)

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

<a id="experiencestore"></a>
# **ExperienceStore**
> ExperienceStore201Response ExperienceStore (ExperienceStoreRequest experienceStoreRequest)

Experience@store

Create an Experience entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **experienceStoreRequest** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition |  |

### Return type

[**ExperienceStore201Response**](ExperienceStore201Response.md)

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

<a id="experienceupdate"></a>
# **ExperienceUpdate**
> ExperienceUpdate200Response ExperienceUpdate (int id, ExperienceStoreRequest experienceStoreRequest)

Experience@update

Update an Experience entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Experience entry ID |  |
| **experienceStoreRequest** | [**ExperienceStoreRequest**](ExperienceStoreRequest.md) | Experience definition |  |

### Return type

[**ExperienceUpdate200Response**](ExperienceUpdate200Response.md)

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

