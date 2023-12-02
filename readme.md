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
- `pages:` содержит .....
- `services:` содержит .....
- `pom.xml`: содержит все необходимые зависимости
- `README.md`: текущий файл с описанием проекта.

### Предусловия
Для корректной работы автотеста необходимо иметь установленный браузер FireFox.

### Сценарии тестирования
Проверку функционала покупки квартиры вторичного жилья.
Проверка функционала аренды квартиры.
Проверку функционала покупки квартиры в новостройке.

### Требования к окружению
- Java 8 или выше
- Браузер FireFox.
- Драйвер для браузера FireFox.

### Доработки на 02.12.2023
- Реализовать ввод суммы в тесте RentService
- Реализовать параметры с конструктора в новом классе на прмиере 2-к квартиры
- Проработать желтые замечания
- Привязать Allure отчет
