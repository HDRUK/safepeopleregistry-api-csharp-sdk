# SafePeopleRegistryApiSdk.Api.InfringementApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**InfringementIndex**](InfringementApi.md#infringementindex) | **GET** /api/v1/infringements | Infringement@index |
| [**InfringementShow**](InfringementApi.md#infringementshow) | **GET** /api/v1/infringements/{id} | Infringement@show |
| [**InfringementStore**](InfringementApi.md#infringementstore) | **POST** /api/v1/infringements | Infringement@store |

<a id="infringementindex"></a>
# **InfringementIndex**
> InfringementIndex200Response InfringementIndex ()

Infringement@index

Return a list of Infringements


### Parameters
This endpoint does not need any parameter.
### Return type

[**InfringementIndex200Response**](InfringementIndex200Response.md)

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

<a id="infringementshow"></a>
# **InfringementShow**
> InfringementIndex200Response InfringementShow (int id)

Infringement@show

Return an Infringement entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Infringement entry ID |  |

### Return type

[**InfringementIndex200Response**](InfringementIndex200Response.md)

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

<a id="infringementstore"></a>
# **InfringementStore**
> InfringementStore201Response InfringementStore (InfringementStoreRequest infringementStoreRequest)

Infringement@store

Create an Infringement entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **infringementStoreRequest** | [**InfringementStoreRequest**](InfringementStoreRequest.md) | Infringement definition |  |

### Return type

[**InfringementStore201Response**](InfringementStore201Response.md)

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

