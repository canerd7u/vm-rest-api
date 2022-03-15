# Swagger\Client\DatacentersApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterDatacenterDatacenter34Delete**](DatacentersApi.md#restvcenterdatacenterdatacenter34delete) | **DELETE** /rest/vcenter/datacenter/datacenter-34 | Delete
[**restVcenterDatacenterDatacenter87Get**](DatacentersApi.md#restvcenterdatacenterdatacenter87get) | **GET** /rest/vcenter/datacenter/datacenter-87 | Details
[**restVcenterDatacenterGet**](DatacentersApi.md#restvcenterdatacenterget) | **GET** /rest/vcenter/datacenter | Find
[**restVcenterDatacenterPost**](DatacentersApi.md#restvcenterdatacenterpost) | **POST** /rest/vcenter/datacenter | Create

# **restVcenterDatacenterDatacenter34Delete**
> restVcenterDatacenterDatacenter34Delete()

Delete

Delete the specified datacenter.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatacentersApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterDatacenterDatacenter34Delete();
} catch (Exception $e) {
    echo 'Exception when calling DatacentersApi->restVcenterDatacenterDatacenter34Delete: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterDatacenterDatacenter87Get**
> restVcenterDatacenterDatacenter87Get()

Details

List the details of the specified datacenter.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatacentersApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterDatacenterDatacenter87Get();
} catch (Exception $e) {
    echo 'Exception when calling DatacentersApi->restVcenterDatacenterDatacenter87Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterDatacenterGet**
> restVcenterDatacenterGet($content_type, $filter_names_1)

Find

This call will find the Testbed-DC datacenter created in the setup sample

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatacentersApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$content_type = "content_type_example"; // string | 
$filter_names_1 = "filter_names_1_example"; // string | 

try {
    $apiInstance->restVcenterDatacenterGet($content_type, $filter_names_1);
} catch (Exception $e) {
    echo 'Exception when calling DatacentersApi->restVcenterDatacenterGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **content_type** | **string**|  | [optional]
 **filter_names_1** | **string**|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **restVcenterDatacenterPost**
> restVcenterDatacenterPost($body, $content_type)

Create

Create a new datacenter. Specify the name and the folder for the datacenter to be created in as part of the request body.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatacentersApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterDatacenterPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling DatacentersApi->restVcenterDatacenterPost: ', $e->getMessage(), PHP_EOL;
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

