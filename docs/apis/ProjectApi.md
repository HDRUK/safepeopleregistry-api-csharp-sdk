# SafePeopleRegistryApiSdk.Api.ProjectApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectDestroy**](ProjectApi.md#projectdestroy) | **DELETE** /api/v1/projects/{id} | Project@destroy |
| [**ProjectGetAllUsersFlagProjectByUserId**](ProjectApi.md#projectgetallusersflagprojectbyuserid) | **GET** /api/v1/projects/{projectId}/all_users/{userId} | Get all users by projectID and userID |
| [**ProjectGetProjectByIdAndOrganisationId**](ProjectApi.md#projectgetprojectbyidandorganisationid) | **GET** /api/v1/projects/{projectId}/organisations/{organisationId} | Get project details by projectID and organisationID |
| [**ProjectGetProjectByIdAndUserId**](ProjectApi.md#projectgetprojectbyidanduserid) | **GET** /api/v1/projects/{projectId}/users/{userId} | Get project details by projectID and userID |
| [**ProjectGetProjectUsers**](ProjectApi.md#projectgetprojectusers) | **GET** /api/v1/projects/{id}/users | Project@getProjectUsers |
| [**ProjectGetProjectUsersByOrganisationId**](ProjectApi.md#projectgetprojectusersbyorganisationid) | **GET** /api/v1/projects/{projectId}/organisations/{organisationId}/users | Get all users by projectID and organisationID |
| [**ProjectIndex**](ProjectApi.md#projectindex) | **GET** /api/v1/projects | Project@index |
| [**ProjectMakePrimaryContact**](ProjectApi.md#projectmakeprimarycontact) | **PUT** /api/v1/projects/{id}/users/{registryId}/primary_contact | Project@edit |
| [**ProjectShow**](ProjectApi.md#projectshow) | **GET** /api/v1/projects/{id} | Project@show |
| [**ProjectStore**](ProjectApi.md#projectstore) | **POST** /api/v1/projects | Project@store |
| [**ProjectUpdate**](ProjectApi.md#projectupdate) | **PUT** /api/v1/projects/{id} | Project@update |
| [**ProjectUpdateAllProjectUsers**](ProjectApi.md#projectupdateallprojectusers) | **PUT** /api/v1/projects/{id}/all_users | Project@updateAllProjectUsers |

<a id="projectdestroy"></a>
# **ProjectDestroy**
> AffiliationDestroy200Response ProjectDestroy (int id)

Project@destroy

Delete a Project entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |

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

<a id="projectgetallusersflagprojectbyuserid"></a>
# **ProjectGetAllUsersFlagProjectByUserId**
> ProjectGetAllUsersFlagProjectByUserId200Response ProjectGetAllUsersFlagProjectByUserId (int userId, int projectId)

Get all users by projectID and userID

Fetches users for a project.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | ID of the user |  |
| **projectId** | **int** | ID of the project |  |

### Return type

[**ProjectGetAllUsersFlagProjectByUserId200Response**](ProjectGetAllUsersFlagProjectByUserId200Response.md)

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
| **403** | Forbidden |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectgetprojectbyidandorganisationid"></a>
# **ProjectGetProjectByIdAndOrganisationId**
> CustodiansGetOrganisationUsers200Response ProjectGetProjectByIdAndOrganisationId (int organisationId, int projectId)

Get project details by projectID and organisationID

Fetches project given organisation and project IDs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisationId** | **int** | ID of the organisation |  |
| **projectId** | **int** | ID of the project |  |

### Return type

[**CustodiansGetOrganisationUsers200Response**](CustodiansGetOrganisationUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successfully retrieved project |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Project not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectgetprojectbyidanduserid"></a>
# **ProjectGetProjectByIdAndUserId**
> ProjectGetProjectByIdAndUserId200Response ProjectGetProjectByIdAndUserId (int userId, int projectId)

Get project details by projectID and userID

Fetches project given user and project IDs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **userId** | **int** | ID of the user |  |
| **projectId** | **int** | ID of the project |  |

### Return type

[**ProjectGetProjectByIdAndUserId200Response**](ProjectGetProjectByIdAndUserId200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successfully retrieved project |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Project not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectgetprojectusers"></a>
# **ProjectGetProjectUsers**
> ProjectGetProjectUsers200Response ProjectGetProjectUsers (int id)

Project@getProjectUsers

Return project users by project ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |

### Return type

[**ProjectGetProjectUsers200Response**](ProjectGetProjectUsers200Response.md)

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

<a id="projectgetprojectusersbyorganisationid"></a>
# **ProjectGetProjectUsersByOrganisationId**
> CustodiansGetOrganisationUsers200Response ProjectGetProjectUsersByOrganisationId (int organisationId, int projectId)

Get all users by projectID and organisationID

Fetches users given organisation and project IDs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisationId** | **int** | ID of the organisation |  |
| **projectId** | **int** | ID of the project |  |

### Return type

[**CustodiansGetOrganisationUsers200Response**](CustodiansGetOrganisationUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successfully retrieved organisation users |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Organisation users not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="projectindex"></a>
# **ProjectIndex**
> ProjectIndex200Response ProjectIndex ()

Project@index

Return a list of Projects


### Parameters
This endpoint does not need any parameter.
### Return type

[**ProjectIndex200Response**](ProjectIndex200Response.md)

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

<a id="projectmakeprimarycontact"></a>
# **ProjectMakePrimaryContact**
> ProjectMakePrimaryContact200Response ProjectMakePrimaryContact (int id, int registryId, ProjectMakePrimaryContactRequest projectMakePrimaryContactRequest)

Project@edit

Make user a primary contact


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |
| **registryId** | **int** | Registry ID |  |
| **projectMakePrimaryContactRequest** | [**ProjectMakePrimaryContactRequest**](ProjectMakePrimaryContactRequest.md) | Project definition |  |

### Return type

[**ProjectMakePrimaryContact200Response**](ProjectMakePrimaryContact200Response.md)

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

<a id="projectshow"></a>
# **ProjectShow**
> ProjectIndex200Response ProjectShow (int id)

Project@show

Return a Project entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |

### Return type

[**ProjectIndex200Response**](ProjectIndex200Response.md)

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

<a id="projectstore"></a>
# **ProjectStore**
> AccreditationStoreByRegistryId201Response ProjectStore (ProjectStoreRequest projectStoreRequest)

Project@store

Create a Project entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **projectStoreRequest** | [**ProjectStoreRequest**](ProjectStoreRequest.md) | Project definition |  |

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

<a id="projectupdate"></a>
# **ProjectUpdate**
> ProjectUpdate200Response ProjectUpdate (int id, ProjectIndex200ResponseData projectIndex200ResponseData)

Project@update

Update a Project entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |
| **projectIndex200ResponseData** | [**ProjectIndex200ResponseData**](ProjectIndex200ResponseData.md) | Project definition |  |

### Return type

[**ProjectUpdate200Response**](ProjectUpdate200Response.md)

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

<a id="projectupdateallprojectusers"></a>
# **ProjectUpdateAllProjectUsers**
> ONSSubmissionReceiveCSV200Response ProjectUpdateAllProjectUsers (int id, ProjectUpdateAllProjectUsersRequest projectUpdateAllProjectUsersRequest)

Project@updateAllProjectUsers

Update all users associated with a project


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Project entry ID |  |
| **projectUpdateAllProjectUsersRequest** | [**ProjectUpdateAllProjectUsersRequest**](ProjectUpdateAllProjectUsersRequest.md) | Project definition |  |

### Return type

[**ONSSubmissionReceiveCSV200Response**](ONSSubmissionReceiveCSV200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success response |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

