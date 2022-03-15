# Swagger\Client\VMEthernetApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm19HardwareEthernet4000ConnectPost**](VMEthernetApi.md#restvcentervmvm19hardwareethernet4000connectpost) | **POST** /rest/vcenter/vm/vm-19/hardware/ethernet/4000/connect | Connect
[**restVcenterVmVm19HardwareEthernet4000Patch**](VMEthernetApi.md#restvcentervmvm19hardwareethernet4000patch) | **PATCH** /rest/vcenter/vm/vm-19/hardware/ethernet/4000 | Change Network
[**restVcenterVmVm20HardwareEthernet4000Get**](VMEthernetApi.md#restvcentervmvm20hardwareethernet4000get) | **GET** /rest/vcenter/vm/vm-20/hardware/ethernet/4000 | Details
[**restVcenterVmVm20HardwareEthernetGet**](VMEthernetApi.md#restvcentervmvm20hardwareethernetget) | **GET** /rest/vcenter/vm/vm-20/hardware/ethernet | Get
[**restVcenterVmVm20HardwareEthernetPost**](VMEthernetApi.md#restvcentervmvm20hardwareethernetpost) | **POST** /rest/vcenter/vm/vm-20/hardware/ethernet | Create E1000
[**restVcenterVmVm33HardwareEthernet4000Delete**](VMEthernetApi.md#restvcentervmvm33hardwareethernet4000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/ethernet/4000 | Delete
[**restVcenterVmVm33HardwareEthernet4000DisconnectPost**](VMEthernetApi.md#restvcentervmvm33hardwareethernet4000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/ethernet/4000/disconnect | Disconnect

# **restVcenterVmVm19HardwareEthernet4000ConnectPost**
> restVcenterVmVm19HardwareEthernet4000ConnectPost()

Connect

Connect Ethernet device to the virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm19HardwareEthernet4000ConnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm19HardwareEthernet4000ConnectPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm19HardwareEthernet4000Patch**
> restVcenterVmVm19HardwareEthernet4000Patch($body, $content_type)

Change Network

Change Network the VM is attached to

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm19HardwareEthernet4000Patch($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm19HardwareEthernet4000Patch: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm20HardwareEthernet4000Get**
> restVcenterVmVm20HardwareEthernet4000Get()

Details

Get details for a single Adapter

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm20HardwareEthernet4000Get();
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm20HardwareEthernet4000Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm20HardwareEthernetGet**
> restVcenterVmVm20HardwareEthernetGet()

Get

Return the Ethernet related settings of a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm20HardwareEthernetGet();
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm20HardwareEthernetGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm20HardwareEthernetPost**
> restVcenterVmVm20HardwareEthernetPost($body, $content_type)

Create E1000

Create E1000 Network Adapter

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmVm20HardwareEthernetPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm20HardwareEthernetPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareEthernet4000Delete**
> restVcenterVmVm33HardwareEthernet4000Delete()

Delete

Delete a given ethernet adapter from a virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareEthernet4000Delete();
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm33HardwareEthernet4000Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33HardwareEthernet4000DisconnectPost**
> restVcenterVmVm33HardwareEthernet4000DisconnectPost()

Disconnect

Disconnect Ethernet device to the virtual machine.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMEthernetApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33HardwareEthernet4000DisconnectPost();
} catch (Exception $e) {
    echo 'Exception when calling VMEthernetApi->restVcenterVmVm33HardwareEthernet4000DisconnectPost: ', $e->getMessage(), PHP_EOL;
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

