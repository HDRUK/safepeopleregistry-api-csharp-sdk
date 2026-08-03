# SafePeopleRegistryApiSdk.Api.OrganisationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**OrganisationGetDelegates**](OrganisationApi.md#organisationgetdelegates) | **GET** /api/v1/organisations/{id}/delegates | Return all delegates associated with an organisation |
| [**OrganisationGetProjects**](OrganisationApi.md#organisationgetprojects) | **GET** /api/v1/organisations/{id}/projects | organisation@getProjects |
| [**OrganisationGetSponsorshipsProjects**](OrganisationApi.md#organisationgetsponsorshipsprojects) | **GET** /api/v1/organisations/{id}/projects/sponsorships | organisation@getSponsorshipsProjects |
| [**OrganisationGetUsers**](OrganisationApi.md#organisationgetusers) | **GET** /api/v1/organisations/{id}/users | organisation@getUsers |
| [**OrganisationIndex**](OrganisationApi.md#organisationindex) | **GET** /api/v1/organisations | organisation@index |

<a id="organisationgetdelegates"></a>
# **OrganisationGetDelegates**
> OrganisationGetDelegates200Response OrganisationGetDelegates (int id)

Return all delegates associated with an organisation

Return all delegates associated with an organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Organisation ID |  |

### Return type

[**OrganisationGetDelegates200Response**](OrganisationGetDelegates200Response.md)

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

<a id="organisationgetprojects"></a>
# **OrganisationGetProjects**
> OrganisationGetProjects200Response OrganisationGetProjects (int id)

organisation@getProjects

Return an all projects associated with an organisation (i.e. data-custodian)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Organisation ID |  |

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

<a id="organisationgetsponsorshipsprojects"></a>
# **OrganisationGetSponsorshipsProjects**
> OrganisationGetProjects200Response OrganisationGetSponsorshipsProjects (int id)

organisation@getSponsorshipsProjects

Return an all projects associated with an organisation with sponsorships (i.e. data-custodian)


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Organisation ID |  |

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

<a id="organisationgetusers"></a>
# **OrganisationGetUsers**
> OrganisationGetUsers200Response OrganisationGetUsers (int id)

organisation@getUsers

Return all users associated with an organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Organisation ID |  |

### Return type

[**OrganisationGetUsers200Response**](OrganisationGetUsers200Response.md)

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

<a id="organisationindex"></a>
# **OrganisationIndex**
> OrganisationIndex200Response OrganisationIndex ()

organisation@index

Return a list of organisations


### Parameters
This endpoint does not need any parameter.
### Return type

[**OrganisationIndex200Response**](OrganisationIndex200Response.md)

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

