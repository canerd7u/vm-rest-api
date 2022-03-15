# Swagger\Client\VMCPUCopyApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm19HardwareCpuGet**](VMCPUCopyApi.md#restvcentervmvm19hardwarecpuget) | **GET** /rest/vcenter/vm/vm-19/hardware/cpu | CPU: Get for a single VM
[**restVcenterVmVm33HardwareCpuPatch**](VMCPUCopyApi.md#restvcentervmvm33hardwarecpupatch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/cpu | CPU: Update

# **restVcenterVmVm19HardwareCpuGet**
> restVcenterVmVm19HardwareCpuGet()

CPU: Get for a single VM

Return the CPU related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCPUCopyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareCpuGet();
} catch (Exception $e) {
    echo 'Exception when calling VMCPUCopyApi->restVcenterVmVm19HardwareCpuGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareCpuPatch**
> restVcenterVmVm33HardwareCpuPatch($body, $content_type)

CPU: Update

Update the CPU related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCPUCopyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareCpuPatch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMCPUCopyApi->restVcenterVmVm33HardwareCpuPatch: ', $e->getMessage(), PHP_EOL;
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

