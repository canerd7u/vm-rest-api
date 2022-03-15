# Swagger\Client\VMAdapterSCSIApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33HardwareAdapterScsi1000Get**](VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1000get) | **GET** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1000 | Details
[**restVcenterVmVm33HardwareAdapterScsi1001Delete**](VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1001 | Delete
[**restVcenterVmVm33HardwareAdapterScsi1001Patch**](VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1001 | Update
[**restVcenterVmVm33HardwareAdapterScsiGet**](VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsiget) | **GET** /rest/vcenter/vm/vm-33/hardware/adapter/scsi | List
[**restVcenterVmVm33HardwareAdapterScsiPost**](VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsipost) | **POST** /rest/vcenter/vm/vm-33/hardware/adapter/scsi | Create

# **restVcenterVmVm33HardwareAdapterScsi1000Get**
> restVcenterVmVm33HardwareAdapterScsi1000Get()

Details

Get SCSI details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSCSIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterScsi1000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSCSIApi->restVcenterVmVm33HardwareAdapterScsi1000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareAdapterScsi1001Delete**
> restVcenterVmVm33HardwareAdapterScsi1001Delete()

Delete

Delete SCSI Device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSCSIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterScsi1001Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSCSIApi->restVcenterVmVm33HardwareAdapterScsi1001Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareAdapterScsi1001Patch**
> restVcenterVmVm33HardwareAdapterScsi1001Patch($body, $content_type)

Update

Update SCSI Device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSCSIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterScsi1001Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSCSIApi->restVcenterVmVm33HardwareAdapterScsi1001Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareAdapterScsiGet**
> restVcenterVmVm33HardwareAdapterScsiGet()

List

List SCSI IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSCSIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterScsiGet();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSCSIApi->restVcenterVmVm33HardwareAdapterScsiGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareAdapterScsiPost**
> restVcenterVmVm33HardwareAdapterScsiPost($body, $content_type)

Create

Create SCSI Device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSCSIApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterScsiPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSCSIApi->restVcenterVmVm33HardwareAdapterScsiPost: ', $e->getMessage(), PHP_EOL;
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

