# Отчёт о тестировании кода для валидации номера банковской карты

## Краткое описание

07.07.2021 - 09.07.2021 было проведено дымовое тестирование методом эквивалетного значения кода для валидации номера банковской карты.

На тестирование затрачено: 48 часов

В результате тестирования выявлены следующие дефекты:
* Bug 1  [American Express](https://github.com/DariaSeliverstova/java_1.1/issues/1)
* Bug 2  [Diners Club - Carte Blanche](https://github.com/DariaSeliverstova/java_1.1/issues/2)
* Bug 3  [Diners Club – International ](https://github.com/DariaSeliverstova/java_1.1/issues/3)
* Bug 4  [VISA](https://github.com/DariaSeliverstova/java_1.1/issues/4)

## Описание процесса тестирования
Было проведено тестировоние методом эквивалентного значения некорректных номеров банковских карт.
Было проведено тестирование на валидность сгинерированных валидных номеров следующих платежных систем: VISA, MasterCard,American Express,  Discover,  JCB , Diners Club - North America, Diners Club - Carte Blanche, Diners Club – International,  Maestro, Visa Electron, InstaPayment


В качестве тестовых данных использовались данные :
* Credit Card Number Generator & Validator  [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html).


Тестирование производилось в следующем окружении:
* MacBook Pro
* Java SE 11
