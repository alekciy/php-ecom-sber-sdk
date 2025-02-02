# # PaymentOrderBindingRequestJsonParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**has_valuable_items** | **string** | Маркер наличия высоколиквидной электроники в заказе:  * &#x60;00&#x60; &#x3D; Не содержит высоколиквидной электроники;  * &#x60;01&#x60; &#x3D; Содержит высоколиквидную электронику; | [optional]
**acct_id** | **string** | Идентификатор аккаунта Плательщика в ТСП | [optional]
**ch_acc_date** | **string** | Дата создания аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**ch_acc_age_ind** | **string** | Возраст аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; No account (guest check-out);   * &#x60;02&#x60; &#x3D; Created during this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**ch_acc_change_ind** | **string** | Период времени с последнего редактирования аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; Changed during this transaction;   * &#x60;02&#x60; &#x3D; Less than 30 days;   * &#x60;03&#x60; &#x3D; 30-60 days;   * &#x60;04&#x60; &#x3D; More than 60 days. | [optional]
**ship_addr_city** | **string** | Город доставки товара | [optional]
**ship_delivery_point_id** | **string** | Идентификатор ПВЗ доставки товара | [optional]
**mri_reorder_items_ind** | **string** | Индикатор повторной покупки в ТСП:   * &#x60;01&#x60; &#x3D; First time ordered;   * &#x60;02&#x60; &#x3D; Reordered. | [optional]
**mobile_phone** | **string** | Мобильный телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**ship_name_indicator** | **string** | Признак соответствия имени в аккаунте Плательщика и имени получателя заказа:   * &#x60;01&#x60; &#x3D; Account Name identical to shipping Name;   * &#x60;02&#x60; &#x3D; Account Name different than shipping Name. | [optional]
**suspicious_acc_activity** | **string** | Признак наличия случаев подозрительной активности (включая предыдущие случаи мошенничества) для аккаунта Плательщика:   * &#x60;01&#x60; &#x3D; No suspicious activity has been observed;   * &#x60;02&#x60; &#x3D; Suspicious activity has been observed. | [optional]
**provision_attempts_day** | **string** | Количество попыток добавления карты за последние 24 часа | [optional]
**ship_addr_line1** | **string** | Адрес доставки товара | [optional]
**ship_addr_line2** | **string** | Адрес доставки товара | [optional]
**ship_addr_line3** | **string** | Адрес доставки товара | [optional]
**ship_address_usage** | **string** | Дата первого использования адреса доставки для аккаунта Плательщика в формате YYYYMMDD | [optional]
**ship_address_usage_ind** | **string** | Период времени с момента первого использования адреса доставки для аккаунта Плательщика:   * &#x60;01&#x60; &#x3D; This transaction;   * &#x60;02&#x60; &#x3D; Less than 30 days;   * &#x60;03&#x60; &#x3D; 30-60 days;   * &#x60;04&#x60; &#x3D; More than 60 days. | [optional]
**mri_delivery_timeframe** | **string** | Срок доставки товара: * &#x60;01&#x60; &#x3D; Electronic Delivery; * &#x60;02&#x60; &#x3D; Same day shipping; * &#x60;03&#x60; &#x3D; Overnight shipping; * &#x60;04&#x60; &#x3D; Two-day or more shipping. | [optional]
**mri_ship_indicator** | **string** | Способ доставки, выбранный для операции:   * &#x60;01&#x60; &#x3D; Ship to cardholder&#39;s billing address;   * &#x60;02&#x60; &#x3D; Ship to another verified address on file with merchant;   * &#x60;03&#x60; &#x3D; Ship to address that is different than the cardholder&#39;s billing address;   * &#x60;04&#x60; &#x3D; “Ship to Store” / Pick-up at local store (Store address shall be populated in shipping address fields);   * &#x60;05&#x60; &#x3D; Digital goods (includes online services, electronic gift cards and redemption codes);   * &#x60;06&#x60; &#x3D; Travel and Event tickets, not shipped;   * &#x60;07&#x60; &#x3D; Other (for example, Gaming, digital services not shipped, emedia subscriptions, etc.). | [optional]
**ch_acc_pw_change** | **string** | Дата последнего изменения пароля или сброса аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**ch_acc_pw_change_ind** | **string** | Период времени с последнего изменения пароля или сброса аккаунта Плательщика в ТСП:   * &#x60;01&#x60; &#x3D; No change;   * &#x60;02&#x60; &#x3D; Changed during this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**nb_purchase_account** | **string** | Количество покупок, совершенных с аккаунта Плательщика за последние 6 месяцев | [optional]
**txn_activity_day** | **string** | Количество операций (успешных и незавершенных), совершенных с аккаунта Плательщика за последние 24 часа всеми платёжными средствами | [optional]
**txn_activity_year** | **string** | Количество операций (успешных и незавершенных), совершенных с аккаунта Плательщика за последний год всеми платёжными средствами | [optional]
**payment_acc_age** | **string** | Дата добавления платёжного метода в аккаунте Плательщика в формате YYYYMMDD | [optional]
**payment_acc_ind** | **string** | Период времени с момента добавления платёжного метода в аккаунт Плательщика:   * &#x60;01&#x60; &#x3D; No account (guest check-out);   * &#x60;02&#x60; &#x3D; During this transaction;   * &#x60;03&#x60; &#x3D; Less than 30 days;   * &#x60;04&#x60; &#x3D; 30-60 days;   * &#x60;05&#x60; &#x3D; More than 60 days. | [optional]
**ch_acc_change** | **string** | Дата последнего редактирования аккаунта Плательщика в ТСП в формате YYYYMMDD | [optional]
**dest_wallet_num** | **string** | Номер (идентификатор) электронного кошелька получателя электронных денежных средств.  &lt;span style&#x3D;\&quot;color:red;\&quot;&gt;Обязательно, если MCC&#x3D;6050 или 6051&lt;/span&gt; | [optional]
**dest_phone_num** | **string** | Номер телефона абонента получателя денежных средств.  &lt;span style&#x3D;\&quot;color:red;\&quot;&gt;Обязательно, если MCC&#x3D;4814&lt;/span&gt; | [optional]
**dest_card_num** | **string** | Номер карты получателя перевода.  &lt;span style&#x3D;\&quot;color:red;\&quot;&gt;Обязательно при проведении операции перевода денежных средств на карту, кредитование, для MCC&#x3D;6538&lt;/span&gt; | [optional]
**dest_acct_num** | **string** | Конкатенированное значение БИК Банка (bik) получателя (044583999) и номер счета (bankAccount) получателя 40817810570000123456 для перевода  &lt;span style&#x3D;\&quot;color:red;\&quot;&gt;Обязательно при проведении операции перевода денежных средств на счет, кредитование, для MCC&#x3D;6538&lt;/span&gt; | [optional]
**three_ds_requestor_dec_req_ind** | **string** | Признак поддержки сценария отложенной аутентификации. Допустимые значения: * &#x60;Y&#x60; &#x3D; отложенная аутентификация поддерживается и предпочтительна | [optional]
**three_ds_requestor_dec_max_time** | **string** | Максимальное время ожидания завершения аутентификации в сценарии decoupled (в минутах). Должно быть в интервале от 1 до 10080. | [optional]
**challenge_window_size** | **string** | Разрешение страниц ACS, в случае проведения Challenge с Плательщиком по протоколу 3-D Secure на базе EMV 2.x.x   * &#x60;01&#x60; &#x3D; 250x400   * &#x60;02&#x60; &#x3D; 390x400 (по умолчанию)   * &#x60;03&#x60; &#x3D; 500x600   * &#x60;04&#x60; &#x3D; 600x400   * &#x60;05&#x60; &#x3D; Full screen | [optional]
**browser_accept_header** | **string** | Содержимое HTTP accept headers браузера Плательщика. Обязательно для Browser-based операций |
**browser_ip** | **string** | IP адрес Плательщика, полученный из HTTP заголовков браузера. Обязательно для Browser-based операций |
**browser_java_enabled** | **bool** | Возможность браузера выполнять Java, значение свойства navigator.javaEnabled. Обязательно, если browserJavascriptEnabled &#x3D; true | [optional]
**browser_javascript_enabled** | **bool** | Возможность браузера выполнять JavaScript. Обязательно для Browser-based операций. |
**browser_language** | **string** | Язык браузера согласно ETF BCP47, значение свойства navigator.language. Обязательно, если browserJavascriptEnabled &#x3D; true | [optional]
**browser_color_depth** | **string** | Битовая глубина цветовой палитры экрана, значение свойства screen.colorDepth. Обязательно, если browserJavascriptEnabled &#x3D; true   * &#x60;1&#x60; &#x3D; 1 bit   * &#x60;4&#x60; &#x3D; 4 bits   * &#x60;8&#x60; &#x3D; 8 bits   * &#x60;15&#x60; &#x3D; 15 bits   * &#x60;16&#x60; &#x3D; 16 bits   * &#x60;24&#x60; &#x3D; 24 bits   * &#x60;32&#x60; &#x3D; 32 bits   * &#x60;48&#x60; &#x3D; 48 bits | [optional]
**browser_screen_height** | **string** | Высота экрана в пикселях, значение свойства screen.height. Обязательно, если browserJavascriptEnabled &#x3D; true | [optional]
**browser_screen_width** | **string** | Ширина экрана в пикселях, значение свойства screen.width. Обязательно, если browserJavascriptEnabled &#x3D; true | [optional]
**browser_tz** | **string** | Смещение в минутах между часовым поясом UTC и местным временем браузера. Обязательно, если browserJavascriptEnabled &#x3D; true | [optional]
**browser_user_agent** | **string** | Содержимое заголовка HTTP user-agent. Обязательно для Browser-based операций |
**bill_addr_city** | **string** | Город доставки счета | [optional]
**bill_addr_country** | **string** | Цифровой код страны доставки счета согласно ISO 3166-1 | [optional]
**bill_addr_line1** | **string** | Адрес доставки счета | [optional]
**bill_addr_line2** | **string** | Адрес доставки счета | [optional]
**bill_addr_line3** | **string** | Адрес доставки счета | [optional]
**bill_addr_post_code** | **string** | Почтовый индекс адреса доставки счета | [optional]
**bill_addr_state** | **string** | Штат или провинция адреса доставки счета согласно ISO 3166-2 | [optional]
**ship_addr_country** | **string** | Цифровой код страны доставки товара согласно ISO 3166-1 | [optional]
**ship_addr_post_code** | **string** | Почтовый индекс адреса доставки товара | [optional]
**ship_addr_state** | **string** | Штат или провинция адреса доставки товара согласно ISO 3166-2 | [optional]
**work_phone** | **string** | Рабочий телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**home_phone** | **string** | Домашний телефон в формате \&quot;код страны\&quot;-\&quot;номер телефона\&quot; (например, 7-4951234567) согласно ITU-E.164 | [optional]
**mri_delivery_email_address** | **string** | Для электронной доставки, электронный адрес доставки товара | [optional]
**mri_gift_card_amount** | **string** | При покупке предоплаченной или подарочной карты, общий номинал карт в мажорных единицах валюты | [optional]
**mri_gift_card_count** | **string** | При покупке предоплаченной или подарочной карты, общее количество карт | [optional]
**mri_gift_card_curr** | **string** | При покупке предоплаченной или подарочной карты, цифровой код валюты карты согласно ISO-4217 | [optional]
**mri_pre_order_date** | **string** | Дата поставки товара под заказ в формате YYYYMMDD для предварительного заказа | [optional]
**mri_pre_order_purchase_ind** | **string** | Индикатор заказа товаров не в наличии (под заказ):   * &#x60;01&#x60; &#x3D; Merchandise available;   * &#x60;02&#x60; &#x3D; Future availability. | [optional]
**three_ds_req_prior_auth_data** | **string** | Данные первой аутентификации в цепочке, которая произошла до текущей операции (например, первой аутентификации для recurring платежа) | [optional]
**three_ds_req_prior_auth_method** | **string** | Способ аутентификации Плательщика в первой операции в цепочке:   * &#x60;01&#x60; &#x3D; Frictionless authentication occurred by ACS;   * &#x60;02&#x60; &#x3D; Cardholder challenge occurred by ACS;   * &#x60;03&#x60; &#x3D; AVS verified;   * &#x60;04&#x60; &#x3D; Other issuer methods;   * &#x60;05&#x60;–&#x60;79&#x60; &#x3D; Reserved for EMVCo future use (values invalid until defined by EMVCo);   * &#x60;80&#x60;–&#x60;99&#x60; &#x3D; Reserved for DS use. | [optional]
**three_ds_req_prior_auth_timestamp** | **string** | Дата и время в UTC первой аутентификации в цепочке в формате YYYYMMDDHHMM | [optional]
**three_ds_req_prior_ref** | **string** | ACS Transaction ID первой аутентификации в цепочке запросов (например, первой аутентификации для recurring платежа) | [optional]
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
**device_category** | **string** | Категория устройства, в котором инициирована аутентификация 3-D Secure. Допустимые значения:   * &#x60;0&#x60; (BRW) &#x3D; аутентификация инициирована в браузере Плательщика (по умолчанию);   * &#x60;1&#x60; (APP) &#x3D; аутентификация инициирована в мобильном приложении Плательщика;   * &#x60;2&#x60; (3RI) &#x3D; аутентификация инициирована сервером ТСТ. |
**sdk_app_id** | **string** | Идентификатор в формате uuid, создаваемый при каждой установке приложения ТСТ и хранимый в 3DS SDK. Обязательно для deviceCategory &#x3D; 1 |
**sdk_reference_number** | **string** | Идентификатор вендора и версии 3DS SDK, присвоенный EMVCo. Обязательно для deviceCategory &#x3D; 1 |
**sdk_trans_id** | **string** | Идентификатор в формате uuid, присваиваемый 3DS SDK для каждого запроса аутентификации. Обязательно для deviceCategory &#x3D; 1 |
**sdk_max_timeout** | **string** | Максимальное время в минутах для проведения аутентификации (должно быть не меньше 5). По умолчанию присваивается значение 5 | [optional]
**sdk_enc_data** | **string** | Информация об устройстве Плательщика. Обязательно для deviceCategory &#x3D; 1 |
**sdk_ephem_pub_key** | **string** | Сессионный публичный ключ, генерируемый 3DS SDK для каждого запроса аутентификации, передаваемый в кодировке base64. Обязательно для deviceCategory &#x3D; 1 |
**device_render_options** | **string** | Объект с типами UI, поддерживаемыми 3DS SDK и приложением ТСТ, передаваемый в кодировке base64. По умолчанию поддерживаются все возможные типы UI | [optional]
**name1** | **mixed** | Дополнительный параметр 1 | [optional]
**name2** | **mixed** | Дополнительный параметр 2 | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
