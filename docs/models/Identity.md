# SafePeopleRegistryApiSdk.Model.Identity
Model representing identity records

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int** | Unique identifier for the identity record | [optional] 
**RegistryId** | **int** | ID of the registry associated with the identity record | [optional] 
**Address1** | **string** | First line of the address | [optional] 
**Address2** | **string** | Second line of the address | [optional] 
**Town** | **string** | Town of the address | [optional] 
**County** | **string** | County of the address | [optional] 
**Country** | **string** | Country of the address | [optional] 
**Postcode** | **string** | Postcode of the address | [optional] 
**Dob** | **DateOnly** | Date of birth | [optional] 
**IdvtSuccess** | **int** | Indicates whether IDVT was successful (1 for success, 0 for failure) | [optional] 
**IdvtIdentificationNumber** | **string** | Identification number from IDVT | [optional] 
**IdvtDocumentType** | **string** | Type of document used for IDVT | [optional] 
**IdvtDocumentNumber** | **string** | Document number used for IDVT | [optional] 
**IdvtDocumentCountry** | **string** | Country of the document used for IDVT | [optional] 
**IdvtDocumentValidUntil** | **DateOnly** | Validity date of the document used for IDVT | [optional] 
**IdvtAttemptId** | **string** | ID of the IDVT attempt | [optional] 
**IdvtContextId** | **string** | Context ID for IDVT | [optional] 
**IdvtDocumentDob** | **DateOnly** | Date of birth on the document used for IDVT | [optional] 
**IdvtContext** | **string** | Context of the IDVT process | [optional] 
**IdvtCompletedAt** | **DateTime** | Timestamp when IDVT was completed | [optional] 
**IdvtResultText** | **string** | Result text of the IDVT process | [optional] 
**IdvtStartedAt** | **DateTime** | Timestamp when IDVT was started | [optional] 
**CreatedAt** | **DateTime** | Timestamp when the identity record was created | [optional] 
**UpdatedAt** | **DateTime** | Timestamp when the identity record was last updated | [optional] 
**DeletedAt** | **DateTime** | Timestamp when the identity record was deleted | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

