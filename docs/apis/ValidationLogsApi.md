# SafePeopleRegistryApiSdk.Api.ValidationLogsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ValidationLogsGetCustodianOrganisationValidationLogs**](ValidationLogsApi.md#validationlogsgetcustodianorganisationvalidationlogs) | **GET** /api/v1/custodians/{custodianId}/organisation/{organisationId}/validation_logs | Get Validation Logs for Custodian and Organisation |
| [**ValidationLogsGetCustodianProjectUserValidationLogs**](ValidationLogsApi.md#validationlogsgetcustodianprojectuservalidationlogs) | **GET** /api/v1/custodians/{custodianId}/projects/{projectId}/registries/{registryId}/validation_logs | Get Validation Logs for Custodian, Project, and Registry |
| [**ValidationLogsUpdate**](ValidationLogsApi.md#validationlogsupdate) | **PUT** /api/v1/validation_logs/{id} | Update a Validation Log |
| [**ValidationLogsUpdateCustodianValidationLogs**](ValidationLogsApi.md#validationlogsupdatecustodianvalidationlogs) | **PUT** /api/v1/custodians/{custodianId}/validation_Logs | Enable or Disable All Validation Logs for a Custodian Across Projects/Registries |

<a id="validationlogsgetcustodianorganisationvalidationlogs"></a>
# **ValidationLogsGetCustodianOrganisationValidationLogs**
> ValidationLogsGetCustodianProjectUserValidationLogs200Response ValidationLogsGetCustodianOrganisationValidationLogs (int custodianId, int organisationId, bool showDisabled = null)

Get Validation Logs for Custodian and Organisation

Retrieve validation logs associated with a given custodian and organisation.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian entity |  |
| **organisationId** | **int** | The ID of the organisation entity |  |
| **showDisabled** | **bool** | Whether to include disabled validation logs | [optional]  |

### Return type

[**ValidationLogsGetCustodianProjectUserValidationLogs200Response**](ValidationLogsGetCustodianProjectUserValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response with validation logs |  -  |
| **404** | Custodian or Organisation not found |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogsgetcustodianprojectuservalidationlogs"></a>
# **ValidationLogsGetCustodianProjectUserValidationLogs**
> ValidationLogsGetCustodianProjectUserValidationLogs200Response ValidationLogsGetCustodianProjectUserValidationLogs (int custodianId, int projectId, int registryId)

Get Validation Logs for Custodian, Project, and Registry

Retrieve validation logs associated with a given custodian, project, and registry.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian entity |  |
| **projectId** | **int** | The ID of the project entity |  |
| **registryId** | **int** | The ID of the registry entity |  |

### Return type

[**ValidationLogsGetCustodianProjectUserValidationLogs200Response**](ValidationLogsGetCustodianProjectUserValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful response with validation logs |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogsupdate"></a>
# **ValidationLogsUpdate**
> ValidationLogsUpdate200Response ValidationLogsUpdate (int id, ValidationLogsUpdateRequest validationLogsUpdateRequest = null)

Update a Validation Log

Update a validation log entry, including marking it as complete, incomplete, passed, or failed.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | The ID of the validation log entry |  |
| **validationLogsUpdateRequest** | [**ValidationLogsUpdateRequest**](ValidationLogsUpdateRequest.md) |  | [optional]  |

### Return type

[**ValidationLogsUpdate200Response**](ValidationLogsUpdate200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation log status updated successfully |  -  |
| **404** | Validation log not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="validationlogsupdatecustodianvalidationlogs"></a>
# **ValidationLogsUpdateCustodianValidationLogs**
> ValidationLogsUpdateCustodianValidationLogs200Response ValidationLogsUpdateCustodianValidationLogs (int custodianId, ValidationLogsUpdateCustodianValidationLogsRequest validationLogsUpdateCustodianValidationLogsRequest)

Enable or Disable All Validation Logs for a Custodian Across Projects/Registries

Bulk update the enabled flag for all validation logs tied to a custodian and any project/registry.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | The ID of the custodian entity |  |
| **validationLogsUpdateCustodianValidationLogsRequest** | [**ValidationLogsUpdateCustodianValidationLogsRequest**](ValidationLogsUpdateCustodianValidationLogsRequest.md) |  |  |

### Return type

[**ValidationLogsUpdateCustodianValidationLogs200Response**](ValidationLogsUpdateCustodianValidationLogs200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation logs updated successfully |  -  |
| **400** | Invalid request |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

