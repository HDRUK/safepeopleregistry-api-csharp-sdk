# SafePeopleRegistryApiSdk.Api.ValidationChecksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ValidationChecksDestroy**](ValidationChecksApi.md#validationchecksdestroy) | **DELETE** /api/v1/validation_checks/{id} | Delete a validation check |
| [**ValidationChecksIndex**](ValidationChecksApi.md#validationchecksindex) | **GET** /api/v1/validation_checks | List all validation checks |
| [**ValidationChecksShow**](ValidationChecksApi.md#validationchecksshow) | **GET** /api/v1/validation_checks/{id} | Get a single validation check |
| [**ValidationChecksStore**](ValidationChecksApi.md#validationchecksstore) | **POST** /api/v1/validation_checks | Create a new validation check |
| [**ValidationChecksUpdate**](ValidationChecksApi.md#validationchecksupdate) | **PUT** /api/v1/validation_checks/{id} | Update a validation check |

<a id="validationchecksdestroy"></a>
# **ValidationChecksDestroy**
> ValidationChecksDestroy200Response ValidationChecksDestroy (int id)

Delete a validation check

Remove a validation check.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the validation check |  |

### Return type

[**ValidationChecksDestroy200Response**](ValidationChecksDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation check deleted successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Validation check not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationchecksindex"></a>
# **ValidationChecksIndex**
> List&lt;ValidationCheck&gt; ValidationChecksIndex ()

List all validation checks

Retrieve all validation checks.


### Parameters
This endpoint does not need any parameter.
### Return type

[**List&lt;ValidationCheck&gt;**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation checks retrieved successfully |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationchecksshow"></a>
# **ValidationChecksShow**
> ValidationCheck ValidationChecksShow (int id)

Get a single validation check

Retrieve a specific validation check by ID.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the validation check |  |

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation check retrieved successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Validation check not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationchecksstore"></a>
# **ValidationChecksStore**
> ValidationCheck ValidationChecksStore (ValidationChecksStoreRequest validationChecksStoreRequest)

Create a new validation check

Create a new validation check entry.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **validationChecksStoreRequest** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  |  |

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Validation check created successfully |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationchecksupdate"></a>
# **ValidationChecksUpdate**
> ValidationCheck ValidationChecksUpdate (int id, ValidationChecksStoreRequest validationChecksStoreRequest)

Update a validation check

Edit an existing validation check.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the validation check |  |
| **validationChecksStoreRequest** | [**ValidationChecksStoreRequest**](ValidationChecksStoreRequest.md) |  |  |

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation check updated successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Validation check not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

