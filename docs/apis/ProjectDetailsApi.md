# SafePeopleRegistryApiSdk.Api.ProjectDetailsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectDetailsDestroy**](ProjectDetailsApi.md#projectdetailsdestroy) | **DELETE** /api/v1/project_details/{id} | ProjectDetails@destroy |
| [**ProjectDetailsStore**](ProjectDetailsApi.md#projectdetailsstore) | **POST** /api/v1/project_details | ProjectDetails@store |
| [**ProjectDetailsUpdate**](ProjectDetailsApi.md#projectdetailsupdate) | **PUT** /api/v1/project_details/{id} | ProjectDetails@update |

<a id="projectdetailsdestroy"></a>
# **ProjectDetailsDestroy**
> AffiliationDestroy200Response ProjectDetailsDestroy (int id)

ProjectDetails@destroy

Delete a ProjectDetail entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ProjectDetails entry ID |  |

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

<a id="projectdetailsstore"></a>
# **ProjectDetailsStore**
> IdentityStore201Response ProjectDetailsStore (ProjectDetail projectDetail)

ProjectDetails@store

Create a ProjectDetail


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **projectDetail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetail definition |  |

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
| **404** | Not found response |  -  |
| **201** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectdetailsupdate"></a>
# **ProjectDetailsUpdate**
> ProjectDetailsUpdate200Response ProjectDetailsUpdate (int id, ProjectDetail projectDetail)

ProjectDetails@update

Update a ProjectDetail entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ProjectDetails entry ID |  |
| **projectDetail** | [**ProjectDetail**](ProjectDetail.md) | ProjectDetails definition |  |

### Return type

[**ProjectDetailsUpdate200Response**](ProjectDetailsUpdate200Response.md)

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

