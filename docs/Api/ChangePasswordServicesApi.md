# SberPay\ChangePasswordServicesApi

All URIs are relative to https://ecomtest.sberbank.ru, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**generate()**](ChangePasswordServicesApi.md#generate) | **POST** /ecomm/gw/partner/api/accounts/v1/apikey/generate | Генерация ключа Клиента для работы с сервисами платежного шлюза через SDK. |
| [**setPermanentPassword()**](ChangePasswordServicesApi.md#setPermanentPassword) | **POST** /ecomm/gw/partner/api/accounts/v1/set-permanent-password | Установка постоянного пароля |


## `generate()`

```php
generate($generate_apikey_request): \SberPay\Model\GenerateApikeyResponse
```

Генерация ключа Клиента для работы с сервисами платежного шлюза через SDK.

Сервис для генерации ключа Клиента для работы с сервисами платежного шлюза через SDK. Может быть создано не более 5 активных ключей.

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new SberPay\Api\ChangePasswordServicesApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$generate_apikey_request = {"userName":"testUserName","password":"testPassword","description":"testDescription","merchantLogin":"merchantLogin"}; // \SberPay\Model\GenerateApikeyRequest

try {
    $result = $apiInstance->generate($generate_apikey_request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ChangePasswordServicesApi->generate: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **generate_apikey_request** | [**\SberPay\Model\GenerateApikeyRequest**](../Model/GenerateApikeyRequest.md)|  | |

### Return type

[**\SberPay\Model\GenerateApikeyResponse**](../Model/GenerateApikeyResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`, `text/html`, `test/html`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)

## `setPermanentPassword()`

```php
setPermanentPassword($set_permanent_password_request): \SberPay\Model\SetPermanentPasswordResponse
```

Установка постоянного пароля

Сервис для смены временного пароля на постоянный

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new SberPay\Api\ChangePasswordServicesApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$set_permanent_password_request = {"login":"testUserName","tmpPassword":"testPassword","password":"NewPassword"}; // \SberPay\Model\SetPermanentPasswordRequest | Запрос предназначен для изменение временного пароля, выданного при регистрации Клиента на ПШ на постоянный пароль на стороне Клиента.

try {
    $result = $apiInstance->setPermanentPassword($set_permanent_password_request);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ChangePasswordServicesApi->setPermanentPassword: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **set_permanent_password_request** | [**\SberPay\Model\SetPermanentPasswordRequest**](../Model/SetPermanentPasswordRequest.md)| Запрос предназначен для изменение временного пароля, выданного при регистрации Клиента на ПШ на постоянный пароль на стороне Клиента. | |

### Return type

[**\SberPay\Model\SetPermanentPasswordResponse**](../Model/SetPermanentPasswordResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`, `test/html`, `text/html`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
