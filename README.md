# SwaggerClient-php
The folders within this collection represent the Rest API resources and the different operations that can be performed on each. These are individual requests. In many cases, each request will require input that would come from other requests. It is left up to the user to insert the correct data into the URL, query parameters and request bodies for the requests to work correctly. Refer to the ReST API Documentation for further help.

This PHP package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0-oas3
- Build package: io.swagger.codegen.v3.generators.php.PhpClientCodegen

## Requirements

PHP 5.5 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/GIT_USER_ID/GIT_REPO_ID.git"
    }
  ],
  "require": {
    "GIT_USER_ID/GIT_REPO_ID": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/SwaggerClient-php/vendor/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AuthenticationApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $apiInstance->restComVmwareCisSessionDelete();
} catch (Exception $e) {
    echo 'Exception when calling AuthenticationApi->restComVmwareCisSessionDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

## Documentation for API Endpoints

All URIs are relative to *https://{{vc}}*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AuthenticationApi* | [**restComVmwareCisSessionDelete**](docs/Api/AuthenticationApi.md#restcomvmwarecissessiondelete) | **DELETE** /rest/com/vmware/cis/session | Logout
*DatacentersApi* | [**restVcenterDatacenterDatacenter34Delete**](docs/Api/DatacentersApi.md#restvcenterdatacenterdatacenter34delete) | **DELETE** /rest/vcenter/datacenter/datacenter-34 | Delete
*DatacentersApi* | [**restVcenterDatacenterDatacenter87Get**](docs/Api/DatacentersApi.md#restvcenterdatacenterdatacenter87get) | **GET** /rest/vcenter/datacenter/datacenter-87 | Details
*DatacentersApi* | [**restVcenterDatacenterGet**](docs/Api/DatacentersApi.md#restvcenterdatacenterget) | **GET** /rest/vcenter/datacenter | Find
*DatacentersApi* | [**restVcenterDatacenterPost**](docs/Api/DatacentersApi.md#restvcenterdatacenterpost) | **POST** /rest/vcenter/datacenter | Create
*DatastoresApi* | [**restVcenterDatastoreDatastore26Get**](docs/Api/DatastoresApi.md#restvcenterdatastoredatastore26get) | **GET** /rest/vcenter/datastore/datastore-26 | List details for a single datastore
*DatastoresApi* | [**restVcenterDatastoreGet**](docs/Api/DatastoresApi.md#restvcenterdatastoreget) | **GET** /rest/vcenter/datastore | Find
*HostsApi* | [**restVcenterHostGet**](docs/Api/HostsApi.md#restvcenterhostget) | **GET** /rest/vcenter/host | List
*HostsApi* | [**restVcenterHostHost10ConnectPost**](docs/Api/HostsApi.md#restvcenterhosthost10connectpost) | **POST** /rest/vcenter/host/host-10/connect | Connect
*HostsApi* | [**restVcenterHostHost10DisconnectPost**](docs/Api/HostsApi.md#restvcenterhosthost10disconnectpost) | **POST** /rest/vcenter/host/host-10/disconnect | Disconnect
*HostsApi* | [**restVcenterHostHost12Delete**](docs/Api/HostsApi.md#restvcenterhosthost12delete) | **DELETE** /rest/vcenter/host/host-12 | Delete
*HostsApi* | [**restVcenterHostPost**](docs/Api/HostsApi.md#restvcenterhostpost) | **POST** /rest/vcenter/host | Add
*NetworkApi* | [**restVcenterNetworkGet**](docs/Api/NetworkApi.md#restvcenternetworkget) | **GET** /rest/vcenter/network | List details
*ResourcePoolApi* | [**restVcenterResourcePoolResgroup8Get**](docs/Api/ResourcePoolApi.md#restvcenterresourcepoolresgroup8get) | **GET** /rest/vcenter/resource-pool/resgroup-8 | Get details
*VMApi* | [**restVcenterVmGet**](docs/Api/VMApi.md#restvcentervmget) | **GET** /rest/vcenter/vm | Find
*VMApi* | [**restVcenterVmVm22Get**](docs/Api/VMApi.md#restvcentervmvm22get) | **GET** /rest/vcenter/vm/vm-22 | Details
*VMApi* | [**restVcenterVmVm32Delete**](docs/Api/VMApi.md#restvcentervmvm32delete) | **DELETE** /rest/vcenter/vm/vm-32 | Delete
*VMAdapterSATAApi* | [**restVcenterVmVm19HardwareAdapterSata15000Get**](docs/Api/VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersata15000get) | **GET** /rest/vcenter/vm/vm-19/hardware/adapter/sata/15000 | Details
*VMAdapterSATAApi* | [**restVcenterVmVm19HardwareAdapterSataGet**](docs/Api/VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersataget) | **GET** /rest/vcenter/vm/vm-19/hardware/adapter/sata | List
*VMAdapterSATAApi* | [**restVcenterVmVm19HardwareAdapterSataPost**](docs/Api/VMAdapterSATAApi.md#restvcentervmvm19hardwareadaptersatapost) | **POST** /rest/vcenter/vm/vm-19/hardware/adapter/sata | Create
*VMAdapterSATAApi* | [**restVcenterVmVm33HardwareAdapterSata15001Delete**](docs/Api/VMAdapterSATAApi.md#restvcentervmvm33hardwareadaptersata15001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/adapter/sata/15001 | Delete
*VMAdapterSCSIApi* | [**restVcenterVmVm33HardwareAdapterScsi1000Get**](docs/Api/VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1000get) | **GET** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1000 | Details
*VMAdapterSCSIApi* | [**restVcenterVmVm33HardwareAdapterScsi1001Delete**](docs/Api/VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1001 | Delete
*VMAdapterSCSIApi* | [**restVcenterVmVm33HardwareAdapterScsi1001Patch**](docs/Api/VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsi1001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/adapter/scsi/1001 | Update
*VMAdapterSCSIApi* | [**restVcenterVmVm33HardwareAdapterScsiGet**](docs/Api/VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsiget) | **GET** /rest/vcenter/vm/vm-33/hardware/adapter/scsi | List
*VMAdapterSCSIApi* | [**restVcenterVmVm33HardwareAdapterScsiPost**](docs/Api/VMAdapterSCSIApi.md#restvcentervmvm33hardwareadapterscsipost) | **POST** /rest/vcenter/vm/vm-33/hardware/adapter/scsi | Create
*VMAddApi* | [**restComVmwareCisSessionPost**](docs/Api/VMAddApi.md#restcomvmwarecissessionpost) | **POST** /rest/com/vmware/cis/session | Login
*VMAddApi* | [**restVcenterFolderGet**](docs/Api/VMAddApi.md#restvcenterfolderget) | **GET** /rest/vcenter/folder | Find folers to create the VM in
*VMAddApi* | [**restVcenterResourcePoolGet**](docs/Api/VMAddApi.md#restvcenterresourcepoolget) | **GET** /rest/vcenter/resource-pool | Find a resource pool to use
*VMAddApi* | [**restVcenterVmPost**](docs/Api/VMAddApi.md#restvcentervmpost) | **POST** /rest/vcenter/vm | Create VM
*VMCDRomApi* | [**restVcenterVmVm19HardwareCdrom3000Patch**](docs/Api/VMCDRomApi.md#restvcentervmvm19hardwarecdrom3000patch) | **PATCH** /rest/vcenter/vm/vm-19/hardware/cdrom/3000 | CD-Rom: Update
*VMCDRomApi* | [**restVcenterVmVm19HardwareCdromGet**](docs/Api/VMCDRomApi.md#restvcentervmvm19hardwarecdromget) | **GET** /rest/vcenter/vm/vm-19/hardware/cdrom | CD-Rom: List for a single VM
*VMCDRomApi* | [**restVcenterVmVm19HardwareCdromPost**](docs/Api/VMCDRomApi.md#restvcentervmvm19hardwarecdrompost) | **POST** /rest/vcenter/vm/vm-19/hardware/cdrom | CD-Rom: Create SATA
*VMCDRomApi* | [**restVcenterVmVm22HardwareCdrom3001Get**](docs/Api/VMCDRomApi.md#restvcentervmvm22hardwarecdrom3001get) | **GET** /rest/vcenter/vm/vm-22/hardware/cdrom/3001 | CD-Rom: Get details for a single VM
*VMCDRomApi* | [**restVcenterVmVm33HardwareCdrom16000ConnectPost**](docs/Api/VMCDRomApi.md#restvcentervmvm33hardwarecdrom16000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/cdrom/16000/connect | CD-Rom: Connect
*VMCDRomApi* | [**restVcenterVmVm33HardwareCdrom16000DisconnectPost**](docs/Api/VMCDRomApi.md#restvcentervmvm33hardwarecdrom16000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/cdrom/16000/disconnect | CD-Rom: Disconnect
*VMCDRomApi* | [**restVcenterVmVm33HardwareCdrom3000Delete**](docs/Api/VMCDRomApi.md#restvcentervmvm33hardwarecdrom3000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/cdrom/3000 | CD-Rom: Delete
*VMCPUCopyApi* | [**restVcenterVmVm19HardwareCpuGet**](docs/Api/VMCPUCopyApi.md#restvcentervmvm19hardwarecpuget) | **GET** /rest/vcenter/vm/vm-19/hardware/cpu | CPU: Get for a single VM
*VMCPUCopyApi* | [**restVcenterVmVm33HardwareCpuPatch**](docs/Api/VMCPUCopyApi.md#restvcentervmvm33hardwarecpupatch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/cpu | CPU: Update
*VMDiskApi* | [**restVcenterVmVm19HardwareDisk3000Get**](docs/Api/VMDiskApi.md#restvcentervmvm19hardwaredisk3000get) | **GET** /rest/vcenter/vm/vm-19/hardware/disk/3000 | Details
*VMDiskApi* | [**restVcenterVmVm19HardwareDisk3002Delete**](docs/Api/VMDiskApi.md#restvcentervmvm19hardwaredisk3002delete) | **DELETE** /rest/vcenter/vm/vm-19/hardware/disk/3002 | Delete
*VMDiskApi* | [**restVcenterVmVm19HardwareDiskGet**](docs/Api/VMDiskApi.md#restvcentervmvm19hardwarediskget) | **GET** /rest/vcenter/vm/vm-19/hardware/disk | Get
*VMDiskApi* | [**restVcenterVmVm19HardwareDiskPost**](docs/Api/VMDiskApi.md#restvcentervmvm19hardwarediskpost) | **POST** /rest/vcenter/vm/vm-19/hardware/disk | Create SATA
*VMDiskApi* | [**restVcenterVmVm33HardwareDisk3002Patch**](docs/Api/VMDiskApi.md#restvcentervmvm33hardwaredisk3002patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/disk/3002 | Change VMDK location
*VMEthernetApi* | [**restVcenterVmVm19HardwareEthernet4000ConnectPost**](docs/Api/VMEthernetApi.md#restvcentervmvm19hardwareethernet4000connectpost) | **POST** /rest/vcenter/vm/vm-19/hardware/ethernet/4000/connect | Connect
*VMEthernetApi* | [**restVcenterVmVm19HardwareEthernet4000Patch**](docs/Api/VMEthernetApi.md#restvcentervmvm19hardwareethernet4000patch) | **PATCH** /rest/vcenter/vm/vm-19/hardware/ethernet/4000 | Change Network
*VMEthernetApi* | [**restVcenterVmVm20HardwareEthernet4000Get**](docs/Api/VMEthernetApi.md#restvcentervmvm20hardwareethernet4000get) | **GET** /rest/vcenter/vm/vm-20/hardware/ethernet/4000 | Details
*VMEthernetApi* | [**restVcenterVmVm20HardwareEthernetGet**](docs/Api/VMEthernetApi.md#restvcentervmvm20hardwareethernetget) | **GET** /rest/vcenter/vm/vm-20/hardware/ethernet | Get
*VMEthernetApi* | [**restVcenterVmVm20HardwareEthernetPost**](docs/Api/VMEthernetApi.md#restvcentervmvm20hardwareethernetpost) | **POST** /rest/vcenter/vm/vm-20/hardware/ethernet | Create E1000
*VMEthernetApi* | [**restVcenterVmVm33HardwareEthernet4000Delete**](docs/Api/VMEthernetApi.md#restvcentervmvm33hardwareethernet4000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/ethernet/4000 | Delete
*VMEthernetApi* | [**restVcenterVmVm33HardwareEthernet4000DisconnectPost**](docs/Api/VMEthernetApi.md#restvcentervmvm33hardwareethernet4000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/ethernet/4000/disconnect | Disconnect
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppy8000Get**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppy8000get) | **GET** /rest/vcenter/vm/vm-33/hardware/floppy/8000 | Details
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppy8001ConnectPost**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy/8001/connect | Connect
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppy8001Delete**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/floppy/8001 | Delete
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppy8001DisconnectPost**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy/8001/disconnect | Disconnect
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppy8001Patch**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppy8001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/floppy/8001 | Update
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppyGet**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppyget) | **GET** /rest/vcenter/vm/vm-33/hardware/floppy | List
*VMFloppyApi* | [**restVcenterVmVm33HardwareFloppyPost**](docs/Api/VMFloppyApi.md#restvcentervmvm33hardwarefloppypost) | **POST** /rest/vcenter/vm/vm-33/hardware/floppy | Create
*VMMemoryApi* | [**restVcenterVmVm33HardwareMemoryGet**](docs/Api/VMMemoryApi.md#restvcentervmvm33hardwarememoryget) | **GET** /rest/vcenter/vm/vm-33/hardware/memory | Get
*VMMemoryApi* | [**restVcenterVmVm33HardwareMemoryPatch**](docs/Api/VMMemoryApi.md#restvcentervmvm33hardwarememorypatch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/memory | Update
*VMParallelApi* | [**restVcenterVmVm33HardwareParallel10000ConnectPost**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallel10000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/10000/connect | Connect
*VMParallelApi* | [**restVcenterVmVm33HardwareParallel10000DisconnectPost**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallel10000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/10000/disconnect | Disconnect
*VMParallelApi* | [**restVcenterVmVm33HardwareParallel10000Get**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallel10000get) | **GET** /rest/vcenter/vm/vm-33/hardware/parallel/10000 | Details
*VMParallelApi* | [**restVcenterVmVm33HardwareParallel10001Delete**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallel10001delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/parallel/10001 | Delete
*VMParallelApi* | [**restVcenterVmVm33HardwareParallel10001Patch**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallel10001patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/parallel/10001 | Update
*VMParallelApi* | [**restVcenterVmVm33HardwareParallelGet**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallelget) | **GET** /rest/vcenter/vm/vm-33/hardware/parallel | List
*VMParallelApi* | [**restVcenterVmVm33HardwareParallelPost**](docs/Api/VMParallelApi.md#restvcentervmvm33hardwareparallelpost) | **POST** /rest/vcenter/vm/vm-33/hardware/parallel/ | Create
*VMPowerApi* | [**restVcenterVmVm33PowerGet**](docs/Api/VMPowerApi.md#restvcentervmvm33powerget) | **GET** /rest/vcenter/vm/vm-33/power | Details
*VMPowerApi* | [**restVcenterVmVm33PowerResetPost**](docs/Api/VMPowerApi.md#restvcentervmvm33powerresetpost) | **POST** /rest/vcenter/vm/vm-33/power/reset | Reset
*VMPowerApi* | [**restVcenterVmVm33PowerStartPost**](docs/Api/VMPowerApi.md#restvcentervmvm33powerstartpost) | **POST** /rest/vcenter/vm/vm-33/power/start | Power On
*VMPowerApi* | [**restVcenterVmVm33PowerStopPost**](docs/Api/VMPowerApi.md#restvcentervmvm33powerstoppost) | **POST** /rest/vcenter/vm/vm-33/power/stop | Power Off
*VMPowerApi* | [**restVcenterVmVm33PowerSuspendPost**](docs/Api/VMPowerApi.md#restvcentervmvm33powersuspendpost) | **POST** /rest/vcenter/vm/vm-33/power/suspend | Suspend
*VMSerialApi* | [**restVcenterVmVm33HardwareSerial9000ConnectPost**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserial9000connectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/9000/connect | Connect
*VMSerialApi* | [**restVcenterVmVm33HardwareSerial9000Delete**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserial9000delete) | **DELETE** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Delete
*VMSerialApi* | [**restVcenterVmVm33HardwareSerial9000DisconnectPost**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserial9000disconnectpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/9000/disconnect | Disconnect
*VMSerialApi* | [**restVcenterVmVm33HardwareSerial9000Get**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserial9000get) | **GET** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Details
*VMSerialApi* | [**restVcenterVmVm33HardwareSerial9000Patch**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserial9000patch) | **PATCH** /rest/vcenter/vm/vm-33/hardware/serial/9000 | Update
*VMSerialApi* | [**restVcenterVmVm33HardwareSerialGet**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserialget) | **GET** /rest/vcenter/vm/vm-33/hardware/serial | List
*VMSerialApi* | [**restVcenterVmVm33HardwareSerialPost**](docs/Api/VMSerialApi.md#restvcentervmvm33hardwareserialpost) | **POST** /rest/vcenter/vm/vm-33/hardware/serial/ | Create

## Documentation For Models


## Documentation For Authorization


## basicAuth

- **Type**: HTTP basic authentication

## noauthAuth

- **Type**: HTTP basic authentication


## Author



