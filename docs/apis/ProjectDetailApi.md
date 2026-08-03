# SafePeopleRegistryApiSdk.Api.ProjectDetailApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectDetailIndex**](ProjectDetailApi.md#projectdetailindex) | **GET** /api/v1/project_details | ProjectDetail@index |
| [**ProjectDetailShow**](ProjectDetailApi.md#projectdetailshow) | **GET** /api/v1/project_details/{id} | ProjectDetail@show |

<a id="projectdetailindex"></a>
# **ProjectDetailIndex**
> ProjectDetailIndex200Response ProjectDetailIndex ()

ProjectDetail@index

Return a list of ProjectDetail


### Parameters
This endpoint does not need any parameter.
### Return type

[**ProjectDetailIndex200Response**](ProjectDetailIndex200Response.md)

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

<a id="projectdetailshow"></a>
# **ProjectDetailShow**
> ProjectDetailIndex200Response ProjectDetailShow (int id)

ProjectDetail@show

Return a ProjectDetail


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ProjectDetail entry ID |  |

### Return type

[**ProjectDetailIndex200Response**](ProjectDetailIndex200Response.md)

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

