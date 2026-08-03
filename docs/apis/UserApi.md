# SafePeopleRegistryApiSdk.Api.UserApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**UserDestroy**](UserApi.md#userdestroy) | **DELETE** /api/v1/users/{id} | User@destroy |
| [**UserIndex**](UserApi.md#userindex) | **GET** /api/v1/users | User@index |
| [**UserShow**](UserApi.md#usershow) | **GET** /api/v1/users/{id} | User@show |
| [**UserUpdate**](UserApi.md#userupdate) | **PUT** /api/v1/users/{id} | User@update |

<a id="userdestroy"></a>
# **UserDestroy**
> AffiliationDestroy200Response UserDestroy (int id)

User@destroy

Delete a User entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User entry ID |  |

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
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="userindex"></a>
# **UserIndex**
> UserIndex200Response UserIndex ()

User@index

Return a list of Users


### Parameters
This endpoint does not need any parameter.
### Return type

[**UserIndex200Response**](UserIndex200Response.md)

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

<a id="usershow"></a>
# **UserShow**
> UserShow200Response UserShow (int id)

User@show

Return a User entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |

### Return type

[**UserShow200Response**](UserShow200Response.md)

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

<a id="userupdate"></a>
# **UserUpdate**
> UserUpdate200Response UserUpdate (int id, UserUpdateRequest userUpdateRequest)

User@update

Edit a User entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | User ID |  |
| **userUpdateRequest** | [**UserUpdateRequest**](UserUpdateRequest.md) | User definition |  |

### Return type

[**UserUpdate200Response**](UserUpdate200Response.md)

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
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

