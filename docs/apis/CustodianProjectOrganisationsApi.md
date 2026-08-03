# SafePeopleRegistryApiSdk.Api.CustodianProjectOrganisationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianProjectOrganisationsGetWorkflowStates**](CustodianProjectOrganisationsApi.md#custodianprojectorganisationsgetworkflowstates) | **GET** /api/v1/custodian_approvals/projectOrganisations/getWorkflowStates | Get all workflow states for custodian project organisation approvals |
| [**CustodianProjectOrganisationsIndex**](CustodianProjectOrganisationsApi.md#custodianprojectorganisationsindex) | **GET** /api/v1/custodian_approvals/{custodianId}/projectOrganisations | List all project organisations associated with a custodian |
| [**CustodianProjectOrganisationsShow**](CustodianProjectOrganisationsApi.md#custodianprojectorganisationsshow) | **GET** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Get custodian approval for a project organisation |
| [**CustodianProjectOrganisationsUpdate**](CustodianProjectOrganisationsApi.md#custodianprojectorganisationsupdate) | **PUT** /api/v1/custodian_approvals/{custodianId}/projectOrganisations/{projectOrganisationId} | Update custodian approval for a project organisation |

<a id="custodianprojectorganisationsgetworkflowstates"></a>
# **CustodianProjectOrganisationsGetWorkflowStates**
> CustodianProjectOrganisationsGetWorkflowStates200Response CustodianProjectOrganisationsGetWorkflowStates ()

Get all workflow states for custodian project organisation approvals

Returns a list of all possible workflow states


### Parameters
This endpoint does not need any parameter.
### Return type

[**CustodianProjectOrganisationsGetWorkflowStates200Response**](CustodianProjectOrganisationsGetWorkflowStates200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianprojectorganisationsindex"></a>
# **CustodianProjectOrganisationsIndex**
> CustodianProjectOrganisationsIndex200Response CustodianProjectOrganisationsIndex (int custodianId)

List all project organisations associated with a custodian

Returns a list of all custodian project organisation approvals for a specific custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |

### Return type

[**CustodianProjectOrganisationsIndex200Response**](CustodianProjectOrganisationsIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **403** | Forbidden |  -  |
| **404** | Custodian Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianprojectorganisationsshow"></a>
# **CustodianProjectOrganisationsShow**
> CustodianProjectOrganisationsShow200Response CustodianProjectOrganisationsShow (int custodianId, int projectOrganisationId)

Get custodian approval for a project organisation

Returns custodian approval details for a specific project organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **projectOrganisationId** | **int** | ID of the project organisation |  |

### Return type

[**CustodianProjectOrganisationsShow200Response**](CustodianProjectOrganisationsShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianprojectorganisationsupdate"></a>
# **CustodianProjectOrganisationsUpdate**
> CustodianProjectOrganisationsShow200Response CustodianProjectOrganisationsUpdate (int custodianId, int projectOrganisationId, CustodianProjectOrganisationsUpdateRequest custodianProjectOrganisationsUpdateRequest)

Update custodian approval for a project organisation

Updates approval status and/or comment for a project organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **projectOrganisationId** | **int** | ID of the project organisation |  |
| **custodianProjectOrganisationsUpdateRequest** | [**CustodianProjectOrganisationsUpdateRequest**](CustodianProjectOrganisationsUpdateRequest.md) |  |  |

### Return type

[**CustodianProjectOrganisationsShow200Response**](CustodianProjectOrganisationsShow200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **403** | Forbidden |  -  |
| **404** | Not Found |  -  |
| **500** | Bad Request |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

