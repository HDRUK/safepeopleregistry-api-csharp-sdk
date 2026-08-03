# SafePeopleRegistryApiSdk.Api.PermissionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**PermissionDestroy**](PermissionApi.md#permissiondestroy) | **DELETE** /api/v1/permissions/{id} | Permission@destroy |
| [**PermissionIndex**](PermissionApi.md#permissionindex) | **GET** /api/v1/permissions | Permission@index |
| [**PermissionShow**](PermissionApi.md#permissionshow) | **GET** /api/v1/permissions/{id} | Permission@show |
| [**PermissionStore**](PermissionApi.md#permissionstore) | **POST** /api/v1/permissions | Permission@store |
| [**PermissionUpdate**](PermissionApi.md#permissionupdate) | **PATCH** /api/v1/permissions/{id} | Permission@update |

<a id="permissiondestroy"></a>
# **PermissionDestroy**
> AffiliationDestroy200Response PermissionDestroy (int id)

Permission@destroy

Delete a Permission entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Permission entry ID |  |

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
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="permissionindex"></a>
# **PermissionIndex**
> PermissionIndex200Response PermissionIndex ()

Permission@index

Return a list of Permissions


### Parameters
This endpoint does not need any parameter.
### Return type

[**PermissionIndex200Response**](PermissionIndex200Response.md)

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

<a id="permissionshow"></a>
# **PermissionShow**
> PermissionIndex200Response PermissionShow (int id)

Permission@show

Return a Permission entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Permission entry ID |  |

### Return type

[**PermissionIndex200Response**](PermissionIndex200Response.md)

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

<a id="permissionstore"></a>
# **PermissionStore**
> AccreditationStoreByRegistryId201Response PermissionStore (PermissionStoreRequest permissionStoreRequest)

Permission@store

Create a Permission entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **permissionStoreRequest** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition |  |

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

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

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="permissionupdate"></a>
# **PermissionUpdate**
> PermissionUpdate200Response PermissionUpdate (int id, PermissionStoreRequest permissionStoreRequest)

Permission@update

Update a Permission entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Permission entry ID |  |
| **permissionStoreRequest** | [**PermissionStoreRequest**](PermissionStoreRequest.md) | Permission definition |  |

### Return type

[**PermissionUpdate200Response**](PermissionUpdate200Response.md)

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

