# SafePeopleRegistryApiSdk.Api.ProfessionalRegistrationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ProfessionalRegistrationsUpdate**](ProfessionalRegistrationsApi.md#professionalregistrationsupdate) | **PUT** /api/v1/professional_registrations/{id} | Professional Registrations@update |

<a id="professionalregistrationsupdate"></a>
# **ProfessionalRegistrationsUpdate**
> ProfessionalRegistrationsUpdate200Response ProfessionalRegistrationsUpdate (int id, ProfessionalRegistrationsUpdateRequest professionalRegistrationsUpdateRequest)

Professional Registrations@update

Update a Professional Registrations entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Professional Registrations entry ID |  |
| **professionalRegistrationsUpdateRequest** | [**ProfessionalRegistrationsUpdateRequest**](ProfessionalRegistrationsUpdateRequest.md) | Professional Registrations definition |  |

### Return type

[**ProfessionalRegistrationsUpdate200Response**](ProfessionalRegistrationsUpdate200Response.md)

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

