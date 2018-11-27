# Лещёв Н.В.  гр.588-М1
Предметная область:  Интернет-провайдер (25).

# 1. Описание таблиц БД
Таблицы в Oracle SQL Developer:

![default](https://user-images.githubusercontent.com/18438169/49075062-a2674e80-f268-11e8-866b-126948a8f1b9.PNG)

**A_DOGOVOR:**

* "ID_DOGOVOR" - идентификатор договора;
* "ID_USER" - идентификатор пользователя;
* "TARIF" - название тарифа;
* "TRAFFIC" - безлимитный интернет трафик (Мбит/с);
* "DATA_CONECT" - дата подключения;
* "VALIDITY" - действителен до;
* "PRICE" - цена;
* "USER_LOGIN" - логин;
* "USER_PASSWORD" - пароль.

**A_USER:**

* "ID_USER" - идентификатор пользователя;
* "SURNAME" - фамилия;
* "NAME" - имя;
* "PATRONIMIC" - отчество;
* "PASPORT" - № паспорта;
* "ADRESS" - адрес;
* "TEL_NUMBER" - № телефона.
___

# 2. Генерация данных в таблицы
Для генерации данных был использован онлайн ресурс: https://www.mockaroo.com.

**Настройки генератора для A_USER:**

![3](https://user-images.githubusercontent.com/18438169/49077300-8023ff80-f26d-11e8-8919-10155e4bcbb9.PNG)

**Настройки генератора для A_Dogovor:**

![6](https://user-images.githubusercontent.com/18438169/49077372-b1043480-f26d-11e8-83cf-202a6a14d5b5.PNG)

Файл сгенерированных данных для A_USER:
[Users.xlsx](https://github.com/Fenrik/Leshchev-Nikita/files/2619567/Users.xlsx)

Файл сгенерированных данных для A_DOGOVOR:
[Dogovors.xlsx](https://github.com/Fenrik/Leshchev-Nikita/files/2619576/Dogovors.xlsx)
___

# 3. Результат заполнения таблиц

A_DOGOVOR:

![7](https://user-images.githubusercontent.com/18438169/49077804-d5144580-f26e-11e8-81d2-ed05f14bd070.PNG)

A_USER:

![5](https://user-images.githubusercontent.com/18438169/49077809-d80f3600-f26e-11e8-9d8e-4e02fbeb0a8b.PNG)
___

# 4. Примеры выполнения запросов

**Запрос ROLLUP по 1 атрибуту:**

![rollup 1](https://user-images.githubusercontent.com/18438169/49078054-929f3880-f26f-11e8-9a4f-2f3b491c3012.PNG)

![8](https://user-images.githubusercontent.com/18438169/49078071-9af77380-f26f-11e8-9ee7-73564a2a9799.PNG)

Файл с результатом: 
[ROLLUP по 1 атрибуту.txt](https://github.com/Fenrik/Leshchev-Nikita/files/2619614/ROLLUP.1.txt)

**Запрос ROLLUP по 2 атрибутам:**

![rollup 2](https://user-images.githubusercontent.com/18438169/49078230-093c3600-f270-11e8-96fe-2ffa7ad2380a.PNG)

![9](https://user-images.githubusercontent.com/18438169/49078239-0f321700-f270-11e8-8166-91b2b504adc3.PNG)

![10](https://user-images.githubusercontent.com/18438169/49078241-10634400-f270-11e8-9cc2-7f263531fc81.PNG)

Файл с результатом: 
[ROLLUP по 2 атрибутам.txt](https://github.com/Fenrik/Leshchev-Nikita/files/2619622/ROLLUP.2.txt)

**Запрос GROUPING:**

![grouping](https://user-images.githubusercontent.com/18438169/49078323-4ef8fe80-f270-11e8-93fd-d5cd85385b1e.PNG)

![11](https://user-images.githubusercontent.com/18438169/49078332-54eedf80-f270-11e8-900f-7ff61daee29e.PNG)

![12](https://user-images.githubusercontent.com/18438169/49078337-56b8a300-f270-11e8-8dc7-a9a0f5255685.PNG)

Файл с результатом: 
[GROUPING.txt](https://github.com/Fenrik/Leshchev-Nikita/files/2619627/GROUPING.txt)

**Запрос SUM:**

![sum](https://user-images.githubusercontent.com/18438169/49078352-5f10de00-f270-11e8-8cb3-26827722d92f.PNG)

![13](https://user-images.githubusercontent.com/18438169/49078358-61733800-f270-11e8-9875-20fb18cbbd19.PNG)

Файл с результатом: 
[SUM.txt](https://github.com/Fenrik/Leshchev-Nikita/files/2619629/SUM.txt)
___

# 5. Заключение

В результате работы:

* Развернута БД Oracle 11g;
* К БД Oracle 11g подключён Oracle SQL Developer;
* Созданы таблицы "A_DOGOVOR" и "A_USER" для предметной области - Интернет-провайдер;
* Сгенерированы и заполнены данные для таблиц БД; 
* Для таблиц "A_DOGOVOR" и "A_USER" было выполнено несколько запросов.

В работе было использовано следующие ПО:

* БД Oracle 11g;
* Oracle SQL Developer.
