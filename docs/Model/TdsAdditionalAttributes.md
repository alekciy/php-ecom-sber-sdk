# # TdsAdditionalAttributes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bill_addr_city** | **string** | Город доставки счета | [optional]
**bill_addr_country** | **string** | Цифровой код страны доставки счета согласно ISO 3166-1 | [optional]
**bill_addr_line1** | **string** | Адрес доставки счета | [optional]
**bill_addr_line2** | **string** | Адрес доставки счета | [optional]
**bill_addr_line3** | **string** | Адрес доставки счета | [optional]
**bill_addr_post_code** | **string** | Почтовый индекс адреса доставки счета | [optional]
**bill_addr_state** | **string** | Штат или провинция адреса доставки счета согласно ISO 3166-2 | [optional]
**ship_addr_city** | **string** | Город доставки товара | [optional]
**ship_addr_country** | **string** | Цифровой код страны доставки товара согласно ISO 3166-1 | [optional]
**ship_addr_line1** | **string** | Адрес доставки товара | [optional]
**ship_addr_line2** | **string** | Адрес доставки товара | [optional]
**ship_addr_line3** | **string** | Адрес доставки товара | [optional]
**ship_addr_post_code** | **string** | Почтовый индекс адреса доставки товара | [optional]
**ship_addr_state** | **string** | Штат или провинция адреса доставки товара согласно ISO 3166-2 | [optional]
**mobile_phone** | **string** | Мобильный телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**work_phone** | **string** | Рабочий телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**home_phone** | **string** | Домашний телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**mri_delivery_email_address** | **string** | Для электронной доставки, электронный адрес доставки товара | [optional]
**mri_delivery_timeframe** | **string** | Срок доставки товара: * &#x60;01&#x60; &#x3D; Electronic Delivery; * &#x60;02&#x60; &#x3D; Same day shipping; * &#x60;03&#x60; &#x3D; Overnight shipping; * &#x60;04&#x60; &#x3D; Two-day or more shipping. | [optional]
**mri_gift_card_amount** | **string** | При покупке предоплаченной или подарочной карты, общий номинал карт в мажорных единицах валюты | [optional]
**mri_gift_card_count** | **string** | При покупке предоплаченной или подарочной карты, общее количество карт | [optional]
**mri_gift_card_curr** | **string** | При покупке предоплаченной или подарочной карты, цифровой код валюты карты согласно ISO-4217 | [optional]
**mri_pre_order_date** | **string** | Дата поставки товара под заказ в формате YYYYMMDD для предварительного заказа | [optional]
**mri_pre_order_purchase_ind** | **string** | Индикатор заказа товаров не в наличии (под заказ):   * &#x60;01&#x60; &#x3D; Merchandise available;   * &#x60;02&#x60; &#x3D; Future availability. | [optional]
**mri_reorder_items_ind** | **string** | Индикатор повторной покупки в ТСП:   * &#x60;01&#x60; &#x3D; First time ordered;   * &#x60;02&#x60; &#x3D; Reordered. | [optional]
**mri_ship_indicator** | **string** | Способ доставки, выбранный для операции:   * &#x60;01&#x60; &#x3D; Ship to cardholder&#39;s billing address;   * &#x60;02&#x60; &#x3D; Ship to another verified address on file with merchant;   * &#x60;03&#x60; &#x3D; Ship to address that is different than the cardholder&#39;s billing address;   * &#x60;04&#x60; &#x3D; “Ship to Store” / Pick-up at local store (Store address shall be populated in shipping address fields);   * &#x60;05&#x60; &#x3D; Digital goods (includes online services, electronic gift cards and redemption codes);   * &#x60;06&#x60; &#x3D; Travel and Event tickets, not shipped;   * &#x60;07&#x60; &#x3D; Other (for example, Gaming, digital services not shipped, emedia subscriptions, etc.). | [optional]
**three_ds_req_prior_auth_data** | **string** | Данные первой аутентификации в цепочке, которая произошла до текущей операции (например, первой аутентификации для recurring платежа) | [optional]
**three_ds_req_prior_auth_method** | **string** | Способ аутентификации Плательщика в первой операции в цепочке:   * &#x60;01&#x60; &#x3D; Frictionless authentication occurred by ACS;   * &#x60;02&#x60; &#x3D; Cardholder challenge occurred by ACS;   * &#x60;03&#x60; &#x3D; AVS verified;   * &#x60;04&#x60; &#x3D; Other issuer methods;   * &#x60;05&#x60;–&#x60;79&#x60; &#x3D; Reserved for EMVCo future use (values invalid until defined by EMVCo);   * &#x60;80&#x60;–&#x60;99&#x60; &#x3D; Reserved for DS use. | [optional]
**three_ds_req_prior_auth_timestamp** | **string** | Дата и время в UTC первой аутентификации в цепочке в формате YYYYMMDDHHMM | [optional]
**three_ds_req_prior_ref** | **string** | ACS Transaction ID первой аутентификации в цепочке запросов (например, первой аутентификации для recurring платежа) | [optional]
**acct_id** | **string** | Идентификатор аккаунта Плательщика в ТСП | [optional]
**ch_acc_age_ind** | **string** | Возраст аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; No account (guest check-out);   * &#x60;02&#x60; &#x3D; Created during this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**ch_acc_change** | **string** | Дата последнего редактирования аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**ch_acc_change_ind** | **string** | Период времени с последнего редактирования аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; Changed during this transaction;   * &#x60;02&#x60; &#x3D; Less than 30 days;   * &#x60;03&#x60; &#x3D; 30-60 days;   * &#x60;04&#x60; &#x3D; More than 60 days. | [optional]
**ch_acc_date** | **string** | Дата создания аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**ch_acc_pw_change** | **string** | Дата последнего изменения пароля или сброса аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**ch_acc_pw_change_ind** | **string** | Период времени с последнего изменения пароля или сброса аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; No change;   * &#x60;02&#x60; &#x3D; Changed during this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**nb_purchase_account** | **string** | Количество покупок, совершенных с аккаунта Плательщика за последние 6 месяцев | [optional]
**provision_attempts_day** | **string** | Количество попыток добавления карты за последние 24 часа | [optional]
**txn_activity_day** | **string** | Количество операций (успешных и незавершенных), совершенных с аккаунта Плательщика за последние 24 часа всеми платёжными средствами | [optional]
**txn_activity_year** | **string** | Количество операций (успешных и незавершенных), совершенных с аккаунта Плательщика за последний год всеми платёжными средствами | [optional]
**payment_acc_age** | **string** | Дата добавления платёжного метода в аккаунте Плательщика в формате YYYYMMDD | [optional]
**payment_acc_ind** | **string** | Период времени с момента добавления платёжного метода в аккаунт Плательщика:   * &#x60;01&#x60; &#x3D; No account (guest check-out);   * &#x60;02&#x60; &#x3D; During this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**ship_address_usage** | **string** | Дата первого использования адреса доставки для аккаунта Плательщика в формате YYYYMMDD | [optional]
**ship_address_usage_ind** | **string** | Период времени с момента первого использования адреса доставки для аккаунта Плательщика:   * &#x60;01&#x60; &#x3D; This transaction;   * &#x60;02&#x60; &#x3D; Less than 30 days;   * &#x60;03&#x60; &#x3D; 30-60 days;   * &#x60;04&#x60; &#x3D; More than 60 days. | [optional]
**ship_name_indicator** | **string** | Признак соответствия имени в аккаунте Плательщика и имени получателя заказа:   * &#x60;01&#x60; &#x3D; Account Name identical to shipping Name;   * &#x60;02&#x60; &#x3D; Account Name different than shipping Name. | [optional]
**suspicious_acc_activity** | **string** | Признак наличия случаев подозрительной активности (включая предыдущие случаи мошенничества) для аккаунта Плательщика:   * &#x60;01&#x60; &#x3D; No suspicious activity has been observed;   * &#x60;02&#x60; &#x3D; Suspicious activity has been observed. | [optional]
**three_ds_req_auth_data** | **string** | Данные аутентификации Плательщика в ТСП | [optional]
**three_ds_req_auth_method** | **string** | Способ аутентификации Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; No 3DS Requestor authentication occurred (i.e. cardholder “logged in” as guest);   * &#x60;02&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using 3DS Requestor&#39;s own credentials;   * &#x60;03&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using federated ID;   * &#x60;04&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using issuer credentials;   * &#x60;05&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using third-party authentication;   * &#x60;06&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using FIDO Authenticator;   * &#x60;07&#x60; &#x3D; Login to the cardholder account at the 3DS Requestor system using FIDO Authenticator;   * &#x60;08&#x60; &#x3D; SRC Assurance Data;   * &#x60;09&#x60;–&#x60;79&#x60; &#x3D; Reserved for EMVCo future use (values invalid until defined by EMVCo);   * &#x60;80&#x60;–&#x60;99&#x60; &#x3D; Reserved for DS use. | [optional]
**three_ds_req_auth_timestamp** | **string** | Дата и время в UTC аутентификации Плательщика в ТСП в формате YYYYMMDDHHMM | [optional]
**acct_type** | **string** | Тип счета карты Плательщика:   * &#x60;01&#x60; &#x3D; Not Applicable;   * &#x60;02&#x60; &#x3D; Credit;   * &#x60;03&#x60; &#x3D; Debit;   * &#x60;04&#x60;–&#x60;79&#x60; &#x3D; Reserved for EMVCo future use (values invalid until defined by EMVCo);   * &#x60;80&#x60;–&#x60;99&#x60; &#x3D; DS or Payment System-specific. | [optional]
**trans_type** | **string** | Тип операции:   * &#x60;01&#x60; &#x3D; Goods/ Service Purchase;   * &#x60;03&#x60; &#x3D; Check Acceptance;   * &#x60;10&#x60; &#x3D; Account Funding;   * &#x60;11&#x60; &#x3D; Quasi-Cash Transaction;   * &#x60;28&#x60; &#x3D; Prepaid Activation and Load. | [optional]
**addr_match** | **string** | Признак соответствия адреса доставки товара и адреса доставки счета:   * &#x60;Y&#x60; &#x3D; Shipping Address matches Billing Address;   * &#x60;N&#x60; &#x3D; Shipping Address does not match Billing Address. | [optional]
**three_ds_requestor_challenge_ind** | **string** | Признак необходимости проведения Challenge c Плательщиком:   * &#x60;01&#x60; &#x3D; No preference;   * &#x60;02&#x60; &#x3D; No challenge requested;   * &#x60;03&#x60; &#x3D; Challenge requested 3DS Requestor Preference;   * &#x60;04&#x60; &#x3D; Challenge requested Mandate;   * &#x60;05&#x60;–&#x60;79&#x60; &#x3D; Reserved for EMVCo future use (values invalid until defined by EMVCo);   * &#x60;80&#x60;-&#x60;99&#x60; &#x3D; Reserved for DS use. | [optional]
**purchase_instal_data** | **string** | Максимальное количество авторизаций для Installment платежей | [optional]
**recurring_expiry** | **string** | Дата последнего рекуррентного платежа в формате YYYYMMDD | [optional]
**recurring_frequency** | **string** | Минимальное количество дней между рекуррентными платежами | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
