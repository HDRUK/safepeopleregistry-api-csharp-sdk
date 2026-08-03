# SafePeopleRegistryApiSdk.Api.AffiliationApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**AffiliationDestroy**](AffiliationApi.md#affiliationdestroy) | **DELETE** /api/v1/training/{id} | Affiliation@destroy |

<a id="affiliationdestroy"></a>
# **AffiliationDestroy**
> AffiliationDestroy200Response AffiliationDestroy (int id)

Affiliation@destroy

Delete a affiliation entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Affiliation entry ID |  |

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
| **200** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

