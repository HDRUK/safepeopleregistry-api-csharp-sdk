# SafePeopleRegistryApiSdk.Api.HistoryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**HistoryIndex**](HistoryApi.md#historyindex) | **GET** /api/v1/histories | History@index |
| [**HistoryShow**](HistoryApi.md#historyshow) | **GET** /api/v1/histories/{id} | History@show |
| [**HistoryStore**](HistoryApi.md#historystore) | **POST** /api/v1/histories | History@store |

<a id="historyindex"></a>
# **HistoryIndex**
> HistoryIndex200Response HistoryIndex ()

History@index

Return a list of Histories


### Parameters
This endpoint does not need any parameter.
### Return type

[**HistoryIndex200Response**](HistoryIndex200Response.md)

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

<a id="historyshow"></a>
# **HistoryShow**
> HistoryIndex200Response HistoryShow (int id)

History@show

Return a History entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | History entry ID |  |

### Return type

[**HistoryIndex200Response**](HistoryIndex200Response.md)

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

<a id="historystore"></a>
# **HistoryStore**
> HistoryStore201Response HistoryStore (HistoryStoreRequest historyStoreRequest)

History@store

Create a History entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **historyStoreRequest** | [**HistoryStoreRequest**](HistoryStoreRequest.md) | History definition |  |

### Return type

[**HistoryStore201Response**](HistoryStore201Response.md)

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

