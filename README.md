# hotel

9 вариант

Состав команды и обязанности:

  •	Гулимов Владимир - работа с БДУ ФСТЭК (таблица негативных последствий, модель нарушителя, модель угроз ИБ, развёртывание сайта).

  •	Канищев Никита - техническая сторона (Создание схемы и контрольная проверка информации и её запись в github);

  •	Намср Саллов - работа с Mitre ATT&CK (составление и проработка возможных сценариев атаки на систему и/или её компоненты, актуализация угроз);

  •	Общее: составление отчёта


  
Описание проекта

Информационная система "Отель "Москва"

Составные части информационной системы:

  1. Веб-сервер (База данных);

  2. Веб-приложение (converse.js).



Описание условного места установки системы

Программа расположена на сервере отеля

Требования к серверу:

Веб-сервер: Apache 1.3, Apache 2.x, Nginx or Microsoft IIS

  •	PHP версия: PHP 5.6+ to PHP 7.4

  •	Версия MySQL: 5.1+ to 5.7 установленная с созданной базой данных.

  • SSH или FTP доступ (уточните у своего хостинга свои учетные данные)

  •	В конфигурации PHP попросите вашего провайдера установить memory_limit на "128M", upload_max_filesize на "16M" , max_execution_time на "500" и allow_url_fopen "on"

  •	Сертификат SSL, если вы планируете обрабатывать платежи внутри компании (например, не используя PayPal) 

  •	Требуемые расширения PHP: PDO_MySQL, cURL, OpenSSL, SOAP, GD, SimpleXML, DOM, Zip, Phar

  •	Конфигурации локального сервера 

  •	Поддерживаемая операционная система: Windows, Mac и Linux. Готовый пакет: WampServer (для Windows), Xampp (для Windows и Mac) или EasyPHP (для Windows).



Выполненные задачи

Канищев Никита:

1.	Создание схемы инфраструктуры (схема на данный момент в разработке);

Саллов Намср:

1.	Разработка первых сценариев атаки

2.	Cоставление таблицы актуальных Угроз Безопасности Информации (УБИ).

Гулимов Владимир:

1.	Составление таблицы типовых негативных последствий

2.	Составление промежуточной таблицы типовых негативных последствий с количественной оценкой;

3.	Составление таблицы базовых рисков на основе таблицы типовых негативных последствий;

4.	Составление таблицы соответствия нарушителей, целей и рисков

5.	Составление таблицы актуальных нарушителей и рисков

6.	Составление таблицы актуальных Угроз Безопасности Информации (УБИ).


!!!

Развернуть сайт удалось, но создать базу данных не получилось, файл с командами(history.txt) и папка со скриншотами(historyscrin) прилагаются.
