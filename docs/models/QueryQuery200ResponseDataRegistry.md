# SafePeopleRegistryApiSdk.Model.QueryQuery200ResponseDataRegistry
The matched Registry record

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int** |  | [optional] 
**CreatedAt** | **string** |  | [optional] 
**UpdatedAt** | **string** |  | [optional] 
**DeletedAt** | **string** |  | [optional] 
**DigiIdent** | **string** |  | [optional] 
**DlIdent** | **string** |  | [optional] 
**PpIdent** | **string** |  | [optional] 
**Verified** | **int** |  | [optional] 
**Training** | [**List&lt;Training&gt;**](Training.md) | Training records linked to the registry | [optional] 
**History** | [**List&lt;QueryQuery200ResponseDataRegistryAllOfHistoryInner&gt;**](QueryQuery200ResponseDataRegistryAllOfHistoryInner.md) | History records linked to the registry, each with its related affiliation and project | [optional] 

[[Back to Model list]](../../README.md#documentation-for-models) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to README]](../../README.md)

