# SafePeopleRegistryApiSdk.Api.SectorApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**SectorDestroy**](SectorApi.md#sectordestroy) | **DELETE** /api/v1/sectors/{id} | Delete a sector |
| [**SectorIndex**](SectorApi.md#sectorindex) | **GET** /api/v1/sectors | Get a list of sectors |
| [**SectorShow**](SectorApi.md#sectorshow) | **GET** /api/v1/sectors/{id} | Get a specific sector by ID |
| [**SectorStore**](SectorApi.md#sectorstore) | **POST** /api/v1/sectors | Create a new sector |
| [**SectorUpdate**](SectorApi.md#sectorupdate) | **PUT** /api/v1/sectors/{id} | Update an existing sector |

<a id="sectordestroy"></a>
# **SectorDestroy**
> AffiliationDestroy200Response SectorDestroy (int id)

Delete a sector


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the sector |  |

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
| **200** | Deleted |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Sector not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="sectorindex"></a>
# **SectorIndex**
> List&lt;Sector&gt; SectorIndex ()

Get a list of sectors


### Parameters
This endpoint does not need any parameter.
### Return type

[**List&lt;Sector&gt;**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="sectorshow"></a>
# **SectorShow**
> Sector SectorShow (int id)

Get a specific sector by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the sector |  |

### Return type

[**Sector**](Sector.md)

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
| **404** | Sector not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="sectorstore"></a>
# **SectorStore**
> AccreditationStoreByRegistryId201Response SectorStore (Sector sector)

Create a new sector


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **sector** | [**Sector**](Sector.md) |  |  |

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
| **201** | Created |  -  |
| **400** | Validation error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="sectorupdate"></a>
# **SectorUpdate**
> Sector SectorUpdate (int id, Sector sector)

Update an existing sector


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the sector |  |
| **sector** | [**Sector**](Sector.md) |  |  |

### Return type

[**Sector**](Sector.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Updated |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Sector not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

