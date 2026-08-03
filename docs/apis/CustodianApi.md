# SafePeopleRegistryApiSdk.Api.CustodianApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianAddProject**](CustodianApi.md#custodianaddproject) | **POST** /api/v1/custodians/{custodianId}/projects | Custodian@addProject |
| [**CustodianDestroy**](CustodianApi.md#custodiandestroy) | **DELETE** /api/v1/custodians/{id} | Custodian@destroy |
| [**CustodianGetOrganisations**](CustodianApi.md#custodiangetorganisations) | **GET** /api/v1/custodian/{custodianId}/organisations | Return all custodian organisations with projects |
| [**CustodianGetProjects**](CustodianApi.md#custodiangetprojects) | **GET** /api/v1/custodian/{custodianId}/projects | Return all projects associated with a custodian |
| [**CustodianGetProjectsUsers**](CustodianApi.md#custodiangetprojectsusers) | **GET** /api/v1/custodians/{custodianId}/projects_users | Get all users associated with custodian&#39;s projects |
| [**CustodianGetUserProjects**](CustodianApi.md#custodiangetuserprojects) | **GET** /api/v1/custodian/{custodianId}/users/{userId}/projects | Return all custodian projects associated with a user |
| [**CustodianIndex**](CustodianApi.md#custodianindex) | **GET** /api/v1/custodians | Custodian@index |
| [**CustodianShow**](CustodianApi.md#custodianshow) | **GET** /api/v1/custodians/{id} | Custodian@show |
| [**CustodianShowByUniqueIdentifier**](CustodianApi.md#custodianshowbyuniqueidentifier) | **GET** /api/v1/custodians/identifier/{id} | Custodian@showByUniqueIdentifier |
| [**CustodianStore**](CustodianApi.md#custodianstore) | **POST** /api/v1/custodians | Custodian@store |
| [**CustodianUpdate**](CustodianApi.md#custodianupdate) | **PUT** /api/v1/custodians/{id} | Custodian@update |

<a id="custodianaddproject"></a>
# **CustodianAddProject**
> CustodianAddProject201Response CustodianAddProject (int custodianId, CustodianAddProjectRequest custodianAddProjectRequest)

Custodian@addProject

Create a project for a custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **custodianAddProjectRequest** | [**CustodianAddProjectRequest**](CustodianAddProjectRequest.md) | Project definition |  |

### Return type

[**CustodianAddProject201Response**](CustodianAddProject201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiandestroy"></a>
# **CustodianDestroy**
> AffiliationDestroy200Response CustodianDestroy (int id)

Custodian@destroy

Delete a Custodian entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Custodian entry ID |  |

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
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiangetorganisations"></a>
# **CustodianGetOrganisations**
> CustodianGetOrganisations200Response CustodianGetOrganisations (int custodianId)

Return all custodian organisations with projects

Fetch a list of custodians organisations with projects, along with pagination details.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian whose organisations are to be retrieved |  |

### Return type

[**CustodianGetOrganisations200Response**](CustodianGetOrganisations200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiangetprojects"></a>
# **CustodianGetProjects**
> CustodianGetProjects200Response CustodianGetProjects (int custodianId)

Return all projects associated with a custodian

Fetch a list of projects along with pagination details for a specified custodian.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian whose projects are to be retrieved |  |

### Return type

[**CustodianGetProjects200Response**](CustodianGetProjects200Response.md)

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
| **404** | Custodian not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiangetprojectsusers"></a>
# **CustodianGetProjectsUsers**
> CustodianGetProjectsUsers200Response CustodianGetProjectsUsers (int custodianId)

Get all users associated with custodian's projects

Returns paginated users for all projects under a specific custodian.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | Custodian ID |  |

### Return type

[**CustodianGetProjectsUsers200Response**](CustodianGetProjectsUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | List of users |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Custodian not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiangetuserprojects"></a>
# **CustodianGetUserProjects**
> CustodianGetUserProjects200Response CustodianGetUserProjects (int custodianId, int userId)

Return all custodian projects associated with a user

Fetch a list of custodians projects associated with a user, along with pagination details.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian whose projects are to be retrieved |  |
| **userId** | **int** | The ID of the user whose projects are to be retrieved |  |

### Return type

[**CustodianGetUserProjects200Response**](CustodianGetUserProjects200Response.md)

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
| **404** | User not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianindex"></a>
# **CustodianIndex**
> CustodianIndex200Response CustodianIndex ()

Custodian@index

Return a list of Custodians


### Parameters
This endpoint does not need any parameter.
### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

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

<a id="custodianshow"></a>
# **CustodianShow**
> CustodianIndex200Response CustodianShow (int id)

Custodian@show

Return an Custodian entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Custodian ID |  |

### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

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

<a id="custodianshowbyuniqueidentifier"></a>
# **CustodianShowByUniqueIdentifier**
> CustodianIndex200Response CustodianShowByUniqueIdentifier (string id)

Custodian@showByUniqueIdentifier

Return an Custodian entry by Unique Identifier


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **string** | Custodian Unique Identifier |  |

### Return type

[**CustodianIndex200Response**](CustodianIndex200Response.md)

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

<a id="custodianstore"></a>
# **CustodianStore**
> CustodianStore201Response CustodianStore (CustodianStoreRequest custodianStoreRequest)

Custodian@store

Create a Custodian entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianStoreRequest** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition |  |

### Return type

[**CustodianStore201Response**](CustodianStore201Response.md)

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

<a id="custodianupdate"></a>
# **CustodianUpdate**
> CustodianStore201Response CustodianUpdate (int id, CustodianStoreRequest custodianStoreRequest)

Custodian@update

Edit a Custodian entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Custodian ID |  |
| **custodianStoreRequest** | [**CustodianStoreRequest**](CustodianStoreRequest.md) | Custodian definition |  |

### Return type

[**CustodianStore201Response**](CustodianStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **200** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

