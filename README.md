## Отчёт о тестировании Money Transfer

18.03.2021 было проведено тестирование приложения Money Transfer.

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
https://github.com/TakkiDakki/Number2.1/issues/1

##### В качестве тестовых данных использовались данные:

* Текущий баланс счёта клиента -  2_000_000_000
* Сумма перевода - 500_000_000

Рекомендую использовать переменную Long, так как у переменной Int максимальное значение 2147483647, в связи с чем сумма считается неверное.

Тестирование производилось в следующем окружении:

* openjdk version "11.0.10" 2021-01-19
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.10+9)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.10+9, mixed mode)

