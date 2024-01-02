Руководство пользователя для приложения ModbusMaster
Общее описание
Приложение ModbusMaster разработано для работы с внешними устройствами через последовательный порт RS-232, используя протокол Modbus RTU. Оно позволяет настраивать параметры порта, отправлять запросы к устройствам и отображать полученные данные.

Начало работы
Открытие порта:

Запустите приложение.
Выберите необходимый последовательный порт из списка в разделе "Список портов".
Настройте параметры порта (скорость обмена, число бит в байте, тип проверки на четность, число стоповых бит).
Нажмите кнопку "Open Port" для открытия порта.
Настройка запроса:

Введите номер стартового регистра в поле "Стартовый регистр".
Укажите количество считываемых регистров в поле "Количество регистров".
Отправка запроса:

Нажмите кнопку "Send Request" для отправки запроса.
После отправки запроса, данные будут автоматически считаны и отображены в таблице.
Работа с данными
Просмотрите данные в таблице, где отображаются номера запрошенных регистров и их значения.
Вы можете изменить формат отображения данных (двоичный, шестнадцатеричный, десятичный) с помощью выпадающего списка "Формат отображения".
Закрытие порта
Для закрытия порта нажмите кнопку "Close Port". Это прекратит обмен данными и освободит порт для других приложений.
Дополнительные функции
В меню "Файл" доступны опции "Открыть" и "Сохранить" для работы с файлами, а также опция "Выход" для закрытия приложения.