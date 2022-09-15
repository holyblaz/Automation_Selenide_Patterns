# Automation_Selenide_Patterns [![Build status](https://ci.appveyor.com/api/projects/status/31dtnkkxsx7tykcw/branch/main?svg=true)](https://ci.appveyor.com/project/holyblaz/automation-selenide-patterns/branch/main)

# Обучение в Нетологии.

## Курс Автоматизированное тестирование

## Тема: Patterns

Автоматизирование тестирования новой функции формы заказа доставки карты(приложение ```app-card-delivery.jar```)
с условием:

- если заполнить форму повторно теми же данными за исключением "Даты встречи", то система предложит перепланировать время встречи,
после нажатия по кнопке "Перепланировать" произойдёт перепланирование встречи:  

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/holyblaz/Automation_Selenide_Patterns.git
``` 
2. Открыть склонированный проект в Intellij IDEA
3. Открыть в терминале каталог ```artifacts```
4. Для запуска приложения ввести команду ```java -jar ./app-card-delivery.jar```
5. Для запуска в браузере ввести ссылку http://localhost:9999/
6. Запустить команду ```./gradlew test```
