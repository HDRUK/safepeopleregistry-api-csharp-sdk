# SafePeopleRegistryApiSdk.Api.ONSSubmissionApi

All URIs are relative to *http://localhost*

| Method | HTTP request | Description |
|--------|--------------|-------------|
| [**ONSSubmissionReceiveCSV**](ONSSubmissionApi.md#onssubmissionreceivecsv) | **POST** /api/v1/ons-submissions/csv | Upload a CSV file for ONS submission |

<a id="onssubmissionreceivecsv"></a>
# **ONSSubmissionReceiveCSV**
> ONSSubmissionReceiveCSV200Response ONSSubmissionReceiveCSV (System.IO.Stream file = null)

Upload a CSV file for ONS submission


### Parameters

| Name | Type | Description | Notes |
|------|------|-------------|-------|
| **file** | **System.IO.Stream****System.IO.Stream** | CSV file to upload | [optional]  |

### Return type

[**ONSSubmissionReceiveCSV200Response**](ONSSubmissionReceiveCSV200Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | File uploaded successfully |  -  |
| **400** | File upload failed |  -  |

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

