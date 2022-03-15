# Swagger\Client\VMPowerApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterVmVm33PowerGet**](VMPowerApi.md#restvcentervmvm33powerget) | **GET** /rest/vcenter/vm/vm-33/power | Details
[**restVcenterVmVm33PowerResetPost**](VMPowerApi.md#restvcentervmvm33powerresetpost) | **POST** /rest/vcenter/vm/vm-33/power/reset | Reset
[**restVcenterVmVm33PowerStartPost**](VMPowerApi.md#restvcentervmvm33powerstartpost) | **POST** /rest/vcenter/vm/vm-33/power/start | Power On
[**restVcenterVmVm33PowerStopPost**](VMPowerApi.md#restvcentervmvm33powerstoppost) | **POST** /rest/vcenter/vm/vm-33/power/stop | Power Off
[**restVcenterVmVm33PowerSuspendPost**](VMPowerApi.md#restvcentervmvm33powersuspendpost) | **POST** /rest/vcenter/vm/vm-33/power/suspend | Suspend

# **restVcenterVmVm33PowerGet**
> restVcenterVmVm33PowerGet()

Details

List power details for a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMPowerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33PowerGet();
} catch (Exception $e) {
    echo 'Exception when calling VMPowerApi->restVcenterVmVm33PowerGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33PowerResetPost**
> restVcenterVmVm33PowerResetPost()

Reset

Reset a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMPowerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33PowerResetPost();
} catch (Exception $e) {
    echo 'Exception when calling VMPowerApi->restVcenterVmVm33PowerResetPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33PowerStartPost**
> restVcenterVmVm33PowerStartPost()

Power On

Power On a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMPowerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33PowerStartPost();
} catch (Exception $e) {
    echo 'Exception when calling VMPowerApi->restVcenterVmVm33PowerStartPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33PowerStopPost**
> restVcenterVmVm33PowerStopPost()

Power Off

Power Off a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMPowerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33PowerStopPost();
} catch (Exception $e) {
    echo 'Exception when calling VMPowerApi->restVcenterVmVm33PowerStopPost: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmVm33PowerSuspendPost**
> restVcenterVmVm33PowerSuspendPost()

Suspend

Suspend a VM

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMPowerApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterVmVm33PowerSuspendPost();
} catch (Exception $e) {
    echo 'Exception when calling VMPowerApi->restVcenterVmVm33PowerSuspendPost: ', $e->getMessage(), PHP_EOL;
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

