# Динамическая подмена заголовка на сайте через GTM
Этот код динамически заменяет заголовок h1 на странице сайта на основе ключевого слова, переданного в URL.

Например, если URL содержит параметр ?utm_term=delivery, заголовок h1 изменится на «Delivery». 

Заголовки можно создать в [таблице](https://docs.google.com/spreadsheets/d/1ZeJ_G0ilwsE55997lBeBQQgUS-rxt3ZNSm-cFQCSIps/edit?gid=0#gid=0 "Открыть таблицу").

## Импортируйте JSON (import_to_GTM) в GTM, замените measurement id в теге.

Импортирует:
* Тег cHTML - Dynamic H1 replacement
* Триггер PW - URL - ps_term not undefined
* Переменную - Url - ps_term

Необходимо заменить в cHTML - Dynamic H1 replacement заголовки в var keywords.