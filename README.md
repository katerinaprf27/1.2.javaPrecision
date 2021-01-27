# Отчёт о тестировании бонусного приложения "Precision" #

## Краткое описание ##

27.01.2021 было проведено функциональное, позитивное тестирование установки бонусного приложения Precision.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие *дефекты*:

При вычислении бонусов в приложении, использовав переменную "double", получился неверный итог.

Тестирование производилось в следующем *окружении*:

* MacOS x64
* Java version "11.0.9.1"
* IntelliJ IDEA

## Описание тестов ##

Было проведено функциональное, позитивное тестирование установки приложения Precision. 

С целью проверки как работает оператор "сложение" и переменная "double" c числами 0.3 и 0.6.

## Результаты ##

Данное тестирование оказалось 100% неуспешным тестом.

*Ссылка на баг-репорт:*

* [При использовании переменной double выдается неверное значение #1](https://github.com/katerinaprf27/1.2.javaPrecision/issues/1)

При использовании переменной double при сложении данных чисел получилось неверное значение, неверный итог.
 ## Общие рекомендации ##

По итогам тестирования рекомендую при разработке подобного рода приложений, анализировать тип данных и подбирать подходящие переменные для того, чтобы приложение корректно работало.