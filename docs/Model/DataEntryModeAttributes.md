# # DataEntryModeAttributes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data_entry_mode** | **string** | Режим ввода платёжных данных в операции. В случае отсутствия воспринимается, как операция, инициированная Плательщиком без сохранения реквизитов.   * &#x60;CAPTURED&#x60; &#x3D; Операция инициирована Плательщиком; реквизиты сохраняются для последующих операций;   * &#x60;DEFERRED&#x60; &#x3D; Операция инициирована Плательщиком; реквизиты сохраняются для последующих операций, отложенная авторизация;   * &#x60;CREDENTIAL-ON-FILE&#x60; &#x3D; Операция инициирована Плательщиком с использованием ранее сохраненных реквизитов;   * &#x60;RECURRING&#x60; &#x3D; Операция инициирована Клиентом с использованием сохраненных реквизитов; периодический платёж по поручению Плательщика без графика;   * &#x60;INSTALLMENT&#x60; &#x3D; Операция инициирована Клиентом с использованием сохраненных реквизитов; периодический платёж по поручению Плательщика по графику;   * &#x60;RESUBMISSION&#x60; &#x3D; Операция инициирована Клиентом с использованием сохраненных реквизитов; повторная авторизация. | [optional]
**initial_order_id** | **string** | Идентификатор заказа в ПШ сохранения реквизитов Плательщика. Передается в операциях, осуществляемых по ранее сохраненным реквизитам Плательщика | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)