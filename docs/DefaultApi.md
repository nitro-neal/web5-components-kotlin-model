# DefaultApi

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**credentialIssue**](DefaultApi.md#credentialIssue) | **POST** /credentials/issue | 


<a id="credentialIssue"></a>
# **credentialIssue**
> CredentialIssuanceResponse credentialIssue(credentialIssuanceRequest)



### Example
```kotlin
// Import classes:
//import org.openapitools.client.infrastructure.*
//import org.openapitools.client.models.*

val apiInstance = DefaultApi()
val credentialIssuanceRequest : CredentialIssuanceRequest =  // CredentialIssuanceRequest | 
try {
    val result : CredentialIssuanceResponse = apiInstance.credentialIssue(credentialIssuanceRequest)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling DefaultApi#credentialIssue")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling DefaultApi#credentialIssue")
    e.printStackTrace()
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **credentialIssuanceRequest** | [**CredentialIssuanceRequest**](CredentialIssuanceRequest.md)|  |

### Return type

[**CredentialIssuanceResponse**](CredentialIssuanceResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

