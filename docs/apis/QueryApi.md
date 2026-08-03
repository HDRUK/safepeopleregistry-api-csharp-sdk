# SafePeopleRegistryApiSdk.Api.QueryApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**QueryQuery**](QueryApi.md#queryquery) | **POST** /api/v1/query | Query@query |

<a id="queryquery"></a>
# **QueryQuery**
> QueryQuery200Response QueryQuery (string xClientId, QueryQueryRequest queryQueryRequest)

Query@query

Query the registry by Digital Identifier


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **xClientId** | **string** | Custodian client ID used to authenticate the requesting custodian |  |
| **queryQueryRequest** | [**QueryQueryRequest**](QueryQueryRequest.md) | Query definition |  |

### Return type

[**QueryQuery200Response**](QueryQuery200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **401** | Unauthorised - missing or unrecognised x-client-id header |  -  |
| **404** | Not found response |  -  |
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

