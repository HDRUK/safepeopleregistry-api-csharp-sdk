# SafePeopleRegistryApiSdk.Api.AffiliationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**AffiliationsGetOrganisationAffiliation**](AffiliationsApi.md#affiliationsgetorganisationaffiliation) | **GET** /api/v1/affiliations/{registryId}/organisation/{organisationId} | Return a specific organisation&#39;s affiliation by registry ID and organisation ID |
| [**AffiliationsIndexByRegistryId**](AffiliationsApi.md#affiliationsindexbyregistryid) | **GET** /api/v1/affiliations/{registryId} | Affiliations@show |
| [**AffiliationsStoreByRegistryId**](AffiliationsApi.md#affiliationsstorebyregistryid) | **POST** /api/v1/affiliations/{registryId} | Affiliations@store |
| [**AffiliationsUpdate**](AffiliationsApi.md#affiliationsupdate) | **PUT** /api/v1/affiliations/{id} | Affiliations@update |
| [**AffiliationsVerifyEmail**](AffiliationsApi.md#affiliationsverifyemail) | **PUT** /api/v1/affiliations/verify_email/{verificationCode} | Affiliations@verifyEmail |

<a id="affiliationsgetorganisationaffiliation"></a>
# **AffiliationsGetOrganisationAffiliation**
> AffiliationsGetOrganisationAffiliation200Response AffiliationsGetOrganisationAffiliation (int registryId, int organisationId)

Return a specific organisation's affiliation by registry ID and organisation ID

Get a specific organisation's affiliation for a given registry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | Registry ID |  |
| **organisationId** | **int** | Organisation ID |  |

### Return type

[**AffiliationsGetOrganisationAffiliation200Response**](AffiliationsGetOrganisationAffiliation200Response.md)

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
| **404** | Affiliation not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="affiliationsindexbyregistryid"></a>
# **AffiliationsIndexByRegistryId**
> AffiliationsIndexByRegistryId200Response AffiliationsIndexByRegistryId (int registryId)

Affiliations@show

Return a list of affiliations by registry id


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | Affiliations registry id |  |

### Return type

[**AffiliationsIndexByRegistryId200Response**](AffiliationsIndexByRegistryId200Response.md)

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

<a id="affiliationsstorebyregistryid"></a>
# **AffiliationsStoreByRegistryId**
> AffiliationsStoreByRegistryId200Response AffiliationsStoreByRegistryId (int registryId, Affiliation affiliation)

Affiliations@store

Create an Affiliation entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **registryId** | **int** | Registry entry ID |  |
| **affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition |  |

### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

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

<a id="affiliationsupdate"></a>
# **AffiliationsUpdate**
> AffiliationsStoreByRegistryId200Response AffiliationsUpdate (int id, Affiliation affiliation)

Affiliations@update

Update an Affiliation entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Affiliation entry ID |  |
| **affiliation** | [**Affiliation**](Affiliation.md) | Affiliation definition |  |

### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

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

<a id="affiliationsverifyemail"></a>
# **AffiliationsVerifyEmail**
> AffiliationsStoreByRegistryId200Response AffiliationsVerifyEmail (string verificationCode)

Affiliations@verifyEmail

Update an Affiliation entry with verification


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **verificationCode** | **string** | Email verification code |  |

### Return type

[**AffiliationsStoreByRegistryId200Response**](AffiliationsStoreByRegistryId200Response.md)

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

