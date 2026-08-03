# SafePeopleRegistryApiSdk.Api.OrganisationsApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**CustodianProjectOrganisationsGetStatus**](OrganisationsApi.md#custodianprojectorganisationsgetstatus) | **GET** /api/v1/custodian_approvals/{custodianId}/project/{projectId}/organisation/{organisationId}/projectOrganisations/status | Get project organisation status |
| [**OrganisationsCustodianInviteUser**](OrganisationsApi.md#organisationscustodianinviteuser) | **POST** /api/v1/organisations/{id}/custodian_invite_user | organisations@custodian_invite_user |
| [**OrganisationsDestroy**](OrganisationsApi.md#organisationsdestroy) | **DELETE** /api/v1/organisations/{id} | organisations@destroy |
| [**OrganisationsGetRegistries**](OrganisationsApi.md#organisationsgetregistries) | **GET** /api/v1/organisations/{id}/registries | Get all registries for an organisation |
| [**OrganisationsGetStatus**](OrganisationsApi.md#organisationsgetstatus) | **GET** /api/v1/organisations/{id}/status | Get organisation status |
| [**OrganisationsIdvt**](OrganisationsApi.md#organisationsidvt) | **GET** /api/v1/organisations/{id}/idvt | organisations@idvt |
| [**OrganisationsInviteUser**](OrganisationsApi.md#organisationsinviteuser) | **POST** /api/v1/organisations/{id}/invite_user | organisations@invite_user |
| [**OrganisationsShow**](OrganisationsApi.md#organisationsshow) | **GET** /api/v1/organisations/{id} | organisations@show |
| [**OrganisationsStore**](OrganisationsApi.md#organisationsstore) | **POST** /api/v1/organisations | organisations@store |
| [**OrganisationsUpdate**](OrganisationsApi.md#organisationsupdate) | **PUT** /api/v1/organisations/{id} | organisations@update |
| [**OrganisationsUpdateApproved**](OrganisationsApi.md#organisationsupdateapproved) | **PUT** /api/v1/organisations/{id}/approved | SuperAdmin update org system_approved flag |

<a id="custodianprojectorganisationsgetstatus"></a>
# **CustodianProjectOrganisationsGetStatus**
> CustodianProjectOrganisationsGetStatus200Response CustodianProjectOrganisationsGetStatus (int custodianId, int projectId, int organisationId)

Get project organisation status

Retrieve the status of a project organisation for a specific custodian using custodianId, projectId, and organisationId.


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** | Custodian ID |  |
| **projectId** | **int** | Project ID |  |
| **organisationId** | **int** | Organisation ID |  |

### Return type

[**CustodianProjectOrganisationsGetStatus200Response**](CustodianProjectOrganisationsGetStatus200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Organisation or custodian project organisation not found |  -  |
| **500** | Server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationscustodianinviteuser"></a>
# **OrganisationsCustodianInviteUser**
> AccreditationStoreByRegistryId201Response OrganisationsCustodianInviteUser (int id, OrganisationsInviteUserRequest organisationsInviteUserRequest)

organisations@custodian_invite_user

Invites a user to org


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisationsInviteUserRequest** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition |  |

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
| **201** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsdestroy"></a>
# **OrganisationsDestroy**
> AffiliationDestroy200Response OrganisationsDestroy (int id)

organisations@destroy

Delete an organisations entry from the system


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |

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

<a id="organisationsgetregistries"></a>
# **OrganisationsGetRegistries**
> OrganisationsGetRegistries200Response OrganisationsGetRegistries (long id, bool showPending = null)

Get all registries for an organisation

Returns all registries associated with the specified organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **long** | Organisation ID |  |
| **showPending** | **bool** | Include users with pending invitations (true/false) | [optional]  |

### Return type

[**OrganisationsGetRegistries200Response**](OrganisationsGetRegistries200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | No registries found for this organisation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsgetstatus"></a>
# **OrganisationsGetStatus**
> CustodianProjectOrganisationsGetStatus200Response OrganisationsGetStatus (int id)

Get organisation status

Returns the organisation with its model state and state


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | Organisation ID |  |

### Return type

[**CustodianProjectOrganisationsGetStatus200Response**](CustodianProjectOrganisationsGetStatus200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Organisation not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsidvt"></a>
# **OrganisationsIdvt**
> OrganisationsIdvt200Response OrganisationsIdvt (int id)

organisations@idvt

Return an organisations idvt details by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |

### Return type

[**OrganisationsIdvt200Response**](OrganisationsIdvt200Response.md)

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

<a id="organisationsinviteuser"></a>
# **OrganisationsInviteUser**
> AccreditationStoreByRegistryId201Response OrganisationsInviteUser (int id, OrganisationsInviteUserRequest organisationsInviteUserRequest)

organisations@invite_user

Invites a user to org


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisationsInviteUserRequest** | [**OrganisationsInviteUserRequest**](OrganisationsInviteUserRequest.md) | Invite definition |  |

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
| **201** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **403** | forbidden |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="organisationsshow"></a>
# **OrganisationsShow**
> OrganisationIndex200Response OrganisationsShow (int id)

organisations@show

Return an organisations entry by ID


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |

### Return type

[**OrganisationIndex200Response**](OrganisationIndex200Response.md)

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

<a id="organisationsstore"></a>
# **OrganisationsStore**
> IdentityStore201Response OrganisationsStore (Organisation organisation)

organisations@store

Create a organisations entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **organisation** | [**Organisation**](Organisation.md) | organisations definition |  |

### Return type

[**IdentityStore201Response**](IdentityStore201Response.md)

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

<a id="organisationsupdate"></a>
# **OrganisationsUpdate**
> OrganisationsUpdate200Response OrganisationsUpdate (int id, Organisation organisation)

organisations@update

Update a organisations entry


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisation** | [**Organisation**](Organisation.md) | organisations definition |  |

### Return type

[**OrganisationsUpdate200Response**](OrganisationsUpdate200Response.md)

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

<a id="organisationsupdateapproved"></a>
# **OrganisationsUpdateApproved**
> AccreditationStoreByRegistryId201Response OrganisationsUpdateApproved (int id, OrganisationsUpdateApprovedRequest organisationsUpdateApprovedRequest)

SuperAdmin update org system_approved flag

Updates the system_approved flag for an organisation


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **id** | **int** | organisations entry ID |  |
| **organisationsUpdateApprovedRequest** | [**OrganisationsUpdateApprovedRequest**](OrganisationsUpdateApprovedRequest.md) | System approval update definition |  |

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
| **201** | Success |  -  |
| **400** | Invalid argument(s) |  -  |
| **500** | Error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

