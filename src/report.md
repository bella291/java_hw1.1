# Отчёт о тестировании приложения Money Transfer

## Краткое описание

9.09.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 00:10:00 

В результате тестирования выявлен следующий дефект:
* [Баланс счета vip клиента отображается некорректно](https://github.com/bella291/java_hw1.1/issues/1#issue-991163861)

## Описание процесса тестирования

В качестве тестовых данных использовались данные из условия [задачи 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-1---money-transfer):
* текущий баланс счёта клиента - 2 000 000 000 рублей (два миллиарда рублей);
* сумма перевода - 500 000 000 рублей (пятьсот миллионов рублей);

Тестирование производилось в следующем окружении:
* Windows 10 Pro, x64
* Java Version 8 Update 301
* AdoptOpenJDK (HotSpot) version 11.0.11
