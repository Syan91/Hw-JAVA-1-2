# Отчет о тестировании приложения Credit Card Number Validator

07.07.2020 - 08.07.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 3 ч

  В результате тестирования выявлен следующий дефект: 
* [Bug Result FAIL при введении валидного номера карты](https://github.com/Syan91/Hw-JAVA-1-2/issues/1)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
*  [Инструкция по установке приложения InteliJ IDEA и запуску Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)
* [Тестовые данные](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers)

В качестве тестовых данных использовались [данные](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers) :
* 4916523062564974245 (Валидный номер карты) - Result is OK
* 4929346351599433 (Валидный номер карты) - Result is OK
* 49293463515994332 (Валидный номер карты) - Result is OK
* 492934635159943333 (Валидный номер карты) - Result is OK
* 49293463515994333333 (Невалидный номер карты) - Result is FAIL
* 492934635159943 (Невалидный номер карты) - Result is FAIL

*Тестирование производилось в следующем окружении:*
* Macbook Pro 13, Os X El Capitan версия 10.11.6, 
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
