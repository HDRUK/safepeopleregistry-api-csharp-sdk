# SafePeopleRegistryApiSdk.Model.SsoTenant
An enterprise customer's SAML Identity Provider connection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int** | Model primary key | [optional] 
**CreatedAt** | **string** |  | [optional] 
**UpdatedAt** | **string** |  | [optional] 
**Name** | **string** |  | [optional] 
**IdpAlias** | **string** |  | [optional] 
**MetadataUrl** | **string** |  | [optional] 
**EntityId** | **string** |  | [optional] 
**MetadataImportedAt** | **string** |  | [optional] 
**Enabled** | **bool** |  | [optional] 
**SpEntityId** | **string** | Keycloak&#39;s own SP entity ID - null until approved. Register this as the SAML Identifier on the customer&#39;s IdP. | [optional] 
**SpAcsUrl** | **string** | Keycloak&#39;s ACS/reply URL for this tenant - null until approved. | [optional] 
**SpMetadataUrl** | **string** | Downloadable SP metadata descriptor most IdPs can import directly - null until approved. | [optional] 
**Status** | **string** | One of pending, approved, rejected | [optional] 
**SubmittedByUserId** | **int** | ID of the user who submitted this tenant for approval | [optional] 
**RejectedReason** | **string** | Reason given when status is rejected - null otherwise | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

