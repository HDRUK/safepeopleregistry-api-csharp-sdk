# SafePeopleRegistryApiSdk.Api.EndorsementsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**EndorsementsStore**](EndorsementsApi.md#endorsementsstore) | **POST** /api/v1/endorsements | Endorsements@store |

<a id="endorsementsstore"></a>
# **EndorsementsStore**
> EndorsementsStore201Response EndorsementsStore (EndorsementsStoreRequest endorsementsStoreRequest)

Endorsements@store

Create an Endorsements entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **endorsementsStoreRequest** | [**EndorsementsStoreRequest**](EndorsementsStoreRequest.md) | Endorsements definition |  |

### Return type

[**EndorsementsStore201Response**](EndorsementsStore201Response.md)

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

