# CyberSource.Model.PtsV2PaymentsPost201ResponseProcessorInformationCustomer
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PersonalIdResult** | **string** | Personal identifier result. This field is supported only for Redecard in Brazil for CyberSource Latin American Processing. If you included _buyerInformation.personalIdentification[].ID_ in the request, this value indicates whether or not _buyerInformation.personalIdentification[].ID_ matched a value in a record on file. Returned only when the personal ID result is returned by the processor.  Possible values:   - **Y**: Match  - **N**: No match  - **K**: Not supported  - **U**: Unknown  - **Z**: No response returned  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

