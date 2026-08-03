# SafePeopleRegistryApiSdk.Api.CustodiansApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodiansCreateCustodianValidationChecks**](CustodiansApi.md#custodianscreatecustodianvalidationchecks) | **POST** /api/v1/custodians/{custodianId}/validation_checks | Assign a validation check to a custodian |
| [**CustodiansGetCustodianUsers**](CustodiansApi.md#custodiansgetcustodianusers) | **GET** /api/v1/custodians/{custodianId}/custodian_users | Get list of people for a custodian |
| [**CustodiansGetCustodianValidationChecks**](CustodiansApi.md#custodiansgetcustodianvalidationchecks) | **GET** /api/v1/custodians/{custodianId}/validation_checks | Get validation checks assigned to a custodian |
| [**CustodiansGetOrganisationUsers**](CustodiansApi.md#custodiansgetorganisationusers) | **GET** /api/v1/custodians/{custodianId}/organisations/{organisationId}/users | Get list of people for organisation |
| [**CustodiansGetRules**](CustodiansApi.md#custodiansgetrules) | **GET** /api/v1/custodians/{id}/rules | Get rules for a specific custodian |
| [**CustodiansGetStatusesUsers**](CustodiansApi.md#custodiansgetstatusesusers) | **GET** /api/v1/custodians/{custodianId}/projectUsers/{projectUserId}/statuses | Get statuses for a user in a project/organisation/custodian |

<a id="custodianscreatecustodianvalidationchecks"></a>
# **CustodiansCreateCustodianValidationChecks**
> ValidationCheck CustodiansCreateCustodianValidationChecks (int custodianId, CustodiansCreateCustodianValidationChecksRequest custodiansCreateCustodianValidationChecksRequest)

Assign a validation check to a custodian

Creates a new validation check and assigns it to a specific custodian via the custodian_has_validation_check pivot table.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **custodiansCreateCustodianValidationChecksRequest** | [**CustodiansCreateCustodianValidationChecksRequest**](CustodiansCreateCustodianValidationChecksRequest.md) |  |  |

### Return type

[**ValidationCheck**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Validation check created and assigned successfully |  -  |
| **400** | Invalid input |  -  |
| **404** | Custodian not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiansgetcustodianusers"></a>
# **CustodiansGetCustodianUsers**
> CustodiansGetCustodianUsers200Response CustodiansGetCustodianUsers (int custodianId)

Get list of people for a custodian

Fetches the list of custodian users based on the custodian id.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |

### Return type

[**CustodiansGetCustodianUsers200Response**](CustodiansGetCustodianUsers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successfully retrieved custodian users |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Custodian users not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiansgetcustodianvalidationchecks"></a>
# **CustodiansGetCustodianValidationChecks**
> List&lt;ValidationCheck&gt; CustodiansGetCustodianValidationChecks (int custodianId)

Get validation checks assigned to a custodian

Returns the list of validation checks associated with a specific custodian.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |

### Return type

[**List&lt;ValidationCheck&gt;**](ValidationCheck.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Validation checks retrieved successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Custodian not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiansgetorganisationusers"></a>
# **CustodiansGetOrganisationUsers**
> CustodiansGetOrganisationUsers200Response CustodiansGetOrganisationUsers (int custodianId, int organisationId)

Get list of people for organisation

Fetches the list of users associated with the given custodian and organisations IDs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **organisationId** | **int** | ID of the organisation |  |

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

<a id="custodiansgetrules"></a>
# **CustodiansGetRules**
> CustodiansGetRules200Response CustodiansGetRules (int id)

Get rules for a specific custodian

Fetches the list of rules associated with the given custodian ID.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the custodian |  |

### Return type

[**CustodiansGetRules200Response**](CustodiansGetRules200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successfully retrieved rules |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Custodian not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodiansgetstatusesusers"></a>
# **CustodiansGetStatusesUsers**
> CustodiansGetOrganisationUsers200Response CustodiansGetStatusesUsers (int custodianId, int projectUserId)

Get statuses for a user in a project/organisation/custodian

Fetches the user statuses given custodian and organisations and project and user IDs.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **projectUserId** | **int** | ID of the project user |  |

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

