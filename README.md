# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17.11.2020 было проведено тестирование установки, тестирование на совместимость, дымовое тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* <a href="https://github.com/fromkerch/task2-IDE-/issues/1">Некорректная обработка валидных банковских карт состоящих из 19 цифр</a>
* <a href="https://github.com/fromkerch/task2-IDE-/issues/2">Банковские карты платежной системы МИР не проходят проверку</a>


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* <a href="https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md">Руководство по установке IntelliJ IDEA</a>




В качестве тестовых данных использовались данные:
* Приложение IntelliJ IDEA. Ожидаемый результат: запускается и работает согласно руководству использования.
* <a href="https://www.freeformatter.com/credit-card-number-generator-validator.html">Генератор валидных номеров карт</a>


Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* java version "11.0.5"
