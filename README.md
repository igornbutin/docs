Здесь описаны тестовые проекты. Все файлы хранятся на Google Drive и открыты к просмотру.
# Содержание
- [Bloghouse — платформа для ведения блогов](#Bloghouse)
- [ShopBugred — тестовый интернет-магазин](#ShopBugred)
- [ShopBugred.API — api тестового интернет-магазина](#shopbugredapi)

## Bloghouse
*Платформа для ведения блогов — https://blog-house.pro/*
### Задача
Написать тест-кейсы и проверить:
1. Проверить, что регистрация без заполнения обязательных полей невозможна
2. Проверить, что регистрация с некорректным e-mail невозможна
3. Проверить, что регистрация без согласий невозможна
4. Проверить, что регистрация с неверным проверочным кодом невозможна
5. Проверить регистрацию с корректными данными
6. Проверить, что создание автора без заполнения обязательных полей невозможно
7. Создание автора с заполнением обязательных полей
8. Вход с существующим аккаунтом возможен
9. Вход с несуществующим аккаунтом заблокирован
10. Вход с неверным паролем заблокирован
11. Проверить восстановление пароля с существующим аккаунтом
12. Проверить, что восстановление пароля с несуществующим аккаунтом невозможно

### Реализация

**Тест-кейсы:**
https://docs.google.com/spreadsheets/d/1E9cKGQAQhurjS9xqN69dKriDIz6agZfn/edit?usp=sharing&ouid=108529313705024441144&rtpof=true&sd=true

![Bloghouse  Test case](https://user-images.githubusercontent.com/89230342/178154064-d4dcb472-7041-4e5a-9b2d-9a88d3cb0e12.png)

**Баг-репорты:**
https://docs.google.com/spreadsheets/d/1SMGifHDpGiAiXUg7YyN7HNQ22EZsrw6vhaEHGKZ8j8k/edit?usp=sharing

![Bloghouse  Bug-report](https://user-images.githubusercontent.com/89230342/178154068-37c686e3-11eb-4ba7-8c26-da9b9d9dc3db.png)


## ShopBugred
*Тестовая площадка в виде небольшого интернет-магазина — http://shop.bugred.ru/*
### Задача
Составить тестовую документацию на функциональные блоки магазина "Регистрация" и "Авторизация".

### Нюансы
- В отсутствии полного доступа к оригинальной документации, пришлось написать некоторый список требований, от которого можно отталкиваться.
- Это тестовая площадка. Через некоторое время она стирает из базы добавленные данные. Все проверки составлялись с учетом данного факта.

### Реализация

**Требования:**
https://docs.google.com/spreadsheets/d/1Rr_MCV6WiGQEtJs7wxssLVMpH-daSr2b/edit?usp=sharing&ouid=108529313705024441144&rtpof=true&sd=true

![Bugred Требования](https://user-images.githubusercontent.com/89230342/191966741-30a333c7-2ce5-4251-a35f-30f37320f7e2.png)

**Тест-кейсы:**
https://docs.google.com/spreadsheets/d/1fw-TAHFWN-ko4Y34qKz_3l16kNxy2vnK/edit?usp=sharing&ouid=108529313705024441144&rtpof=true&sd=true

![Bugred Тест-кейсы](https://user-images.githubusercontent.com/89230342/191966788-e11f0188-2016-4f98-97fa-fbea2bb628a4.png)

**Баг-репорты:**
https://docs.google.com/spreadsheets/d/1ZAhNgeb7fdHBCv3s2OaEW-STKroTwaCQ_8Hz6ZgRMG4/edit?usp=sharing

![Bugred Баг-репорты](https://user-images.githubusercontent.com/89230342/191966868-2e7d465c-2ba3-49f2-9c2e-a5ad38be97f3.png)


## ShopBugred.API
*Тестовая площадка в виде небольшого интернет-магазина — http://shop.bugred.ru/*
### Задача
Основываясь на [документе](https://docs.google.com/document/d/1YZgmzLktexO5irB7sc_uaClyhJlbUGPX_ZtYLYEgvQI/edit?usp=sharing) составить тест-кейсы и проверить:
1. Позитивные сценарии API
2. Негативные сценарии API

### Реализация
**Тест-кейсы:**
https://docs.google.com/spreadsheets/d/1idALnVhkwebVW_GHq2bkwv5_Qn3yDcOBCZybR_Uc66s/edit?usp=sharing

![Bugred API Тест-кейсы](https://user-images.githubusercontent.com/89230342/191968547-a0452e20-a650-49fc-bd82-bc6969ae9792.png)

**Баг-репорты:**
https://docs.google.com/spreadsheets/d/1xRPKfYrKL8KmnAyU3St6VZ3ezHw2sbypJ-n-NLaKDw0/edit?usp=sharing

![Bugred API Баг-репорты](https://user-images.githubusercontent.com/89230342/191968599-6d2977c6-b607-4111-adeb-31f6dc4da762.png)
