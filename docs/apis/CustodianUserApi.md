# SafePeopleRegistryApiSdk.Api.CustodianUserApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianUserBulkStore**](CustodianUserApi.md#custodianuserbulkstore) | **POST** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries |
| [**CustodianUserDestroy**](CustodianUserApi.md#custodianuserdestroy) | **DELETE** /api/v1/custodian_users/{id} | CustodianUser@destroy |
| [**CustodianUserShow**](CustodianUserApi.md#custodianusershow) | **GET** /api/v1/custodian_users/{id} | CustodianUser@show |
| [**CustodianUserStore**](CustodianUserApi.md#custodianuserstore) | **POST** /api/v1/custodian_users | CustodianUser@store |
| [**CustodianUserUpdate**](CustodianUserApi.md#custodianuserupdate) | **PUT** /api/v1/custodian_users | CustodianUser@update |

<a id="custodianuserbulkstore"></a>
# **CustodianUserBulkStore**
> CustodianUserBulkStore201Response CustodianUserBulkStore (CustodianUserBulkStoreRequest custodianUserBulkStoreRequest)

Create multiple CustodianUser entries

Create multiple CustodianUser entries


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianUserBulkStoreRequest** | [**CustodianUserBulkStoreRequest**](CustodianUserBulkStoreRequest.md) | Array of CustodianUser definitions |  |

### Return type

[**CustodianUserBulkStore201Response**](CustodianUserBulkStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianuserdestroy"></a>
# **CustodianUserDestroy**
> AffiliationDestroy200Response CustodianUserDestroy (int id)

CustodianUser@destroy

Delete a CustodianUser entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | CustodianUser entry ID |  |

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

<a id="custodianusershow"></a>
# **CustodianUserShow**
> CustodianUserShow200Response CustodianUserShow (int id)

CustodianUser@show

Return a CustodianUser entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | CustodianUser entry ID |  |

### Return type

[**CustodianUserShow200Response**](CustodianUserShow200Response.md)

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

<a id="custodianuserstore"></a>
# **CustodianUserStore**
> AccreditationStoreByRegistryId201Response CustodianUserStore (CustodianUser custodianUser)

CustodianUser@store

Create a CustodianUser entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianUser** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition |  |

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
| **201** | Success |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="custodianuserupdate"></a>
# **CustodianUserUpdate**
> CustodianUserUpdate201Response CustodianUserUpdate (CustodianUser custodianUser)

CustodianUser@update

Update a CustodianUser entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianUser** | [**CustodianUser**](CustodianUser.md) | CustodianUser definition |  |

### Return type

[**CustodianUserUpdate201Response**](CustodianUserUpdate201Response.md)

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
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

