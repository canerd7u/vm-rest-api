# Swagger\Client\VMApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmGet**](VMApi.md#restvcentervmget) | **GET** /rest/vcenter/vm | Find
[**restVcenterVmVm22Get**](VMApi.md#restvcentervmvm22get) | **GET** /rest/vcenter/vm/vm-22 | Details
[**restVcenterVmVm32Delete**](VMApi.md#restvcentervmvm32delete) | **DELETE** /rest/vcenter/vm/vm-32 | Delete

# **restVcenterVmGet**
> restVcenterVmGet($filter_names_1)

Find

Find a VM based on the specified filter, in this case the vm name when it was created.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$filter_names_1 = "filter_names_1_example"; // string | 

try {
    $apiInstance->restVcenterVmGet($filter_names_1);
} catch (Exception $e) {
    echo 'Exception when calling VMApi->restVcenterVmGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter_names_1** | **string**|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **restVcenterVmVm22Get**
> restVcenterVmVm22Get()

Details

Get the details for the specified VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm22Get();
} catch (Exception $e) {
    echo 'Exception when calling VMApi->restVcenterVmVm22Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm32Delete**
> restVcenterVmVm32Delete()

Delete

Delete the specified VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm32Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMApi->restVcenterVmVm32Delete: ', $e->getMessage(), PHP_EOL;
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

