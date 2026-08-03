# SafePeopleRegistryApiSdk.Api.EndorsementApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**EndorsementIndex**](EndorsementApi.md#endorsementindex) | **GET** /api/v1/endorsements | Endorsement@index |
| [**EndorsementShow**](EndorsementApi.md#endorsementshow) | **GET** /api/v1/endorsements/{id} | Endorsement@show |

<a id="endorsementindex"></a>
# **EndorsementIndex**
> EndorsementIndex200Response EndorsementIndex ()

Endorsement@index

Return a list of Endorsements


### Parameters
This endpoint does not need any parameter.
### Return type

[**EndorsementIndex200Response**](EndorsementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="endorsementshow"></a>
# **EndorsementShow**
> EndorsementIndex200Response EndorsementShow (int id)

Endorsement@show

Return an Endorsement entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Endorsement entry ID |  |

### Return type

[**EndorsementIndex200Response**](EndorsementIndex200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **404** | Not found response |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

