# Отчёт о тестировании Credit Card Number Validator
## Краткое описание

10.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 5 часов

В результате тестирования выявлены следующие дефекты (https://github.com/AnitaNuares/Java_1.1/issues/1):

    - карта с номером из 14 цифр, фактический результат FAIL 
    - карта с номером из 15 цифр, фактический результат FAIL 
    - карта с номером из 19 цифр, фактический результат FAIL

## Описание процесса тестирования

В качестве тестовых данных использовались данные генератора валидных номеров карт с https://www.freeformatter.com/credit-card-number-generator-validator.html:

    - карта с номером из 14 цифр, ожидаемый результат OK
    - карта с номером из 15 цифр, ожидаемый результат OK
    - карта с номером из 16 цифр, ожидаемый результат OK
    - карта с номером из 19 цифр, ожидаемый результат OK

Тестирование производилось в следующем окружении:

   - Windows 10 Home 64-разрядная версия 2004 
   - Java версия 11.0.10