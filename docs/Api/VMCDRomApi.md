# Swagger\Client\VMCDRomApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm19HardwareCdrom3000Patch**](VMCDRomApi.md#restvcentervmvm19hardwarecdrom3000patch) | **PATCH** /rest/vcenter/vm/vm-19/hardware/cdrom/3000 | CD-Rom: Update
[**restVcenterVmVm19HardwareCdromGet**](VMCDRomApi.md#restvcentervmvm19hardwarecdromget) | **GET** /rest/vcenter/vm/vm-19/hardware/cdrom | CD-Rom: List for a single VM
[**restVcenterVmVm19HardwareCdromPost**](VMCDRomApi.md#restvcentervmvm19hardwarecdrompost) | **POST** /rest/vcenter/vm/vm-19/hardware/cdrom | CD-Rom: Create SATA
[**restVcenterVmVm22HardwareCdrom3001Get**](VMCDRomApi.md#restvcentervmvm22hardwarecdrom3001get) | **GET** /rest/vcenter/vm/vm-22/hardware/cdrom/3001 | CD-Rom: Get details for a single VM
[**restVcenterVmVm33HardwareCdrom16000ConnectPost**](VMCDRomApi.md#restvcentervmvm33hardwarecdrom16000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/cdrom/16000/connect | CD-Rom: Connect
[**restVcenterVmVm33HardwareCdrom16000DisconnectPost**](VMCDRomApi.md#restvcentervmvm33hardwarecdrom16000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/cdrom/16000/disconnect | CD-Rom: Disconnect
[**restVcenterVmVm33HardwareCdrom3000Delete**](VMCDRomApi.md#restvcentervmvm33hardwarecdrom3000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/cdrom/3000 | CD-Rom: Delete

# **restVcenterVmVm19HardwareCdrom3000Patch**
> restVcenterVmVm19HardwareCdrom3000Patch($body, $content_type)

CD-Rom: Update

Update CD-Rom to remove ISO File

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm19HardwareCdrom3000Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm19HardwareCdrom3000Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareCdromGet**
> restVcenterVmVm19HardwareCdromGet()

CD-Rom: List for a single VM

List CD-Rom IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareCdromGet();
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm19HardwareCdromGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareCdromPost**
> restVcenterVmVm19HardwareCdromPost($body, $content_type)

CD-Rom: Create SATA

Create SATA CD-ROM on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm19HardwareCdromPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm19HardwareCdromPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm22HardwareCdrom3001Get**
> restVcenterVmVm22HardwareCdrom3001Get()

CD-Rom: Get details for a single VM

Get CD-Rom details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm22HardwareCdrom3001Get();
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm22HardwareCdrom3001Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareCdrom16000ConnectPost**
> restVcenterVmVm33HardwareCdrom16000ConnectPost()

CD-Rom: Connect

Connect CD-Rom to a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareCdrom16000ConnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm33HardwareCdrom16000ConnectPost: ', $e->getMessage(), PHP_EOL;
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

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **restVcenterVmVm33HardwareCdrom16000DisconnectPost**
> restVcenterVmVm33HardwareCdrom16000DisconnectPost()

CD-Rom: Disconnect

Disconnect CD-Rom from a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareCdrom16000DisconnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm33HardwareCdrom16000DisconnectPost: ', $e->getMessage(), PHP_EOL;
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

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **restVcenterVmVm33HardwareCdrom3000Delete**
> restVcenterVmVm33HardwareCdrom3000Delete()

CD-Rom: Delete

Create IDE CD-ROM on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMCDRomApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareCdrom3000Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMCDRomApi->restVcenterVmVm33HardwareCdrom3000Delete: ', $e->getMessage(), PHP_EOL;
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

