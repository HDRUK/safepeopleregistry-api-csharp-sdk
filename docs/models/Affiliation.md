# SafePeopleRegistryApiSdk.Model.Affiliation
Affiliation model

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int** | Model primary key | [optional] 
**CreatedAt** | **string** |  | [optional] 
**UpdatedAt** | **string** |  | [optional] 
**OrganisationId** | **int** | Organisational link | [optional] 
**MemberId** | **string** | Member ID UUID | [optional] 
**Relationship** | **string** | Textual representation of affiliation relationship | [optional] 
**From** | **string** | Date affiliation commenced | [optional] 
**To** | **string** | Date affiliation concluded | [optional] 
**Department** | **string** | Department worked during affiliation | [optional] 
**Role** | **string** | Role held during affiliation | [optional] 
**Email** | **string** | Professional email held during affiliation | [optional] 
**Ror** | **string** | The ROR.org identifier for this affiliation institute | [optional] 
**RegistryId** | **int** | The Registry primary key associated with this affiliation | [optional] 
**CurrentEmployer** | **bool** | Flag indicating if affiliation is for the current employer | [optional] 
**VerificationCode** | **string** | Unique verification code issued for confirmation | [optional] 
**VerificationSentAt** | **DateTime** | Timestamp when verification code was sent | [optional] 
**VerificationConfirmedAt** | **DateTime** | Timestamp when verification was confirmed | [optional] 
**IsVerified** | **bool** | Flag indicating if affiliation is verified | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

