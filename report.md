# Отчёт о тестировании программы Credit Card Number Validator

## Краткое описание

27.10.20 - 28.10.20 было проведено Smoke testing программы **Credit Card Number Validator** методами:
* эквиваленных значений
* AD-HOC .

На тестирование затрачено: 2 ч.

В результате тестирования выявлены следующие дефекты:
1. [Bug#1](https://github.com/LexinFrom02/Ex1.1-T2/issues/1)
1. [Bug#2](https://github.com/LexinFrom02/Ex1.1-T2/issues/2)
1. [Bug#3](https://github.com/LexinFrom02/Ex1.1-T2/issues/3)
1. [Bug#4](https://github.com/LexinFrom02/Ex1.1-T2/issues/4)

---
## Описание процесса тестирования

#### В процессе тестирования использовались следующие артефакты:
* Руководство по установке IntelliJ IDEA
* Сервис генерирования валидных номеров кредитных карт [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

#### В качестве тестовых данных использовались:

1. Валидные номера кредитных карт:
    * 4916456851182633 (VISA)
    * 5577962774521374 (MASTERCARD)
    * 345620261087216 (AMEX)
    * 0604575550525498 (MAESTRO)
    * 6011784418826866 (DISCOVER)
    * 6011239635821473656 (DISCOVER)
    * 3533918909645535832 (JCB)
    * 30535234132461 (DINER CLUB)
    * 6398123516925556 (ISTAPAYMENT)
1. Невалидные номера кредитных карт:
    * 1
    * "-"
    * " " (значение незаполнено)
    * 12345678910111213
    * ?
    * card
    * шестнадцатьььььь


---
## Тестирование производилось в следующем окружении:
* OS: Windows 7 Professional, Service pack 1, 64-bit
* Java version: OpenJDK 11.0.9
* intelliJ IDEA 2020.2.3 (Community edition) Build #IC-202.7060.26