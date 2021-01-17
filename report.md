# Отчет о тестировании Credit Card Number Validator

## Краткое описание:

<14.01.2021> - <14.01.2021> было проведено позитивное и негативное функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: <2 часа>

В результате тестирования выявлены следующие дефекты:

* [не распознается карта American Express](https://github.com/rasul230885/Java-2/issues/1#issue-786277646)
* [не распознается карта Diners Club - Carte Blanche](https://github.com/rasul230885/Java-2/issues/2#issue-786284491)
* [не распознается карта Diners Club - International](https://github.com/rasul230885/Java-2/issues/3#issue-786293524)

## Описание процесса тестирования

В качестве тестовых данных использовались данные Credit Card Number Generator & Validator:
* Visa:
4532448698289659 ожидаемый результат ОК
* MasterCard:
5188948223216287 ожидаемый результат ОК
* American Express:
378694280608476 ожидаемый результат ОК
* Discover:
6011996523870080 ожидаемый результат ОК
* JCB:
3543584461663560 ожидаемый результат ОК
* Diners Club - North America:
5422283628539505 ожидаемый результат ОК
* Diners Club - Carte Blanche:
30403044853612 ожидаемый результат ОК
* Diners Club - International:
36141379986474 ожидаемый результат ОК
* Maestro:
6761271344551711 ожидаемый результат ОК
* Visa Electron:
4508597554462808 ожидаемый результат ОК
* InstaPayment:
6395375665709958 ожидаемый результат ОК

### Тестирование производилось в следующем окружении:
* ASUS, OS Windows 10, 64-bit
* java 11
* IntelligIdea 2020.3
