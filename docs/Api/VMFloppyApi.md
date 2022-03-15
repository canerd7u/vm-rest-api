# Swagger\Client\VMFloppyApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33HardwareFloppy8000Get**](VMFloppyApi.md#restvcentervmvm33hardwarefloppy8000get) | **GET** /rest/vcenter/vm/vm-33/hardware/floppy/8000 | Details
[**restVcenterVmVm33HardwareFloppy8001ConnectPost**](VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy/8001/connect | Connect
[**restVcenterVmVm33HardwareFloppy8001Delete**](VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/floppy/8001 | Delete
[**restVcenterVmVm33HardwareFloppy8001DisconnectPost**](VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy/8001/disconnect | Disconnect
[**restVcenterVmVm33HardwareFloppy8001Patch**](VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/floppy/8001 | Update
[**restVcenterVmVm33HardwareFloppyGet**](VMFloppyApi.md#restvcentervmvm33hardwarefloppyget) | **GET** /rest/vcenter/vm/vm-33/hardware/floppy | List
[**restVcenterVmVm33HardwareFloppyPost**](VMFloppyApi.md#restvcentervmvm33hardwarefloppypost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy | Create

# **restVcenterVmVm33HardwareFloppy8000Get**
> restVcenterVmVm33HardwareFloppy8000Get()

Details

Get Floppy details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareFloppy8000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppy8000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppy8001ConnectPost**
> restVcenterVmVm33HardwareFloppy8001ConnectPost()

Connect

Connect Floppy to a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareFloppy8001ConnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppy8001ConnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppy8001Delete**
> restVcenterVmVm33HardwareFloppy8001Delete()

Delete

Delete Floppy on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareFloppy8001Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppy8001Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppy8001DisconnectPost**
> restVcenterVmVm33HardwareFloppy8001DisconnectPost()

Disconnect

Disconnect Floppy from a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareFloppy8001DisconnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppy8001DisconnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppy8001Patch**
> restVcenterVmVm33HardwareFloppy8001Patch($body, $content_type)

Update

Update FLoppy to use flp file

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareFloppy8001Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppy8001Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppyGet**
> restVcenterVmVm33HardwareFloppyGet()

List

List Floppy IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareFloppyGet();
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppyGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareFloppyPost**
> restVcenterVmVm33HardwareFloppyPost($body, $content_type)

Create

Create Floppy on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMFloppyApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareFloppyPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMFloppyApi->restVcenterVmVm33HardwareFloppyPost: ', $e->getMessage(), PHP_EOL;
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

