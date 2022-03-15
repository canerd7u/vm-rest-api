# Swagger\Client\VMSerialApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33HardwareSerial9000ConnectPost**](VMSerialApi.md#restvcentervmvm33hardwareserial9000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/9000/connect | Connect
[**restVcenterVmVm33HardwareSerial9000Delete**](VMSerialApi.md#restvcentervmvm33hardwareserial9000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Delete
[**restVcenterVmVm33HardwareSerial9000DisconnectPost**](VMSerialApi.md#restvcentervmvm33hardwareserial9000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/9000/disconnect | Disconnect
[**restVcenterVmVm33HardwareSerial9000Get**](VMSerialApi.md#restvcentervmvm33hardwareserial9000get) | **GET** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Details
[**restVcenterVmVm33HardwareSerial9000Patch**](VMSerialApi.md#restvcentervmvm33hardwareserial9000patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Update
[**restVcenterVmVm33HardwareSerialGet**](VMSerialApi.md#restvcentervmvm33hardwareserialget) | **GET** /rest/vcenter/vm/vm-33/hardware/serial | List
[**restVcenterVmVm33HardwareSerialPost**](VMSerialApi.md#restvcentervmvm33hardwareserialpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/ | Create

# **restVcenterVmVm33HardwareSerial9000ConnectPost**
> restVcenterVmVm33HardwareSerial9000ConnectPost()

Connect

Connect Serial device to a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareSerial9000ConnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerial9000ConnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerial9000Delete**
> restVcenterVmVm33HardwareSerial9000Delete()

Delete

Delete Serial device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareSerial9000Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerial9000Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerial9000DisconnectPost**
> restVcenterVmVm33HardwareSerial9000DisconnectPost()

Disconnect

Disconnect Serial device from a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareSerial9000DisconnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerial9000DisconnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerial9000Get**
> restVcenterVmVm33HardwareSerial9000Get()

Details

Get Serial details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareSerial9000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerial9000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerial9000Patch**
> restVcenterVmVm33HardwareSerial9000Patch($body, $content_type)

Update

Update Serial to use new file

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareSerial9000Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerial9000Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerialGet**
> restVcenterVmVm33HardwareSerialGet()

List

List Serial IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareSerialGet();
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerialGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareSerialPost**
> restVcenterVmVm33HardwareSerialPost($body, $content_type)

Create

Create Serial device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMSerialApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareSerialPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMSerialApi->restVcenterVmVm33HardwareSerialPost: ', $e->getMessage(), PHP_EOL;
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

