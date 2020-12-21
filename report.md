# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

<21.12.2020> - <21.12.2020> было проведено юнит-тестирование класса Credit Card Number Validator.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:

* Дефекты не выявлены


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Руководство использования Установка IntelliJ IDEA https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md
* https://github.com/netology-code/javaqa-homeworks/tree/master/intro
* Credit Card Number Generator & Validator https://www.freeformatter.com/credit-card-number-generator-validator.html


В качестве тестовых данных использовались данные:


* Ключ 2221008815190824 - Ожидаемый результат: ОК Полученный результат: ОК
* Ключ 222100881519082 -  Ожидаемый результат: FAIL Полученный результат: FAIL
* Ключ 222100881519082b - Ожидаемый результат: FAIL Полученный результат: FAIL
* Ключ 2221008815190821 - Ожидаемый результат: FAIL Полученный результат: FAIL
* Ключ  - Ожидаемый результат: FAIL Полученный результат: FAIL
* Ключ 5171768806561662 - Ожидаемый результат: ОК Полученный результат: ОК



![Results](/assets/images/jt-1.2_homework.PNG) 


Тестирование производилось в следующем окружении:
* WINDOWS 10 64
* openjdk version "11.0.9.1" 2020-11-04
* IntelliJ IDEA Community Edition 2020.03
