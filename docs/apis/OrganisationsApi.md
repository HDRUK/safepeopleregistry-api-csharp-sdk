# SafePeopleRegistryApiSdk.Api.OrganisationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**OrganisationsAppointSro**](OrganisationsApi.md#organisationsappointsro) | **PUT** /api/v1/organisations/{id}/sro | organisations@appointSro |
| [**OrganisationsInviteSro**](OrganisationsApi.md#organisationsinvitesro) | **POST** /api/v1/organisations/{id}/sro/invite | organisations@inviteSro |
| [**OrganisationsRemoveDelegate**](OrganisationsApi.md#organisationsremovedelegate) | **DELETE** /api/v1/organisations/{id}/delegates/{userId} | organisations@removeDelegate |
| [**OrganisationsResendSroInvite**](OrganisationsApi.md#organisationsresendsroinvite) | **POST** /api/v1/organisations/{id}/sro/resend_invite | organisations@resendSroInvite |

<a id="organisationsappointsro"></a>
# **OrganisationsAppointSro**
> OrganisationsAppointSro200Response OrganisationsAppointSro (int id, OrganisationsAppointSroRequest organisationsAppointSroRequest)

organisations@appointSro

Hands the SRO role over immediately: the appointee becomes SRO, the current SRO becomes a delegate, and an invited SRO keeps their invitation but will join as a delegate. Delegates can appoint while the organisation has no claimed SRO; after that only the SRO can.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisationsAppointSroRequest** | [**OrganisationsAppointSroRequest**](OrganisationsAppointSroRequest.md) |  |  |

### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

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
| **403** | Forbidden |  -  |
| **404** | The user is not a claimed member of this organisation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsinvitesro"></a>
# **OrganisationsInviteSro**
> OrganisationsInviteSro201Response OrganisationsInviteSro (int id, OrganisationsInviteSroRequest organisationsInviteSroRequest)

organisations@inviteSro

Creates an invited (unclaimed) SRO and emails them an invitation. The current SRO keeps the role until the invitee claims their account; any other invited SRO keeps their invitation but will join as a delegate. Delegates can invite while the organisation has no claimed SRO; after that only the SRO can.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisationsInviteSroRequest** | [**OrganisationsInviteSroRequest**](OrganisationsInviteSroRequest.md) |  |  |

### Return type

[**OrganisationsInviteSro201Response**](OrganisationsInviteSro201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Created |  -  |
| **400** | Invalid argument(s) |  -  |
| **403** | Forbidden |  -  |
| **409** | The email already belongs to a user; appoint an existing member with PUT /organisations/{id}/sro instead |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsremovedelegate"></a>
# **OrganisationsRemoveDelegate**
> OrganisationsAppointSro200Response OrganisationsRemoveDelegate (int id, int userId)

organisations@removeDelegate

Detaches a delegate from the organisation and notifies them and the remaining members. The SRO and delegates of the organisation can remove other delegates; the SRO cannot be removed and nobody can remove themselves.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **userId** | **int** | ID of the delegate to remove |  |

### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

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
| **403** | Forbidden |  -  |
| **404** | The user is not a delegate of this organisation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsresendsroinvite"></a>
# **OrganisationsResendSroInvite**
> OrganisationsAppointSro200Response OrganisationsResendSroInvite (int id)

organisations@resendSroInvite

Resends the pending SRO invitation with the code it already has. Delegates can resend while the organisation has no claimed SRO; after that only the SRO can.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |

### Return type

[**OrganisationsAppointSro200Response**](OrganisationsAppointSro200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Success |  -  |
| **403** | Forbidden |  -  |
| **404** | The organisation has no pending SRO invitation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

