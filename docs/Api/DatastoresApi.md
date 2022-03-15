# Swagger\Client\DatastoresApi

All URIs are relative to *https://{{vc}}*

Method | HTTP request | Description
------------- | ------------- | -------------
[**restVcenterDatastoreDatastore26Get**](DatastoresApi.md#restvcenterdatastoredatastore26get) | **GET** /rest/vcenter/datastore/datastore-26 | List details for a single datastore
[**restVcenterDatastoreGet**](DatastoresApi.md#restvcenterdatastoreget) | **GET** /rest/vcenter/datastore | Find

# **restVcenterDatastoreDatastore26Get**
> restVcenterDatastoreDatastore26Get()

List details for a single datastore

List details for a datastore

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatastoresApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restVcenterDatastoreDatastore26Get();
} catch (Exception $e) {
    echo 'Exception when calling DatastoresApi->restVcenterDatastoreDatastore26Get: ', $e->getMessage(), PHP_EOL;
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

# **restVcenterDatastoreGet**
> restVcenterDatastoreGet($content_type, $filter_names_1)

Find

Find Datastores with given filter details

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DatastoresApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$content_type = "content_type_example"; // string | 
$filter_names_1 = "filter_names_1_example"; // string | 

try {
    $apiInstance->restVcenterDatastoreGet($content_type, $filter_names_1);
} catch (Exception $e) {
    echo 'Exception when calling DatastoresApi->restVcenterDatastoreGet: ', $e->getMessage(), PHP_EOL;
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

