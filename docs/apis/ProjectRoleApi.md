# SafePeopleRegistryApiSdk.Api.ProjectRoleApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectRoleIndex**](ProjectRoleApi.md#projectroleindex) | **GET** /api/v1/project_roles | ProjectRole@index |
| [**ProjectRoleShow**](ProjectRoleApi.md#projectroleshow) | **GET** /api/v1/project_roles/{id} | ProjectRole@show |
| [**ProjectRoleStore**](ProjectRoleApi.md#projectrolestore) | **POST** /api/v1/project_roles | ProjectRole@store |
| [**ProjectRoleUpdate**](ProjectRoleApi.md#projectroleupdate) | **PUT** /api/v1/project_roles/{id} | ProjectRole@update |

<a id="projectroleindex"></a>
# **ProjectRoleIndex**
> ProjectRoleIndex200Response ProjectRoleIndex ()

ProjectRole@index

Return a list of ProjectRole


### Parameters
This endpoint does not need any parameter.
### Return type

[**ProjectRoleIndex200Response**](ProjectRoleIndex200Response.md)

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

<a id="projectroleshow"></a>
# **ProjectRoleShow**
> ProjectRoleIndex200Response ProjectRoleShow (int id)

ProjectRole@show

Return a ProjectRole


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ProjectRole entry ID |  |

### Return type

[**ProjectRoleIndex200Response**](ProjectRoleIndex200Response.md)

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

<a id="projectrolestore"></a>
# **ProjectRoleStore**
> IdentityStore201Response ProjectRoleStore (ProjectRole projectRole)

ProjectRole@store

Create a ProjectRole


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **projectRole** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition |  |

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

<a id="projectroleupdate"></a>
# **ProjectRoleUpdate**
> ProjectRoleUpdate200Response ProjectRoleUpdate (int id, ProjectRole projectRole)

ProjectRole@update

Update a ProjectRole entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ProjectRole entry ID |  |
| **projectRole** | [**ProjectRole**](ProjectRole.md) | ProjectRole definition |  |

### Return type

[**ProjectRoleUpdate200Response**](ProjectRoleUpdate200Response.md)

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

