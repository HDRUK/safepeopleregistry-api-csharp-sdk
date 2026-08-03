# SafePeopleRegistryApiSdk.Api.CustodianModelConfigApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianModelConfigDestroy**](CustodianModelConfigApi.md#custodianmodelconfigdestroy) | **DELETE** /api/v1/custodian_config/{id} | CustodianModelConfig@destroy |
| [**CustodianModelConfigGetByCustodianID**](CustodianModelConfigApi.md#custodianmodelconfiggetbycustodianid) | **GET** /api/v1/custodian_config/{id} | CustodianModelConfig@getByCustodianID |
| [**CustodianModelConfigGetEntityModels**](CustodianModelConfigApi.md#custodianmodelconfiggetentitymodels) | **GET** /api/v1/custodian_config/{custodianId}/entity_models | Get entity models for custodian config |
| [**CustodianModelConfigStore**](CustodianModelConfigApi.md#custodianmodelconfigstore) | **POST** /api/v1/custodian_config | CustodianModelConfig@store |
| [**CustodianModelConfigUpdate**](CustodianModelConfigApi.md#custodianmodelconfigupdate) | **PUT** /api/v1/custodian_config/{id} | CustodianModelConfig@update |
| [**CustodianModelConfigUpdateEntityModels**](CustodianModelConfigApi.md#custodianmodelconfigupdateentitymodels) | **PUT** /api/v1/custodian_config/{custodianId}/entity_models | Update a custodian&#39;s entity models |

<a id="custodianmodelconfigdestroy"></a>
# **CustodianModelConfigDestroy**
> AffiliationDestroy200Response CustodianModelConfigDestroy (int id)

CustodianModelConfig@destroy

Delete a CustodianModelConfig entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | CustodianModelConfig entry ID |  |

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

<a id="custodianmodelconfiggetbycustodianid"></a>
# **CustodianModelConfigGetByCustodianID**
> CustodianModelConfigGetByCustodianID200Response CustodianModelConfigGetByCustodianID (int id)

CustodianModelConfig@getByCustodianID

Return a list of Custodian config


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | CustodianModelConfig entry ID |  |

### Return type

[**CustodianModelConfigGetByCustodianID200Response**](CustodianModelConfigGetByCustodianID200Response.md)

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

<a id="custodianmodelconfiggetentitymodels"></a>
# **CustodianModelConfigGetEntityModels**
> CustodianModelConfigGetEntityModels200Response CustodianModelConfigGetEntityModels (int custodianId, string entityModelType)

Get entity models for custodian config

Retrieve entity models associated with custodian config based on the specified entity_model_type


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **entityModelType** | **string** | Type of entity model to retrieve |  |

### Return type

[**CustodianModelConfigGetEntityModels200Response**](CustodianModelConfigGetEntityModels200Response.md)

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

<a id="custodianmodelconfigstore"></a>
# **CustodianModelConfigStore**
> CustodianModelConfigUpdate200Response CustodianModelConfigStore (CustodianModelConfig custodianModelConfig)

CustodianModelConfig@store

Create a CustodianModelConfig entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianModelConfig** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition |  |

### Return type

[**CustodianModelConfigUpdate200Response**](CustodianModelConfigUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianmodelconfigupdate"></a>
# **CustodianModelConfigUpdate**
> CustodianModelConfigUpdate200Response CustodianModelConfigUpdate (int id, CustodianModelConfig custodianModelConfig)

CustodianModelConfig@update

Update an CustodianModelConfig entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | CustodianModelConfig entry ID |  |
| **custodianModelConfig** | [**CustodianModelConfig**](CustodianModelConfig.md) | CustodianModelConfig definition |  |

### Return type

[**CustodianModelConfigUpdate200Response**](CustodianModelConfigUpdate200Response.md)

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

<a id="custodianmodelconfigupdateentitymodels"></a>
# **CustodianModelConfigUpdateEntityModels**
> CustodianModelConfigUpdateEntityModels200Response CustodianModelConfigUpdateEntityModels (int custodianId, CustodianModelConfigUpdateEntityModelsRequest custodianModelConfigUpdateEntityModelsRequest)

Update a custodian's entity models

Update the active status of specified custodian model configs for a given custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **custodianModelConfigUpdateEntityModelsRequest** | [**CustodianModelConfigUpdateEntityModelsRequest**](CustodianModelConfigUpdateEntityModelsRequest.md) |  |  |

### Return type

[**CustodianModelConfigUpdateEntityModels200Response**](CustodianModelConfigUpdateEntityModels200Response.md)

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
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

