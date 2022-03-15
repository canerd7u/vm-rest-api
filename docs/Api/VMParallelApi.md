# Swagger\Client\VMParallelApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33HardwareParallel10000ConnectPost**](VMParallelApi.md#restvcentervmvm33hardwareparallel10000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/10000/connect | Connect
[**restVcenterVmVm33HardwareParallel10000DisconnectPost**](VMParallelApi.md#restvcentervmvm33hardwareparallel10000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/10000/disconnect | Disconnect
[**restVcenterVmVm33HardwareParallel10000Get**](VMParallelApi.md#restvcentervmvm33hardwareparallel10000get) | **GET** /rest/vcenter/vm/vm-33/hardware/parallel/10000 | Details
[**restVcenterVmVm33HardwareParallel10001Delete**](VMParallelApi.md#restvcentervmvm33hardwareparallel10001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/parallel/10001 | Delete
[**restVcenterVmVm33HardwareParallel10001Patch**](VMParallelApi.md#restvcentervmvm33hardwareparallel10001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/parallel/10001 | Update
[**restVcenterVmVm33HardwareParallelGet**](VMParallelApi.md#restvcentervmvm33hardwareparallelget) | **GET** /rest/vcenter/vm/vm-33/hardware/parallel | List
[**restVcenterVmVm33HardwareParallelPost**](VMParallelApi.md#restvcentervmvm33hardwareparallelpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/ | Create

# **restVcenterVmVm33HardwareParallel10000ConnectPost**
> restVcenterVmVm33HardwareParallel10000ConnectPost()

Connect

Connect Parallel device to a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareParallel10000ConnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallel10000ConnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallel10000DisconnectPost**
> restVcenterVmVm33HardwareParallel10000DisconnectPost()

Disconnect

Disconnect Parallel device from a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareParallel10000DisconnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallel10000DisconnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallel10000Get**
> restVcenterVmVm33HardwareParallel10000Get()

Details

Get Parallel details for a single VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareParallel10000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallel10000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallel10001Delete**
> restVcenterVmVm33HardwareParallel10001Delete()

Delete

Delete Parallel device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareParallel10001Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallel10001Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallel10001Patch**
> restVcenterVmVm33HardwareParallel10001Patch($body, $content_type)

Update

Update Parallel to use new file

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareParallel10001Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallel10001Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallelGet**
> restVcenterVmVm33HardwareParallelGet()

List

List Parallel IDs for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareParallelGet();
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallelGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareParallelPost**
> restVcenterVmVm33HardwareParallelPost($body, $content_type)

Create

Create Parallel device on VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMParallelApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm33HardwareParallelPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMParallelApi->restVcenterVmVm33HardwareParallelPost: ', $e->getMessage(), PHP_EOL;
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

