# SafePeopleRegistryApiSdk.Api.WebhooksApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**WebhooksCreateReceiver**](WebhooksApi.md#webhookscreatereceiver) | **POST** /api/v1/webhooks/receivers | Create a new webhook receiver |
| [**WebhooksDeleteReceiver**](WebhooksApi.md#webhooksdeletereceiver) | **DELETE** /api/v1/webhooks/receivers/{custodianId} | Delete a webhook receiver |
| [**WebhooksGetAllEventTriggers**](WebhooksApi.md#webhooksgetalleventtriggers) | **GET** /api/v1/webhooks/event-triggers | Get all webhook event triggers |
| [**WebhooksGetAllReceivers**](WebhooksApi.md#webhooksgetallreceivers) | **GET** /api/v1/webhooks/receivers | Get all webhook receivers |
| [**WebhooksGetReceiversByCustodian**](WebhooksApi.md#webhooksgetreceiversbycustodian) | **GET** /api/v1/webhooks/receivers/{custodianId} | Get webhook receivers by custodian |
| [**WebhooksSendgrid**](WebhooksApi.md#webhookssendgrid) | **GET** /api/v1/webhooks/sendgrid | Get sendgrid webhook event triggers |
| [**WebhooksUpdateReceiver**](WebhooksApi.md#webhooksupdatereceiver) | **PUT** /api/v1/webhooks/receivers/{custodianId} | Update a webhook receiver |

<a id="webhookscreatereceiver"></a>
# **WebhooksCreateReceiver**
> WebhooksCreateReceiver201Response WebhooksCreateReceiver (WebhooksCreateReceiverRequest webhooksCreateReceiverRequest)

Create a new webhook receiver

Creates a new webhook receiver for a custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **webhooksCreateReceiverRequest** | [**WebhooksCreateReceiverRequest**](WebhooksCreateReceiverRequest.md) |  |  |

### Return type

[**WebhooksCreateReceiver201Response**](WebhooksCreateReceiver201Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **201** | Successful operation |  -  |
| **422** | Validation error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhooksdeletereceiver"></a>
# **WebhooksDeleteReceiver**
> EducationDestroyByRegistryId200Response WebhooksDeleteReceiver (int custodianId, WebhooksDeleteReceiverRequest webhooksDeleteReceiverRequest)

Delete a webhook receiver

Deletes a specific webhook receiver for a custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** |  |  |
| **webhooksDeleteReceiverRequest** | [**WebhooksDeleteReceiverRequest**](WebhooksDeleteReceiverRequest.md) |  |  |

### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Webhook receiver not found |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhooksgetalleventtriggers"></a>
# **WebhooksGetAllEventTriggers**
> WebhooksGetAllEventTriggers200Response WebhooksGetAllEventTriggers ()

Get all webhook event triggers

Returns all webhook event triggers


### Parameters
This endpoint does not need any parameter.
### Return type

[**WebhooksGetAllEventTriggers200Response**](WebhooksGetAllEventTriggers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhooksgetallreceivers"></a>
# **WebhooksGetAllReceivers**
> WebhooksGetAllReceivers200Response WebhooksGetAllReceivers ()

Get all webhook receivers

Returns all webhook receivers with their associated event trigger details


### Parameters
This endpoint does not need any parameter.
### Return type

[**WebhooksGetAllReceivers200Response**](WebhooksGetAllReceivers200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhooksgetreceiversbycustodian"></a>
# **WebhooksGetReceiversByCustodian**
> WebhooksGetAllReceivers200Response WebhooksGetReceiversByCustodian (int custodianId)

Get webhook receivers by custodian

Returns all webhook receivers for a specific custodian with their associated event trigger details


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** |  |  |

### Return type

[**WebhooksGetAllReceivers200Response**](WebhooksGetAllReceivers200Response.md)

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

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhookssendgrid"></a>
# **WebhooksSendgrid**
> void WebhooksSendgrid ()

Get sendgrid webhook event triggers

Returns sendgrid webhook event triggers


### Parameters
This endpoint does not need any parameter.
### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

<a id="webhooksupdatereceiver"></a>
# **WebhooksUpdateReceiver**
> EducationDestroyByRegistryId200Response WebhooksUpdateReceiver (int custodianId, WebhooksUpdateReceiverRequest webhooksUpdateReceiverRequest)

Update a webhook receiver

Updates a specific webhook receiver for a custodian


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **custodianId** | **int** |  |  |
| **webhooksUpdateReceiverRequest** | [**WebhooksUpdateReceiverRequest**](WebhooksUpdateReceiverRequest.md) |  |  |

### Return type

[**EducationDestroyByRegistryId200Response**](EducationDestroyByRegistryId200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Successful operation |  -  |
| **400** | Invalid argument(s) |  -  |
| **404** | Webhook receiver not found |  -  |
| **422** | Validation error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

