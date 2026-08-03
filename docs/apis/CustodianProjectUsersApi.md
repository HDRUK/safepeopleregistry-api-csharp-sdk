# SafePeopleRegistryApiSdk.Api.CustodianProjectUsersApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianProjectUsersIndex**](CustodianProjectUsersApi.md#custodianprojectusersindex) | **GET** /api/v1/custodian_approvals/{custodianId}/projectUsers | List all project users associated with a custodian |
| [**CustodianProjectUsersShow**](CustodianProjectUsersApi.md#custodianprojectusersshow) | **GET** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Get custodian approval for a project user |
| [**CustodianProjectUsersUpdate**](CustodianProjectUsersApi.md#custodianprojectusersupdate) | **PUT** /api/v1/custodian_approvals/{custodianId}/projectUsers/{projectUserId} | Update custodian approval for a project user |

<a id="custodianprojectusersindex"></a>
# **CustodianProjectUsersIndex**
> CustodianProjectUsersIndex200Response CustodianProjectUsersIndex (int custodianId)

List all project users associated with a custodian

Returns a list of all custodian project user approvals for a specific custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |

### Return type

[**CustodianProjectUsersIndex200Response**](CustodianProjectUsersIndex200Response.md)

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

<a id="custodianprojectusersshow"></a>
# **CustodianProjectUsersShow**
> CustodianProjectUsersShow200Response CustodianProjectUsersShow (int custodianId, int projectUserId)

Get custodian approval for a project user

Returns custodian approval details for a specific project user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **projectUserId** | **int** | ID of the project user |  |

### Return type

[**CustodianProjectUsersShow200Response**](CustodianProjectUsersShow200Response.md)

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

<a id="custodianprojectusersupdate"></a>
# **CustodianProjectUsersUpdate**
> CustodianProjectUsersShow200Response CustodianProjectUsersUpdate (int custodianId, int projectUserId, CustodianProjectUsersUpdateRequest custodianProjectUsersUpdateRequest)

Update custodian approval for a project user

Updates approval status and/or comment for a project user


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | ID of the custodian |  |
| **projectUserId** | **int** | ID of the project user |  |
| **custodianProjectUsersUpdateRequest** | [**CustodianProjectUsersUpdateRequest**](CustodianProjectUsersUpdateRequest.md) |  |  |

### Return type

[**CustodianProjectUsersShow200Response**](CustodianProjectUsersShow200Response.md)

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

