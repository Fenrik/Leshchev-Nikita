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

