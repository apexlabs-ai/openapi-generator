# Org.OpenAPITools.Api.AnotherFakeApi

All URIs are relative to *http://petstore.swagger.io:80/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Call123TestSpecialTags**](AnotherFakeApi.md#call123testspecialtags) | **PATCH** /another-fake/dummy | To test special tags



## Call123TestSpecialTags

> ModelClient Call123TestSpecialTags (ModelClient body)

To test special tags

To test special tags and operation ID starting with number

### Example

```csharp
using System.Collections.Generic;
using System.Diagnostics;
using Org.OpenAPITools.Api;
using Org.OpenAPITools.Client;
using Org.OpenAPITools.Model;

namespace Example
{
    public class Call123TestSpecialTagsExample
    {
        public static void Main()
        {
            Configuration.Default.BasePath = "http://petstore.swagger.io:80/v2";
            var apiInstance = new AnotherFakeApi(Configuration.Default);
            var body = new ModelClient(); // ModelClient | client model

            try
            {
                // To test special tags
                ModelClient result = apiInstance.Call123TestSpecialTags(body);
                Debug.WriteLine(result);
            }
            catch (ApiException e)
            {
                Debug.Print("Exception when calling AnotherFakeApi.Call123TestSpecialTags: " + e.Message );
                Debug.Print("Status Code: "+ e.ErrorCode);
                Debug.Print(e.StackTrace);
            }
        }
    }
}
```

### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ModelClient**](ModelClient.md)| client model | 

### Return type

[**ModelClient**](ModelClient.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
| **200** | successful operation |  -  |

[[Back to top]](#)
[[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)
