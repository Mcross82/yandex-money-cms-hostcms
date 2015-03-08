#yandexmoney-hostcms

Модуль оплаты yandexmoney-hostcms необходим для интеграции с сервисом [Яндекс.Касса](http://kassa.yandex.ru/) на базе HostCMS. 

Доступные платежные методы, если вы работаете как юридическое лицо:
* **Банковские карты** -  Visa (включая Electron), MasterCard и Maestro любого банка мира
* **Электронные деньги** - Яндекс.Деньги и WebMoney
* **Наличные** - [Более 170 тысяч пунктов](https://money.yandex.ru/pay/doc.xml?id=526209) оплаты по России
* **Баланс телефона** - Билайн, МегаФон и МТС
* **Интернет банкинг** - Альфа-Клик и Сбербанк Онлайн

###Требования к CMS HostCMS:
* версия 6

###Установка модуля
Внимание! Необходимо сделать резервную копию всех изменяемых файлов Вашего магазина.

Для установки данного модуля необходимо загрузить [архив](https://github.com/yandex-money/yandex-money-cms-hostcms/archive/master.zip) и переместить папку `hostcmsfiles` в корень вашего сайта!
Далее необходимо добавить в `Справочник платежных систем` новый элемент и вставить код из файла `handlerXX.php` в поле `Обработчик платежной системы`. 

###Нашли ошибку или у вас есть предложение по улучшению модуля?
Пишите нам cms@yamoney.ru
