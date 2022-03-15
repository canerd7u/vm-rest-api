# Swagger\Client\VMAddApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restComVmwareCisSessionPost**](VMAddApi.md#restcomvmwarecissessionpost) | **POST** /rest/com/vmware/cis/session | Login
[**restVcenterFolderGet**](VMAddApi.md#restvcenterfolderget) | **GET** /rest/vcenter/folder | Find folers to create the VM in
[**restVcenterResourcePoolGet**](VMAddApi.md#restvcenterresourcepoolget) | **GET** /rest/vcenter/resource-pool | Find a resource pool to use
[**restVcenterVmPost**](VMAddApi.md#restvcentervmpost) | **POST** /rest/vcenter/vm | Create VM

# **restComVmwareCisSessionPost**
> restComVmwareCisSessionPost($authorization)

Login

Login to vCenter API and retrieve Session using username and password. The environment variables username and password are passed via the

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAddApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$authorization = "authorization_example"; // string | 

try {
    $apiInstance->restComVmwareCisSessionPost($authorization);
} catch (Exception $e) {
    echo 'Exception when calling VMAddApi->restComVmwareCisSessionPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **authorization** | **string**|  | [optional]

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **restVcenterFolderGet**
> restVcenterFolderGet()

Find folers to create the VM in

This request can be called to get a list of folders. To create a VM, we need the datastore and vm folders. If not previously captured during the /datacenter/<datacenter-name> details, the response can be parsed for the vm and datastore folders.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAddApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterFolderGet();
} catch (Exception $e) {
    echo 'Exception when calling VMAddApi->restVcenterFolderGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterResourcePoolGet**
> restVcenterResourcePoolGet()

Find a resource pool to use

Grab the first resource pool returned

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAddApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterResourcePoolGet();
} catch (Exception $e) {
    echo 'Exception when calling VMAddApi->restVcenterResourcePoolGet: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterVmPost**
> restVcenterVmPost($body, $content_type)

Create VM

This request will create a VM using the environment variables for storage, resource pool and folder.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\VMAddApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$body = new \stdClass; // object | 
$content_type = "content_type_example"; // string | 

try {
    $apiInstance->restVcenterVmPost($body, $content_type);
} catch (Exception $e) {
    echo 'Exception when calling VMAddApi->restVcenterVmPost: ', $e->getMessage(), PHP_EOL;
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

