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
**From** | **DateOnly** | Date affiliation commenced | [optional] 
**To** | **DateOnly** | Date affiliation ends (or ended). Null when there is no known end date | [optional] 
**EndDateRecordedAt** | **DateTime** | When the end date was recorded | [optional] 
**EndDateRecordedBy** | **int** | The user who recorded the end date | [optional] 
**EndDateSource** | **string** | Who recorded the end date. The organisation&#39;s date wins over the user&#39;s | [optional] 
**LeftAt** | **DateTime** | When the leaver flow ran for this affiliation | [optional] 
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

