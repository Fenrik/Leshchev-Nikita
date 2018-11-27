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
Для генерации данных был использовался онлайн ресурс: https://www.mockaroo.com.

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





