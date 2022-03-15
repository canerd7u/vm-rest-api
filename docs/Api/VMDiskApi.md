# Swagger\Client\VMDiskApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm19HardwareDisk3000Get**](VMDiskApi.md#restvcentervmvm19hardwaredisk3000get) | **GET** /rest/vcenter/vm/vm-19/hardware/disk/3000 | Details
[**restVcenterVmVm19HardwareDisk3002Delete**](VMDiskApi.md#restvcentervmvm19hardwaredisk3002delete) | **DELETE** /rest/vcenter/vm/vm-19/hardware/disk/3002 | Delete
[**restVcenterVmVm19HardwareDiskGet**](VMDiskApi.md#restvcentervmvm19hardwarediskget) | **GET** /rest/vcenter/vm/vm-19/hardware/disk | Get
[**restVcenterVmVm19HardwareDiskPost**](VMDiskApi.md#restvcentervmvm19hardwarediskpost) | **POST** /rest/vcenter/vm/vm-19/hardware/disk | Create SATA
[**restVcenterVmVm33HardwareDisk3002Patch**](VMDiskApi.md#restvcentervmvm33hardwaredisk3002patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/disk/3002 | Change VMDK location

# **restVcenterVmVm19HardwareDisk3000Get**
> restVcenterVmVm19HardwareDisk3000Get()

Details

Get Disk details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMDiskApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareDisk3000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMDiskApi->restVcenterVmVm19HardwareDisk3000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareDisk3002Delete**
> restVcenterVmVm19HardwareDisk3002Delete()

Delete

Delete a given disk from a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMDiskApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareDisk3002Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMDiskApi->restVcenterVmVm19HardwareDisk3002Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareDiskGet**
> restVcenterVmVm19HardwareDiskGet()

Get

Return the Disk related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMDiskApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareDiskGet();
} catch (Exception $e) {
    echo 'Exception when calling VMDiskApi->restVcenterVmVm19HardwareDiskGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareDiskPost**
> restVcenterVmVm19HardwareDiskPost($body, $content_type)

Create SATA

Create SATA Disk with default size.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMDiskApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm19HardwareDiskPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMDiskApi->restVcenterVmVm19HardwareDiskPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareDisk3002Patch**
> restVcenterVmVm33HardwareDisk3002Patch($body, $content_type)

Change VMDK location

Change disk VMDK location to new VMDK

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMDiskApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareDisk3002Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMDiskApi->restVcenterVmVm33HardwareDisk3002Patch: ', $e->getMessage(), PHP_EOL;
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

