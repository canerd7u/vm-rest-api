# Swagger\Client\NetworkApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterNetworkGet**](NetworkApi.md#restvcenternetworkget) | **GET** /rest/vcenter/network | List details

# **restVcenterNetworkGet**
> restVcenterNetworkGet()

List details

This request will get the list of all networks available.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\NetworkApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterNetworkGet();
} catch (Exception $e) {
    echo 'Exception when calling NetworkApi->restVcenterNetworkGet: ', $e->getMessage(), PHP_EOL;
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

