# SafePeopleRegistryApiSdk.Api.ProjectHasOrganisationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProjectHasOrganisationShow**](ProjectHasOrganisationApi.md#projecthasorganisationshow) | **GET** /api/v1/project-organisations/{projectOrganisationId} | Get details of a project-organisation relationship |

<a id="projecthasorganisationshow"></a>
# **ProjectHasOrganisationShow**
> ProjectHasOrganisation ProjectHasOrganisationShow (int projectOrganisationId)

Get details of a project-organisation relationship


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **projectOrganisationId** | **int** | ID of the project-organisation relationship |  |

### Return type

[**ProjectHasOrganisation**](ProjectHasOrganisation.md)

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
| **404** | Project-organisation relationship not found |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

