# SafePeopleRegistryApiSdk.Api.VendorWebhookReceiverApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**VendorWebhookReceiverReceive**](VendorWebhookReceiverApi.md#vendorwebhookreceiverreceive) | **POST** /api/v1/vendor-webhooks/{provider} | Receive a webhook callback from a vendor |

<a id="vendorwebhookreceiverreceive"></a>
# **VendorWebhookReceiverReceive**
> VendorWebhookReceiverReceive200Response VendorWebhookReceiverReceive (string provider, Object body)

Receive a webhook callback from a vendor


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **provider** | **string** | Name of the vendor providing the webhook |  |
| **body** | **Object** |  |  |

### Return type

[**VendorWebhookReceiverReceive200Response**](VendorWebhookReceiverReceive200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | Webhook processed successfully |  -  |
| **400** | Invalid argument(s) |  -  |
| **500** | Internal server error |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

