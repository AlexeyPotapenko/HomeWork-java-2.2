# Отчёт о тестировании Precision

## Краткое описание

16.07.2021 - 16.07.2021 было проведено функциональное тестирование дополнительных бонусов новым клиентам.

На тестирование затрачено: 3 часа

Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

[Тест-кейс](https://docs.google.com/spreadsheets/d/1AlKYIjc8tNUUDGFRJLfQ5j79sSi4fNZtNWJv1APkj6A/edit?usp=sharing)

В результате тестирования выявлены следующие дефекты:
[Некорректный рассчет бонуса для новых клиентов](https://github.com/AlexeyPotapenko/HomeWork-java-2.2/issues/1#issue-961716225)

В качестве тестовых данных использовались данные:

1. Текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)*;
2. Сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей);
3. переменная для хранения итогового значения - тип int;


В качестве тестовых данных использовались данные:
Текущий бонус - переменная типа double regularBonus равная 0.3 ;
Дополнительный бонус - переменная типа double specialBonus равная 0.6;
Итоговый бонус - переменная типа double равная regularBonus + specialBonus;

Тестирование производилось в следующем окружении:


Windows 10 pro 64x
<11.0.5>

