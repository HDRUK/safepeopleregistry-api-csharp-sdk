# SafePeopleRegistryApiSdk.Api.ActionLogsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ActionLogsGetEntityActionLog**](ActionLogsApi.md#actionlogsgetentityactionlog) | **GET** /api/v1/{entity}/{id}/action_log | Get Action Logs for an Entity |
| [**ActionLogsUpdate**](ActionLogsApi.md#actionlogsupdate) | **PUT** /api/v1/action_logs/{id} | Update an Action Log |

<a id="actionlogsgetentityactionlog"></a>
# **ActionLogsGetEntityActionLog**
> ActionLogsGetEntityActionLog200Response ActionLogsGetEntityActionLog (string entity, int id)

Get Action Logs for an Entity

Retrieve action logs for a given entity type (users, organisations) by ID.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **entity** | **string** | The entity type (e.g., users, organisations) |  |
| **id** | **int** | The ID of the entity |  |

### Return type

[**ActionLogsGetEntityActionLog200Response**](ActionLogsGetEntityActionLog200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response with action logs |  -  |
| **404** | No action logs found for this entity |  -  |
| **400** | Invalid entity type |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="actionlogsupdate"></a>
# **ActionLogsUpdate**
> ActionLogsUpdate200Response ActionLogsUpdate (int id, bool complete = null, bool incomplete = null)

Update an Action Log

Update an action log entry, including marking it as complete or incomplete.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the action log |  |
| **complete** | **bool** | Mark as complete | [optional]  |
| **incomplete** | **bool** | Mark as incomplete | [optional]  |

### Return type

[**ActionLogsUpdate200Response**](ActionLogsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Action status updated successfully |  -  |
| **404** | Action log not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

