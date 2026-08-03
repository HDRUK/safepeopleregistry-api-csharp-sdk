# SafePeopleRegistryApiSdk.Api.ValidationLogCommentsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ValidationLogCommentsComments**](ValidationLogCommentsApi.md#validationlogcommentscomments) | **GET** /api/v1/validation_logs/{id}/comments | Get all comments for a Validation Log |
| [**ValidationLogCommentsDestroy**](ValidationLogCommentsApi.md#validationlogcommentsdestroy) | **DELETE** /api/v1/validation_log_comments/{id} | Delete a validation log comment |
| [**ValidationLogCommentsShow**](ValidationLogCommentsApi.md#validationlogcommentsshow) | **GET** /api/v1/validation_log_comments/{id} | Get a single validation log comment |
| [**ValidationLogCommentsStore**](ValidationLogCommentsApi.md#validationlogcommentsstore) | **POST** /api/v1/validation_log_comments | Create a new validation log comment |
| [**ValidationLogCommentsUpdate**](ValidationLogCommentsApi.md#validationlogcommentsupdate) | **PUT** /api/v1/validation_log_comments/{id} | Update a validation log comment |

<a id="validationlogcommentscomments"></a>
# **ValidationLogCommentsComments**
> List&lt;ValidationLog&gt; ValidationLogCommentsComments (int id)

Get all comments for a Validation Log

Retrieve all comments associated with a specific validation log entry.


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

<a id="validationlogcommentsdestroy"></a>
# **ValidationLogCommentsDestroy**
> ValidationLogCommentsDestroy200Response ValidationLogCommentsDestroy (int id)

Delete a validation log comment

Remove a comment from the validation logs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | The ID of the comment |  |

### Return type

[**ValidationLogCommentsDestroy200Response**](ValidationLogCommentsDestroy200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Comment deleted successfully |  -  |
| **400** | Comment not found |  -  |
| **404** | Comment not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogcommentsshow"></a>
# **ValidationLogCommentsShow**
> ValidationLogComment ValidationLogCommentsShow (int id)

Get a single validation log comment

Retrieve a specific validation log comment by ID.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | The ID of the comment |  |

### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Comment retrieved successfully |  -  |
| **400** | Comment not found |  -  |
| **404** | Comment not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogcommentsstore"></a>
# **ValidationLogCommentsStore**
> ValidationLogComment ValidationLogCommentsStore (ValidationLogCommentsStoreRequest validationLogCommentsStoreRequest)

Create a new validation log comment

Add a new comment to a validation log.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **validationLogCommentsStoreRequest** | [**ValidationLogCommentsStoreRequest**](ValidationLogCommentsStoreRequest.md) |  |  |

### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Comment created successfully |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogcommentsupdate"></a>
# **ValidationLogCommentsUpdate**
> ValidationLogComment ValidationLogCommentsUpdate (int id, ValidationLogCommentsUpdateRequest validationLogCommentsUpdateRequest)

Update a validation log comment

Edit an existing validation log comment.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | The ID of the comment |  |
| **validationLogCommentsUpdateRequest** | [**ValidationLogCommentsUpdateRequest**](ValidationLogCommentsUpdateRequest.md) |  |  |

### Return type

[**ValidationLogComment**](ValidationLogComment.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Comment updated successfully |  -  |
| **400** | Comment not found |  -  |
| **404** | Comment not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

