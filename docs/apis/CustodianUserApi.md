# SafePeopleRegistryApiSdk.Api.CustodianUserApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianUserBulkStore**](CustodianUserApi.md#custodianuserbulkstore) | **POST** /api/v1/custodian_users/bulk | Create multiple CustodianUser entries |

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

