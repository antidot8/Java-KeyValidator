# Отчёт о тестировании KeyValidator

## Краткое описание

<24/03/2021> - <24/03/2021> было проведено тестирование приложения KeyValidator.

На тестирование затрачено: 1 час 30 минут.

В результате тестирования выявлены следующие дефекты:
* [Ключи из списка валидных ключей определяются как невалидные](https://github.com/antidot8/Java-KeyValidator/issues/1);
* [Ключи из списка невалидных ключей определяются как валидные](https://github.com/antidot8/Java-KeyValidator/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* 2 баг-репорта;
* 1 отчет о тестировании.

В качестве тестовых данных использовались данные <указать источник, откуда брались тестовые данные>:
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Тестирование производилось в следующем окружении:
* ОС Windows 7, x64,
* версия Java 11.0.10.
