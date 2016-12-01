# client
Клиентская часть Кардинала

Инсталяция для разработчика
===========================

В корне нужно создать ссылку `ext` на дистрибутив Sencha Ext JS 6.2.0.
Также должен быть установлен Sencha Cmd версии 6.2.1.


В серверной части в папке client хранится production-версия клиентской части программы.
Ссылка на нее должна находится в `C:\@repositories\cardinalkeeper-client\build\production\` и называться `Cardinal`.

Иными словами:

`C:\@repositories\cardinalkeeper-client\build\production\Cardinal` -> `C:\@repositories\cardinalkeeper-server\client`.

Таким образом папка client обновляется при вызове команды `sencha app build`.



Команды Sencha Cmd
==================

sencha app watch - Запустить клиент для разработки.

sencha app build - Создать билд для обновления клиента в папке сервера.