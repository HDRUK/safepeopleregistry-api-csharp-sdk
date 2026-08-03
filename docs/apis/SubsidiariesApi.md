# SafePeopleRegistryApiSdk.Api.SubsidiariesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SubsidiariesDestroy**](SubsidiariesApi.md#subsidiariesdestroy) | **DELETE** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@destroy |
| [**SubsidiariesStore**](SubsidiariesApi.md#subsidiariesstore) | **POST** /api/v1/subsidiaries/organisations/{organisationId} | subsidiaries@store |
| [**SubsidiariesUpdate**](SubsidiariesApi.md#subsidiariesupdate) | **PUT** /api/v1/subsidiaries/{subsidiaryId}/organisations/{organisationId} | subsidiaries@update |

<a id="subsidiariesdestroy"></a>
# **SubsidiariesDestroy**
> AffiliationDestroy200Response SubsidiariesDestroy (int organisationId, int subsidiaryId)

subsidiaries@destroy

Delete an subsidiary entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisationId** | **int** | organisations entry ID |  |
| **subsidiaryId** | **int** | subsidiary entry ID |  |

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

<a id="subsidiariesstore"></a>
# **SubsidiariesStore**
> SubsidiariesStore201Response SubsidiariesStore (int organisationId, Subsidiary subsidiary)

subsidiaries@store

Create a subsidiary entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisationId** | **int** | organisations entry ID |  |
| **subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition |  |

### Return type

[**SubsidiariesStore201Response**](SubsidiariesStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="subsidiariesupdate"></a>
# **SubsidiariesUpdate**
> SubsidiariesStore201Response SubsidiariesUpdate (int organisationId, int subsidiaryId, Subsidiary subsidiary)

subsidiaries@update

Update a subsidiary entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisationId** | **int** | organisations entry ID |  |
| **subsidiaryId** | **int** | subsidiary entry ID |  |
| **subsidiary** | [**Subsidiary**](Subsidiary.md) | subsidiary definition |  |

### Return type

[**SubsidiariesStore201Response**](SubsidiariesStore201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Not found response |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

