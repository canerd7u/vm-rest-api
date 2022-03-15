# Swagger\Client\VMMemoryApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33HardwareMemoryGet**](VMMemoryApi.md#restvcentervmvm33hardwarememoryget) | **GET** /rest/vcenter/vm/vm-33/hardware/memory | Get
[**restVcenterVmVm33HardwareMemoryPatch**](VMMemoryApi.md#restvcentervmvm33hardwarememorypatch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/memory | Update

# **restVcenterVmVm33HardwareMemoryGet**
> restVcenterVmVm33HardwareMemoryGet()

Get

Return the Memory related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMMemoryApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareMemoryGet();
} catch (Exception $e) {
    echo 'Exception when calling VMMemoryApi->restVcenterVmVm33HardwareMemoryGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareMemoryPatch**
> restVcenterVmVm33HardwareMemoryPatch($body, $content_type)

Update

Update the Memory related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMMemoryApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareMemoryPatch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMMemoryApi->restVcenterVmVm33HardwareMemoryPatch: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**object**](../Model/object.md)|  | [optional]
 **content_type** | **string**|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

