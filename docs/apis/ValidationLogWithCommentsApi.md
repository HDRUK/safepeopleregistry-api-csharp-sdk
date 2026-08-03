# SafePeopleRegistryApiSdk.Api.ValidationLogWithCommentsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ValidationLogWithCommentsIndex**](ValidationLogWithCommentsApi.md#validationlogwithcommentsindex) | **GET** /api/v1/validation_logs/{id} | Get  a Validation Log |

<a id="validationlogwithcommentsindex"></a>
# **ValidationLogWithCommentsIndex**
> List&lt;ValidationLog&gt; ValidationLogWithCommentsIndex (int id)

Get  a Validation Log

Retrieve a specific entry for a validation log .


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | The ID of the validation log |  |

### Return type

[**List&lt;ValidationLog&gt;**](ValidationLog.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation log with comments |  -  |
| **404** | Validation log not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

