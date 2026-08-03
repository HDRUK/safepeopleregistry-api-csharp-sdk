# SafePeopleRegistryApiSdk.Api.IdentityApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**IdentityDestroy**](IdentityApi.md#identitydestroy) | **DELETE** /api/v1/identities/{id} | Identity@destroy |
| [**IdentityIndex**](IdentityApi.md#identityindex) | **GET** /api/v1/identities | Identity@index |
| [**IdentityShow**](IdentityApi.md#identityshow) | **GET** /api/v1/identities/{id} | Identity@show |
| [**IdentityStore**](IdentityApi.md#identitystore) | **POST** /api/v1/identities | Identity@store |
| [**IdentityUpdate**](IdentityApi.md#identityupdate) | **PUT** /api/v1/identities/{id} | Identity@update |

<a id="identitydestroy"></a>
# **IdentityDestroy**
> AffiliationDestroy200Response IdentityDestroy (int id)

Identity@destroy

Delete an Identity entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Identity entry ID |  |

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

<a id="identityindex"></a>
# **IdentityIndex**
> IdentityIndex200Response IdentityIndex ()

Identity@index

Return a list of Identity entries


### Parameters
This endpoint does not need any parameter.
### Return type

[**IdentityIndex200Response**](IdentityIndex200Response.md)

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

<a id="identityshow"></a>
# **IdentityShow**
> IdentityIndex200Response IdentityShow (int id)

Identity@show

Return an Identity entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Identity ID |  |

### Return type

[**IdentityIndex200Response**](IdentityIndex200Response.md)

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

<a id="identitystore"></a>
# **IdentityStore**
> IdentityStore201Response IdentityStore (IdentityStoreRequest identityStoreRequest)

Identity@store

Create a Identity entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **identityStoreRequest** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition |  |

### Return type

[**IdentityStore201Response**](IdentityStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Success |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="identityupdate"></a>
# **IdentityUpdate**
> IdentityUpdate200Response IdentityUpdate (int id, IdentityStoreRequest identityStoreRequest)

Identity@update

Update a Identity entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Identity entry ID |  |
| **identityStoreRequest** | [**IdentityStoreRequest**](IdentityStoreRequest.md) | Identity definition |  |

### Return type

[**IdentityUpdate200Response**](IdentityUpdate200Response.md)

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
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

