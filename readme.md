# Автотест для тестирования сайта M2.ru

### Стек технологий:

>Java, Maven, Junit5, Selenide, Allure Reports

### Описание проекта:
Данный проект представляет собой автоматизированные тесты, 
написанные на Java с использованием Selenium WebDriver. 
Тесты проверяют функциональность веб-приложения по продаже квартир и аренде квартир.

### Структура проекта:
- `src`: содержит исходные коды автотестов на Java.
- `tests`: содержит классы с автотестами.
- `pages:` содержит классы с данными страницы
- `services:` содержит классы с сервисами
- `pom.xml`: содержит все необходимые зависимости
- `README.md`: текущий файл с описанием проекта.

### Предусловие:
Для корректной работы автотеста необходимо иметь установленный браузер FireFox.


Примечание: При работе с браузером Google Chrome срабатывает защита от бота.

### Сценарии тестирования:
- Проверка функционала покупки квартиры вторичного жилья.
- Проверка функционала аренды квартиры.
- Проверка функционала покупки квартиры в новостройке.

### Требования к окружению:
- Java 8 или выше
- Браузер FireFox.
- Драйвер для браузера FireFox.

### Доработки на 07.12.2023
- Привязать allure отчет
- Реализовать ввод суммы в тесте RentService
- Реализовать класс Новостройки с параметрами конструктора

