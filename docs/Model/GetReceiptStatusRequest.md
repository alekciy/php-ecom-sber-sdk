# # GetReceiptStatusRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user_name** | **string** | Логин Клиента, полученный при подключении к ПШ |
**password** | **string** | Пароль Клиента, полученный при подключении к ПШ |
**receipt_status** | **int** | Статус чека * &#x60;0&#x60; - не определен; * &#x60;1&#x60; - ожидается отправка или переотправка чека * &#x60;2&#x60; - чек отправлен, ожидание результата обработки * &#x60;3&#x60; - чек обработан успешно * &#x60;4&#x60; - ошибка обработки чека * &#x60;5&#x60; - ошибка отправки чека (исчерпаны попытки отправки) * &#x60;6&#x60; - некорректные данные для отправки чека | [optional]
**receipt_id** | **string** | Идентификатор чека, присвоенный кассовым сервисом (uuid) |
**order_id** | **string** | Уникальный номер заказа в Платёжном шлюзе |
**order_number** | **string** | Уникальный номер (идентификатор) заказа в системе Клиента |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
