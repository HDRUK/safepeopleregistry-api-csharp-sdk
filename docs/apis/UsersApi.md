# SafePeopleRegistryApiSdk.Api.UsersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**UsersStore**](UsersApi.md#usersstore) | **POST** /api/v1/users | Users@store |

<a id="usersstore"></a>
# **UsersStore**
> UsersStore201Response UsersStore (UsersStoreRequest usersStoreRequest)

Users@store

Create a User entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **usersStoreRequest** | [**UsersStoreRequest**](UsersStoreRequest.md) | User definition |  |

### Return type

[**UsersStore201Response**](UsersStore201Response.md)

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

