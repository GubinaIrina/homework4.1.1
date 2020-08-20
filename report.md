# **Отчёт о тестировании KeyValidator**

## Краткое описание

20.08.2020 - 20.08.2020 было проведено тестирование документации, тестирование установки, тестирование совместимости приложения KeyValidator.

На тестирование затрачено: 4 часа

## В результате тестирования выявлены следующие дефекты:

1. [Ошибка в валидных ключах](https://github.com/GubinaIrina/homework4.1.1/issues/1#issue-683031153)

1. [Ошибка в невалидных ключах](https://github.com/GubinaIrina/homework4.1.1/issues/2#issue-683034353)

## Описание процесса тестирования

1. Открыть [Инструкцию по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
1. В соответсвии с инструкцией произвести установку OpenJDK для своей ОС
1. Открыть [Руководство по использованию KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
1. В соответсвии с руководством по использованию провести тестирование валидных и невалидных ключей

## В качестве тестовых данных использовались данные:

- [Инструкция по установке OpenJDK](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) 

Ожидаемый результат: приложение скачивается и устанавливается на ОС Windows, MacOS, Linux.

- [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Ожидаемый результат: приложение запускается без ошибок, совместимо с Java 11.
- [Приложение KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)

Ожидаемый результат:

 В результате работы вывод приложения для валидных ключей будет выглядеть следующим образом:

Result for 00000000-0000-0000-0000-000000000000: OK

Для невалидных ключей следующим:

Result for 00000000-0000-0000-0000-000000000001: FAIL

## Тестирование производилось в следующем окружении:

- версия и разрядность ОС: Windows 10, 64-bit
- версия Java: 11.0.8
