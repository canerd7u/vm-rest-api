# Swagger\Client\ResourcePoolApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterResourcePoolResgroup8Get**](ResourcePoolApi.md#restvcenterresourcepoolresgroup8get) | **GET** /rest/vcenter/resource-pool/resgroup-8 | Get details

# **restVcenterResourcePoolResgroup8Get**
> restVcenterResourcePoolResgroup8Get()

Get details

This request will return the details of the specified resource pool.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\ResourcePoolApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterResourcePoolResgroup8Get();
} catch (Exception $e) {
    echo 'Exception when calling ResourcePoolApi->restVcenterResourcePoolResgroup8Get: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

