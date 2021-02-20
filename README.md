# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание

При переводе средств на счете клиента была получена неправильная итоговая сумма средств. На счету было 2 000 000 000, перевели на этот счет 500 000 000. Итоговая ссумма на счету должна была быть 2 500 000 000, но программа показала результат -1794967296. 
## Описание тестов

Было проведено функциональное тестирование.

## Результаты

1. Тест неуспешный
2. [Баг-репорт](https://github.com/AnastasiaMR/Money-Transfer/issues/1)


## Общие рекомендации

По итогам тестирования рекомендую использовать для переменной Total тип long. Так как у используемого типа int диапозон значений от -2 147 483 648 до 2 147 483 647.
