# SafePeopleRegistryApiSdk.Api.FeatureApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FeatureIndex**](FeatureApi.md#featureindex) | **GET** /api/v1/features | Feature@index |
| [**FeatureShow**](FeatureApi.md#featureshow) | **GET** /api/v1/features/{featureId} | Feature@show |
| [**FeatureToggleByFeatureId**](FeatureApi.md#featuretogglebyfeatureid) | **PUT** /api/v1/features/{featureId}/toggle | Feature@show |

<a id="featureindex"></a>
# **FeatureIndex**
> FeatureIndex200Response FeatureIndex ()

Feature@index

Return a list of Feature entries


### Parameters
This endpoint does not need any parameter.
### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

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

<a id="featureshow"></a>
# **FeatureShow**
> FeatureIndex200Response FeatureShow (int featureId)

Feature@show

Return a Feature entry by its ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **featureId** | **int** | ID of the feature |  |

### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

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

<a id="featuretogglebyfeatureid"></a>
# **FeatureToggleByFeatureId**
> FeatureIndex200Response FeatureToggleByFeatureId (int featureId)

Feature@show

Toggle and return a Feature entry by its ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **featureId** | **int** | ID of the feature |  |

### Return type

[**FeatureIndex200Response**](FeatureIndex200Response.md)

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

