# SafePeopleRegistryApiSdk.Api.DepartmentApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**DepartmentDestroy**](DepartmentApi.md#departmentdestroy) | **DELETE** /api/v1/departments/{id} | Delete a department |
| [**DepartmentIndex**](DepartmentApi.md#departmentindex) | **GET** /api/v1/departments | Get a list of departments |
| [**DepartmentShow**](DepartmentApi.md#departmentshow) | **GET** /api/v1/departments/{id} | Get a specific department by ID |
| [**DepartmentStore**](DepartmentApi.md#departmentstore) | **POST** /api/v1/departments | Create a new department |
| [**DepartmentUpdate**](DepartmentApi.md#departmentupdate) | **PUT** /api/v1/departments/{id} | Update an existing department |

<a id="departmentdestroy"></a>
# **DepartmentDestroy**
> AffiliationDestroy200Response DepartmentDestroy (int id)

Delete a department


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the department |  |

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
| **404** | Department not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="departmentindex"></a>
# **DepartmentIndex**
> List&lt;Department&gt; DepartmentIndex ()

Get a list of departments


### Parameters
This endpoint does not need any parameter.
### Return type

[**List&lt;Department&gt;**](Department.md)

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

<a id="departmentshow"></a>
# **DepartmentShow**
> Department DepartmentShow (int id)

Get a specific department by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the department |  |

### Return type

[**Department**](Department.md)

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
| **404** | Department not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="departmentstore"></a>
# **DepartmentStore**
> AccreditationStoreByRegistryId201Response DepartmentStore (Department department)

Create a new department


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **department** | [**Department**](Department.md) |  |  |

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

<a id="departmentupdate"></a>
# **DepartmentUpdate**
> Department DepartmentUpdate (int id, Department department)

Update an existing department


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | ID of the department |  |
| **department** | [**Department**](Department.md) |  |  |

### Return type

[**Department**](Department.md)

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
| **404** | Department not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

