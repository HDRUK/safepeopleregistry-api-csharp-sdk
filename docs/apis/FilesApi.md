# SafePeopleRegistryApiSdk.Api.FilesApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**FilesDownload**](FilesApi.md#filesdownload) | **GET** /api/v1/files/{id}/download | Download an uploaded file |
| [**FilesShow**](FilesApi.md#filesshow) | **GET** /api/v1/files/{id} | Files@show |
| [**FilesStore**](FilesApi.md#filesstore) | **POST** /api/v1/files | Files@store |

<a id="filesdownload"></a>
# **FilesDownload**
> System.IO.Stream FilesDownload (int id)

Download an uploaded file

Downloads the specified file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | File ID |  |

### Return type

**System.IO.Stream**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/octet-stream, application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | File downloaded successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | File not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="filesshow"></a>
# **FilesShow**
> FilesShow200Response FilesShow (int id)

Files@show

Gets an uploaded file


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | File ID |  |

### Return type

[**FilesShow200Response**](FilesShow200Response.md)

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
| **404** | Not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="filesstore"></a>
# **FilesStore**
> AccreditationStoreByRegistryId201Response FilesStore (int registryId = null, System.IO.Stream file = null, string fileType = null, string entityType = null)

Files@store

Uploads a file to the registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** |  | [optional]  |
| **file** | **System.IO.Stream****System.IO.Stream** |  | [optional]  |
| **fileType** | **string** |  | [optional]  |
| **entityType** | **string** |  | [optional]  |

### Return type

[**AccreditationStoreByRegistryId201Response**](AccreditationStoreByRegistryId201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **400** | Bad request |  -  |
| **201** | Success |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

