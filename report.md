# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

17.11.2020г  было проведено функциональное тестирование приложения Credit Card Number Validator  и Руководства по  установке Intellij IDEA.

На тестирование затрачено: 4ч

В результате тестирования выявлены следующие дефекты:
1. [В Руководстве по установке IntelliJ IDEA отсутствует  шаг выбора языка](https://github.com/kos-vkg/Java_1.1_Task2-Credit-Card-Number-Validator/issues/3#issue-745633847)
1. [В Руководстве по установке IntelliJ IDEA  описан шаг 8, который реально отсутствует](https://github.com/kos-vkg/Java_1.1_Task2-Credit-Card-Number-Validator/issues/4#issue-745671892) 
1. [Неверная обработка карты Maestro](https://github.com/kos-vkg/Java_1.1_Task2-Credit-Card-Number-Validator/issues/1#issue-745591508)
1. [Неверная обработка карты American Express](https://github.com/kos-vkg/Java_1.1_Task2-Credit-Card-Number-Validator/issues/2#issue-745594829)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Руководство по установке Intellij IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

В качестве тестовых данных использовались данные источника:

* [Таблица тестовых карт (валидные номера карт)](https://developer.rbk.money/docs/payments/refs/testcards/#_2)
	* 4242424242424242   Visa 	
	* 5555555555554444   MasterCard	
	* 586824160825533338 Maestro
	* 2201382000000013   MIR 	 
  
* [Генератор случайных кредитных карт(валидные номера карт)](https://tools.seo-zona.ru/credit-card-generator.html)
	* 4763 6941 6224 3314 Visa 
	* 5297 5514 8885 6116 MasterCard 	
	* 3709 6690 1926 190 American Express
	* 6011 1621 1634 7347  Discover 	 
   * 3528 6065 4157 8184   JCB

Тестирование производилось в следующем окружении:
* Windows7_64 Prof
* IntelliJ IDEA 2020.2.3 (Community Idition) 