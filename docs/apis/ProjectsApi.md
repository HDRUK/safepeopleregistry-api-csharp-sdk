# SafePeopleRegistryApiSdk.Api.ProjectsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectsDelete**](ProjectsApi.md#projectsdelete) | **DELETE** /api/v1/project_users/{id} | ProjectHasUser@delete |
| [**ProjectsGetValidatedProjects**](ProjectsApi.md#projectsgetvalidatedprojects) | **GET** /api/v1/projects/user/{registryId}/validated | Project@getValidatedProjects |

<a id="projectsdelete"></a>
# **ProjectsDelete**
> void ProjectsDelete (int id)

ProjectHasUser@delete

Delete a user from a project


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID |  |

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | success |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | failed |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectsgetvalidatedprojects"></a>
# **ProjectsGetValidatedProjects**
> OrganisationGetProjects200Response ProjectsGetValidatedProjects (int registryId)

Project@getValidatedProjects

Return (approved) projects for a registry (user)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | Registry ID |  |

### Return type

[**OrganisationGetProjects200Response**](OrganisationGetProjects200Response.md)

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

