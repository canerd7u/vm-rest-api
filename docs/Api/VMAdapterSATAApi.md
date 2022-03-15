# Swagger\Client\VMAdapterSATAApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm19HardwareAdapterSata15000Get**](VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersata15000get) | **GET** /rest/vcenter/vm/vm-19/hardware/adapter/sata/15000 | Details
[**restVcenterVmVm19HardwareAdapterSataGet**](VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersataget) | **GET** /rest/vcenter/vm/vm-19/hardware/adapter/sata | List
[**restVcenterVmVm19HardwareAdapterSataPost**](VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersatapost) | **POST** /rest/vcenter/vm/vm-19/hardware/adapter/sata | Create
[**restVcenterVmVm33HardwareAdapterSata15001Delete**](VMAdapterSATAApi.md#restvcentervmvm33hardwareadaptersata15001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/adapter/sata/15001 | Delete

# **restVcenterVmVm19HardwareAdapterSata15000Get**
> restVcenterVmVm19HardwareAdapterSata15000Get()

Details

Get SATA details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSATAApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareAdapterSata15000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSATAApi->restVcenterVmVm19HardwareAdapterSata15000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareAdapterSataGet**
> restVcenterVmVm19HardwareAdapterSataGet()

List

List SATA IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSATAApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareAdapterSataGet();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSATAApi->restVcenterVmVm19HardwareAdapterSataGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareAdapterSataPost**
> restVcenterVmVm19HardwareAdapterSataPost($body, $content_type)

Create

Create SATA on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSATAApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm19HardwareAdapterSataPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSATAApi->restVcenterVmVm19HardwareAdapterSataPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareAdapterSata15001Delete**
> restVcenterVmVm33HardwareAdapterSata15001Delete()

Delete

Delete SATA Device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAdapterSATAApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareAdapterSata15001Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMAdapterSATAApi->restVcenterVmVm33HardwareAdapterSata15001Delete: ', $e->getMessage(), PHP_EOL;
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

